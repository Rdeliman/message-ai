---
title: Message AI privacy policy
---


Last updated 7 October 2026. Written from what the app does today; every sentence here matches a screen or a notice
in the app. When a feature changes what leaves the phone, this page changes with it.

## The short version

Message AI reads your texts on your phone to answer questions about them, suggest replies and remind you who is
waiting. It keeps everything on the phone. The only time anything leaves is when you ask the AI something, and then it
goes only to the AI company you chose and gave your own key for. Nobody who makes Message AI ever receives your
messages, your contacts or your keys. There is no account, no server of ours, no analytics and no advertising.

## What stays on the phone

- **Your messages.** SMS and MMS read from the phone's own store, and, if you turn notification access on, messages the
  app sees arrive in WhatsApp. They are kept in an index in the app's private storage, excluded from cloud backup and
  device-to-device transfer.
- **Your contacts** (names for the numbers you text), **your call history** (only if you allow it, to know when you
  talked instead of texting), **voice messages turned into text** (Android's own on-device speech recognizer; the audio
  never leaves the phone).
- **Your chats with the AI and their answers**, what the app learned about how you write and about each person, the
  notes you wrote in About you, and the app's own usage log (tokens and estimated cost per question).
- **Your API keys**, wrapped with a key that lives in the Android Keystore and cannot be exported.

## What leaves the phone, and when

Nothing leaves until you ask the AI something, with one exception you turn on yourself: with "Prepare reply ideas as
texts arrive" on (off unless you turn it on, under Settings › Messages and alerts), each new message goes to your AI
company as it arrives, so the alert can offer reply ideas; with "Full reply ideas" on as well, what the app has noted
about that person and your About you go along. Otherwise:

- **A question in Ask AI, Reply ideas, a draft, Catch me up.** The AI searches the on-device index and the messages it
  opens are sent to the AI company of that chat, including what others wrote to you. You see every lookup under the
  answer ("Sources · what left the phone"). Follow-up questions re-send the chat so far.
- **Learning.** About 1,000 texts you sent (never what others wrote) go once to the model, with names and numbers
  taken out, to learn how you write. The first time the AI writes for someone, up to 300 of your texts to them and your
  newest 150 texts with them, theirs too, go once, to learn how you text them and a few lasting things about them;
  again after 100 new texts, at most twice a year. Since the "Finish setting up" steps, nothing is learned until you
  tap Learn now, and that step shows the cost first.
- **Photos.** Only a photo you tap to let the AI look at, once; the app shows you the photos first and waits for your
  OK.
- **Web search**, if you turn it on: only the search words, never your texts, to the search company named in Settings.
- **OpenRouter's record of a call**: the call's own id, to read what OpenRouter charged for it. Never any text.

Each of those goes over an encrypted connection (HTTPS) directly from your phone to that company. We never see it.

## Which companies, and what they do with it

You choose the company by adding its key. The app tells you how each one treats what it receives before the key is
saved, and again under Settings › Privacy and data › What leaves the phone:

- **Anthropic (Claude):** not used for training by default; deleted within 30 days.
- **Google (Gemini):** on the free tier, prompts may be reviewed and used to improve Google products; the paid tier is
  not used that way.
- **Nous Research:** a gateway that passes prompts to the company that runs the model, and may store and train on them
  unless Privacy Mode is on in the Nous portal.
- **OpenRouter:** a gateway; prompts go on to the company that runs the model you pick, and your OpenRouter privacy
  settings decide whether companies that may train on them are used. OpenRouter does not store them unless you turn
  that on.
- **OpenAI:** not used for training unless your organization opts in; kept up to 30 days in abuse-monitoring logs,
  where flagged ones may be reviewed. Message AI sends with storage off.
- **Chatbox AI:** a gateway; prompts go to Chatbox AI, which passes them to the company that runs the model you pick
  (OpenAI, Anthropic, Google, DeepSeek, Moonshot, xAI, Alibaba and others). Chatbox says it keeps nothing after the
  answer; the model company's own rules apply there.

Their own policies apply once a message reaches them. Message AI has no agreement with any of them beyond the key you
hold.

## What the app never does

- Never sends a message by itself. A reply you choose is handed to your messaging app, and you send it there.
- Never sends your messages, contacts, photos or keys to us, or to anyone you did not pick by adding a key.
- Never runs analytics, advertising or tracking. There is no account and no sign-in.
- In the demo ("Try a demo first"), nothing leaves the phone at all: three sample people, prepared answers.

## Permissions, and why each is asked

- **SMS and MMS:** to read your texts into the index. Required for the app to be useful with your own messages.
- **Contacts:** names for the numbers you text, and the people you link.
- **Notification access** (optional): to see WhatsApp messages as they arrive. Nothing is sent back through it unless
  you tap Send on a reply, and then the reply goes through WhatsApp's own notification reply.
- **Call log** (optional): to know when you talked instead of texting.
- **Notifications:** for the app's own reminders and alerts.

## Your controls

- **Settings › Privacy and data:** What leaves the phone, Delete all chats, Delete everything (the index, all chats and
  every key are removed and the app returns to setup).
- **Settings › AI:** remove any key at any time; chats on that company stop at once.
- **Uninstalling the app** removes everything it kept.

## Children

Message AI is not directed at children under 13 and does not knowingly collect anything from them.

## Changes and contact

Changes to this page are dated at the top. Questions: open an issue on the project's GitHub page, or write to
Ray Deliman, Raymond.deliman@gmail.com.
