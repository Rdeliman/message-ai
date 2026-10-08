---
title: Message AI privacy policy
---


Last updated 7 October 2026. Written from what the app does today; every sentence here matches a screen or a notice
in the app. When a feature changes what leaves the phone, this page changes with it.

## The short version

Message AI reads your texts on your phone to answer questions about them, suggest replies and remind you who is
waiting. It keeps everything on the phone. The only time anything leaves is when you ask the AI something, or turn on
"Prepare reply ideas as texts arrive", and then it goes only to the AI company you chose and gave your own key for.
Your key alone also goes to that company, to check it and to read its models, limits and costs: never any text.
Nobody who makes Message AI ever receives your messages, your contacts or your keys. There is no account, no server of
ours, no analytics and no advertising.

## What stays on the phone

- **Your messages.** SMS and MMS read from the phone's own store, and, if you turn notification access on, messages the
  app sees arrive in WhatsApp. They are kept in an index in the app's private storage, excluded from cloud backup and
  device-to-device transfer.
- **Your contacts** (names and birthdays for the numbers you text) and **your call history** (only if you allow it, to
  know when you talked instead of texting). Neither list is ever sent; a name, an approximate age or a call's time and
  length can go with a question, as described below.
- **Voice messages turned into text** (Android's own on-device speech recognizer; the audio never leaves the phone).
- **Your chats with the AI and their answers**, what the app learned about how you write and about each person, the
  notes in About you, and the app's own usage log (tokens and estimated cost per question). What My Voice and About
  you hold goes along with what the AI writes for you while each is on, and what was noted about a person with what it
  writes about them, as described below; the texts they were learned from do not.
- **Your API keys**, wrapped with a key that lives in the Android Keystore and cannot be exported.

## What leaves the phone, and when

Nothing leaves until you ask the AI something, with one exception you turn on yourself: with "Prepare reply ideas as
texts arrive" on (off unless you turn it on, under Settings › Messages and alerts), each new message goes to your AI
company as it arrives, with up to your last 20 texts with that person (in a WhatsApp chat, up to five messages before
it), so the alert can offer reply ideas; with "Full reply ideas" on as well, what the app has noted about that person
and your About you go along. Otherwise:

- **A question in Ask AI, Reply ideas, a draft, Catch me up.** The AI searches the on-device index and the messages it
  opens are sent to the AI company of that chat, including what others wrote to you. You see every lookup under the
  answer ("Sources · what left the phone"). Follow-up questions re-send the chat so far.
- **Your first name**, if you typed one (Settings › You and your voice), goes with questions, reply ideas and Catch me
  up, so the AI can refer to you.
- **Names and ages.** Each message the AI reads goes with its sender's name as your contacts have it, or the number
  when there is no contact. When a person's birthday is known (typed by you, or from your contacts), questions and reply
  ideas about them say roughly how old they are ("about 12", never the date), and reply ideas on the day say it is their
  birthday. Your contact list itself is never sent.
- **Calls.** Catch me up sends the calls with that person in the stretch it covers; Reply ideas, a call after their last
  message; a question that reads a WhatsApp chat, the calls in it: when each was, how long it lasted, which way it
  went and whether it was missed. They come from your call history, if you allowed it, and from WhatsApp's call
  notifications. Never the number, never any audio, never the rest of your call history.
- **My Voice.** While Use My Voice is on, what the app learned about how you write (a short description and a few
  example lines of yours) goes along with reply ideas, drafts and tone changes; the texts it learned from do not.
- **About you.** While Use About you is on, its notes go with reply ideas, drafts, Ask AI and Catch me up (and with an
  alert's ideas when Full reply ideas is on); the AI is told never to put them in a web search.
- **About them.** Who a person is to you, your note about them and their related people, as you set them in People,
  go with questions, reply ideas, tone changes and Help me say it about them, and, while Use My Voice is on, how you
  text them. Their About (your notes and what the app learned from your texts with them) goes with reply ideas on
  screen and Help me say it, and with an alert's ideas only when Full reply ideas is on.
- **A report you email.** If you report an AI answer (press and hold it, Report this answer), the report stays on the
  phone under Settings › Privacy and data › Reports until you choose Email the developer or Email all reports. That
  opens your mail app, addressed to the address at the bottom of this page, with the report filled in: when, which
  chat and answer, the model and company, what was wrong and the note you typed. Never the messages the answer
  read. You see the text before anything is sent, and you send it from your mail app.
- **Learning.** About 1,000 texts you sent (never what others wrote) go once to the model, with names and numbers
  taken out, to learn how you write. About you learns from up to 300 of your own newest texts and WhatsApp messages
  the same way, only what you sent, to note lasting facts about you; again after 100 new ones, at most twice a year.
  The first time the AI writes for someone, up to 300 of your texts to them and your newest 150 texts with them,
  theirs too, go once, to learn how you text them and a few lasting things about them; again after 100 new texts, at
  most twice a year. Since the "Finish setting up" steps, nothing is learned unless you tap Learn now, or a person's
  own Learn button on their page (About you and My Voice have their own too), and each shows the cost first.
- **Photos.** Only a photo you tap to let the AI look at: for that request, and again for More ideas and tone changes
  in the same panel. The app shows you the photos first and waits for your OK.
- **Web search**, which asks you first by default (or runs on its own if you set it to Automatic): only the search
  words, never your texts, to the search company named in Settings.
- **OpenRouter's record of a call**: the call's own id, to read what OpenRouter charged for it. Never any text.
- **Your key alone**: when the app lists a company's models, reads your OpenRouter key's limits, or reads OpenAI's
  costs with an admin key, only the key goes, never any text.

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

- Never sends a message without your confirm. A reply you choose goes out through your messaging app: through its own
  Reply on the notification once you tap Send, or opened there with the text filled in for you to send.
- Never sends your messages, contacts, photos or keys to us, or to anyone you did not pick by adding a key.
- Never runs analytics, advertising or tracking. There is no account and no sign-in.
- In the demo ("Try a demo first"), nothing leaves the phone at all: three sample people, prepared answers.

## Permissions, and why each is asked

- **SMS and MMS:** to read your texts into the index. Required for the app to be useful with your own messages.
- **Contacts:** names and birthdays for the numbers you text, and the people you link.
- **Notification access** (optional): to see WhatsApp messages as they arrive. Nothing is sent back through it unless
  you tap Send on a reply, and then the reply goes through WhatsApp's own notification reply.
- **Call log** (optional): to know when you talked instead of texting.
- **Notifications:** for the app's own reminders and alerts.

## Your controls

- **Settings › Privacy and data:** What leaves the phone, Reports (answers you reported: email one or all, delete
  any time), Delete all chats, Delete everything (the index, every chat, every key, My Voice, About you, your people
  and their links, your tones, captured messages, reminders, the AI spending log, setup progress and every report are
  removed and the app returns to setup; your first name stays).
- **Settings › AI:** remove any key at any time; chats on that company stop at once.
- **Uninstalling the app** removes everything it kept.

## Children

Message AI is not directed at children under 13 and does not knowingly collect anything from them.

## Changes and contact

Changes to this page are dated at the top. Questions: open an issue on the project's GitHub page, or write to
Ray Deliman, Raymond.deliman@gmail.com.
