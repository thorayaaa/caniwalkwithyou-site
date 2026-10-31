---
layout: default
title: support
permalink: /support/
description: help with can i walk with you? - and how to reach us.
---

# support

need help, found something broken, or want to report something? email <a href="mailto:{{ site.contact_email }}">{{ site.contact_email }}</a>. we read everything, and we'll get back to you as soon as we can.

## common questions

### how does a talk-walk work?
**talking:** tap "talk" (the round red button), read "talk on your walk", then tap "start walking". lock your phone and walk. tap "mark spot" when you stop somewhere, and "pass the mic" to ask the listener something - both are on your lock screen too. when you finish, name it, add photos, and choose who hears it.

**listening:** on the "listen" tab, pick a walk, tap "start walking with ...", then "tap to start listening". at each pass of the mic it's your turn - answer out loud, or skip. at the end you choose who hears what you said.

new here? "a minute with thoraya" on the listen tab is a one-minute practice walk.

### who hears what I recorded?
you choose, every time, after the walk. a talk-walk: just you, or everyone. an answer: keep it for yourself, send it to the talker, or share it publicly under their walk. either way, your @handle or anonymous, your own voice or a changed one.

### why can I only keep a walk for myself?
talk-walks are about walking. if a walk (or your walk with someone) barely moved, it can only be kept for yourself. if walking isn't possible for you, turn on "walking isn't possible for me" in settings - no need to explain - and your walks and answers post like everyone else's.

### who can see that I walked with someone?
a walk's page shows how many people walked it. only answers shared publicly are listed, with your name, or "anonymous" if you went anonymous. answers kept for yourself or sent only to the talker are counted but never named.

### why does it say "checking your walk"?
everything shared with others is turned into text and checked against our community rules before anyone else hears it. it usually takes a minute. if part of it can't be shared, the app shows you the moment and why, and lets you cut that part, keep it just for you, or ask a person on our team to look.

### I forgot my password
on the sign-in screen, tap "forgot password?" and enter your email or handle. we'll email you a code to set a new one. accounts made with Sign in with Apple don't have a password - just sign in with Apple again.

### I didn't get my code
check your spam or promotions folder, then tap "send a new code" on the code page (you can ask for a new one once a minute). if a sign-up code is never typed, the sign-up is deleted after 7 days and you can start again.

### how do I change my email or password?
your profile → ⋯ → settings → "change email" or "change password".

### how do I make my profile private?
your profile → ⋯ → settings → private profile. then only people you approve see your walks and your name.

### the app can't hear me / doesn't know where I am
recording and walking with someone need the microphone: Settings → Privacy & Security → Microphone → can i walk with you?. a walk's path needs location: Settings → Privacy & Security → Location Services → can i walk with you?. the app only follows your location while you record or listen to a walk.

### my buttons aren't on the lock screen
turn on Live Activities: Settings → can i walk with you? → Live Activities.

### I'm not getting notifications
check they're on in the app (your profile → ⋯ → settings → notifications) and on your iPhone (Settings → Notifications → can i walk with you?).

### I can't tap "create my account"
tick the box under it first: "i agree to the terms and privacy policy, and i'm 18 or older." Sign in with Apple waits for the same box. can i walk with you? is only for people 18 and over.

### how do I report or block someone?
tap "⋯" on a walk, an answer or a profile, then "report" - pick a reason and add details if you like - or "block". reports come straight to us. we review reports and remove anything that breaks our rules. the person is never told who reported them.

### how do I stop the walk club emails?
tap "unsubscribe" at the bottom of any of them - one tap and you're off the list.

### how do I delete a walk, or my account?
a walk: open it, "⋯" → delete. your account: your profile → ⋯ → settings → delete account, then type "delete". deleting removes the recordings too. our [privacy policy](/privacy/#deleting-your-account) explains exactly what's removed and what's kept.

<a id="takedown"></a>

## a takedown request

not on the app, and a walk has your voice in it without your agreement, uses your work, or something else is wrong? tell us here. it comes straight to the same inbox as reports in the app, and we'll reply by email.

<style>
  #takedown-form label { display: block; margin: 16px 0 6px; font-weight: 700; }
  #takedown-form input[type=email], #takedown-form input[type=text], #takedown-form textarea { width: 100%; font: inherit; font-size: 16px; color: var(--ink); background: #fff; border: 1px solid var(--line); border-radius: 10px; padding: 10px 12px; }
  #takedown-form textarea { min-height: 110px; resize: vertical; }
  #takedown-form .choice { display: flex; align-items: center; gap: 10px; min-height: 44px; font-weight: 400; margin: 0; }
  #takedown-form .choice input { width: 20px; height: 20px; accent-color: var(--red); }
  #takedown-form .trap { position: absolute; left: -10000px; width: 1px; height: 1px; overflow: hidden; }
  #takedown-result { font-weight: 700; }
</style>

<p id="takedown-result" role="status" hidden></p>
<form id="takedown-form" method="post" action="https://pencwliltbpwagjteugt.supabase.co/functions/v1/takedown-request">
  <label for="td-email">your email</label>
  <input id="td-email" name="email" type="email" autocomplete="email" maxlength="254" required>
  <label for="td-where">the walk's link, or the talker's name</label>
  <input id="td-where" name="where" type="text" maxlength="500" required>
  <fieldset style="border:0;padding:0;margin:16px 0 0;">
    <legend style="font-weight:700;padding:0;">what's wrong?</legend>
    <label class="choice"><input type="radio" name="reason" value="recorded" required> recorded without agreeing</label>
    <label class="choice"><input type="radio" name="reason" value="copyright"> copyright</label>
    <label class="choice"><input type="radio" name="reason" value="other"> something else</label>
  </fieldset>
  <label for="td-details">anything else we should know (optional)</label>
  <textarea id="td-details" name="details" maxlength="2000"></textarea>
  <div class="trap" aria-hidden="true"><label for="td-website">leave this empty</label><input id="td-website" name="website" type="text" tabindex="-1" autocomplete="off"></div>
  <input type="hidden" name="t" id="td-t">
  <button type="submit" class="pill" id="td-send">send</button>
</form>
<noscript><p class="quiet">this form needs javascript turned on. you can also write to <a href="mailto:{{ site.contact_email }}">{{ site.contact_email }}</a>.</p></noscript>
<p class="quiet">for copyright, include the details in our <a href="/terms/#copyright">terms</a> (what you own, where it is, and the two statements). we only use your email to answer you.</p>
<script>
  (function () {
    document.getElementById('td-t').value = String(Date.now());
    var said = { sent: "sent - thank you. we'll look at it and reply by email.", check: 'please add your email, the walk, and what\'s wrong.', limited: 'too many requests just now - try again later, or write to us.', error: "that didn't send. please try again, or write to us." };
    var r = new URLSearchParams(location.search).get('takedown');
    if (r && said[r]) { var p = document.getElementById('takedown-result'); p.textContent = said[r]; p.hidden = false; }
    document.getElementById('takedown-form').addEventListener('submit', function () { document.getElementById('td-send').disabled = true; });
  })();
</script>

## something unsafe?

we don't monitor walks and can't respond to emergencies. if you or someone else is in danger, call your local emergency number.

need to talk to someone now? in the US, call or text 988 (Suicide & Crisis Lifeline). outside the US, find your country's free helpline at [findahelpline.com](https://findahelpline.com). it's also in the app: settings, and every "⋯" menu.

to report something in the app, use "⋯" → report, or write to <a href="mailto:{{ site.contact_email }}">{{ site.contact_email }}</a>. our [safety tips](/safety/) are worth a read.

## more

- [safety tips](/safety/)
- [privacy policy](/privacy/)
- [terms](/terms/)
