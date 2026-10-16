---
title: Message AI privacy policy
---

Last updated 15 October 2026. Written from what the app does today; every sentence here matches a screen or a notice
in the app. When a feature changes what leaves the phone, this page changes with it.

## The short version

Message AI reads your texts on your phone to answer questions about them, suggest replies and remind you who is
waiting. It keeps everything on the phone. The only time anything leaves is when you ask the AI something, turn on
"Prepare reply ideas as texts arrive", or save a scheduled message, and then it goes only to the AI company you chose
and gave your own key for, or to an address you set yourself.
Your key alone also goes to that company or address, to check it and to read its models, limits and costs: never any
text.
Nobody who makes Message AI ever receives your messages, your contacts or your keys. There is no account, no analytics
company and no advertising. The one thing that can come to us is a beta tester's diagnostics log, only if they turn
"Share diagnostics (beta)" on: what the app did, never what anyone wrote, and what they choose to send with Report a
problem or Send feedback (below).

## What stays on the phone

- **Your messages.** SMS and MMS read from the phone's own store, and, if you turn notification access on, messages the
  app sees arrive in WhatsApp. They are kept in an index in the app's private storage, excluded from cloud backup and
  device-to-device transfer.
- **Messages you import yourself:** a WhatsApp chat you export and share to the app, and an iMessage history from an old
  iPhone (a file a converter on your own computer makes from the iPhone's backup, which you copy to the phone and share
  to the app). The file is read on the phone and its copy is deleted once read (an iPhone history's when its import
  finishes); the messages are kept like the others. Photos and videos are not in the file. Nothing is sent when you
  import; the messages go to your AI company only as any messages do, below. The converter runs on your computer only
  and sends nothing anywhere.
- **Your contacts** (names and birthdays for the numbers you text and the contacts you add to People) and **your call
  history** (only if you allow it, to know when you talked instead of texting). Neither list is ever sent; a name, an
  approximate age or a call's time and length can go with a question, as described below.
- **Voice messages turned into text** (Android's own on-device speech recognizer; the audio never leaves the phone).
- **WhatsApp voice messages turned into text on the phone too**, if you allow it: Message AI reads them from the folder
  where WhatsApp saves them, which you pick once in Android's own folder picker, and only a recording that matches a
  message you received. The audio never leaves the phone. Stop (Settings › Messages and alerts › Voice messages) or
  Delete everything gives the access back.
- **Your chats with the AI and their answers**, what the app learned about how you write and about each person, the
  notes in About you, and the app's own usage log (tokens and estimated cost per question). What My Voice and About
  you hold goes along with what the AI writes for you while each is on, and what was noted about a person with what it
  writes about them, as described below; the texts they were learned from do not.
- **Your API keys**, wrapped with a key that lives in the Android Keystore and cannot be exported.
- **The Needs you widget** on the home screen shows a count, or names and ages if you turn that on in Settings ›
  Messages and alerts, never the messages; nothing leaves the phone because of it.
- **The Reminders widget** on the home screen shows how many reminders are still coming today and their times, or each
  reminder's words if you turn that on in Settings › Messages and alerts; nothing leaves the phone because of it.
- **Your side of chats in other apps**, only if you turn it on: the messages you send with the Message AI keyboard after
  its card's Keep them, in the messaging apps whose switch is on (Settings › Keyboard › Keep the messages you
  send), kept as your side of each chat in the app's private storage, never backed up (excluded from cloud backup and
  device-to-device transfer). Never a password, a search box or a private box. A message sent while the keyboard isn’t
  sure of the chat is kept apart, in no chat, waiting for its chat (your pick on the keyboard, its chat's alert opened
  while you are still in that box, the same words at the same minute in a later export or alert of that app, or Home's
  card); nothing reads it until it is in a chat, and it goes after 7 days if it never is. Kept until you remove them or
  Delete everything: a tap on a line's From your keyboard tag removes it, and Home's card removes a waiting one.
- **The keyboard's words and emoji.** The Message AI keyboard's word suggestions, the words it learns and your recent
  emoji stay on the phone: the suggestions come from an English word list inside the app, and what it learns (a word you
  kept as you typed it, or put back after it fixed your spelling) and the emoji you picked are kept in its own small file,
  never backed up and never from a private box, so nothing of them leaves the phone. The next word it offers after a
  space comes from your own messages already on the phone (your side of each chat, never theirs), counted on the phone
  into its own small files; nothing of them leaves it.

## What leaves the phone, and when

Nothing leaves until you ask the AI something, with two exceptions you set up yourself: with "Prepare reply ideas as
texts arrive" on (off unless you turn it on, under Settings › Messages and alerts), each new message goes to your AI
company as it arrives, with up to your last 20 texts with that person (in a WhatsApp chat, up to five messages before
it), so the alert can offer reply ideas, and whose birthday it is today or yesterday among you and the people in that
chat, worked out on the phone (never a date; see Names and ages); with "Full reply ideas" on as well, what the app has
noted about that person and your About you go along. And a scheduled message you save writes its drafts at their times
(Scheduled messages, below). Otherwise:

- **A question in Ask AI, Reply ideas, a draft, Catch me up.** The AI searches the on-device index and the messages it
  opens are sent to the AI company of that chat, including what others wrote to you. You see every lookup under the
  answer ("Sources · what left the phone"). Follow-up questions re-send the chat so far.
- **Your first name**, if you typed one (Settings › You and your voice), goes with questions, reply ideas and Catch me
  up, so the AI can refer to you.
- **Names and ages.** Each message the AI reads goes with its sender's name as your contacts have it, or the number
  when there is no contact. When a person's birthday is known (typed by you, or from your contacts), questions and reply
  ideas about them say roughly how old they are ("about 12", never the date), and reply ideas on the day say it is their
  birthday. Ask AI about one person (the app's, in a chat about their conversation, or the keyboard's, in a chat with
  them it is sure of) gets their birthday's month and day from their page instead of how old they are, never the year.
  In a chat the AI reads (reply ideas, an alert's too, Catch me up, Ask AI about a conversation, the
  keyboard's Ask AI in a chat it is sure of), the phone works out whose birthday it is today or yesterday among you and
  the people in it, so a "happy birthday" there is never taken as yours unless it is: in a group, only whose birthday it
  is today or yesterday, worked out on the phone, and the They are you set for the people in it; never a date. A tone
  change in a group (the app's, or the keyboard's Rewrite) gets only that They are, never a birthday. Your contact list
  itself is never sent.
- **Calls.** Catch me up sends the calls with that person in the stretch it covers; Reply ideas, a call after their last
  message; a question that reads a WhatsApp chat, the calls in it: when each was, how long it lasted, which way it
  went and whether it was missed. They come from your call history, if you allowed it, and from WhatsApp's call
  notifications. Never the number, never any audio, never the rest of your call history.
- **My Voice.** While Use My Voice is on, what the app learned about how you write (a short description and a few
  example lines of yours) goes along with reply ideas, drafts and tone changes; the texts it learned from do not.
- **About you.** While Use About you is on, its notes go with reply ideas, drafts, tone changes, Ask AI and Catch me up,
  and with the keyboard's Reply ideas, Rewrite and Ask AI (and with an alert's ideas when Full reply ideas is on); the AI is told never to put them in a web search. I am and My birthday, at
  the top of About you, go the same way: I am as "the user is a man" or "a woman" (Something else: your name or "they"),
  and My birthday only as "it's the user's birthday today" on the day, with your age if you gave one, never the date.
- **About them.** Who a person is to you, your note about them, their They are ("Dana is a woman: she/her", only when
  you set it, never guessed) and their related people, as you set them in People,
  go with questions, reply ideas, tone changes and Help me say it about them, and with the keyboard's Reply ideas,
  Rewrite and Ask AI in a chat with them it is sure of, and, while Use My Voice is on, how you text them. Who they are to you goes with a scheduled message's drafts to them too, and the AI is told to address
  them only as your own texts to them do. Their About (your notes and what the app learned from your texts with them) goes with reply ideas on
  screen and Help me say it, and with an alert's ideas only when Full reply ideas is on.
- **A report you email.** If you report an AI answer (press and hold it, Report this answer), the report stays on the
  phone under Settings › Privacy and data › Reports until you choose Email the developer or Email all reports. That
  opens your mail app, addressed to the address at the bottom of this page, with the report filled in: when, which
  chat and answer, the model and company, what was wrong and the note you typed. Never the messages the answer
  read. You see the text before anything is sent, and you send it from your mail app. In a beta build with Share
  diagnostics (beta) on, saving a report also sends it to Message AI's own private inbox, as Diagnostics (beta) below
  says (never which chat or answer); the report sheet says so before you save, and the report still stays on the
  phone to email.
- **A chat you export.** Export chat (a chat's ⋮, or chats you choose in Chats) shows you the text first: the chat's
  title, who it is about and the model, each question with its answer and its Sources lines, and, for a chat opened
  from a message, that message. Share then opens your phone's share sheet, and the text goes only to the app you pick,
  when you send or save it there. Never your keys, the app's instructions to the AI, the texts the AI read or what it
  cost. The app keeps no copy.
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
- **Scheduled messages.** Only for a rule you save yourself from a chat's card ("every time the Hawks play, write
  something fun for the Weekend crew group"), and only until you pause or delete it (Settings › Messages and alerts ›
  Scheduled messages). At each draft time the app asks your AI company (the model in Settings › AI) for a fresh draft:
  with it go your voice (while Use My Voice is on), that conversation's last 20 messages (in a WhatsApp chat, only what
  its notifications brought in), who the person is to you (for a draft to one person), the rule's words and the
  occasion (the event, who and when). Just before each draft, a
  rule saved with web search on looks its occasion up once: only the event's name and date (like "Hawks vs. the
  Kestrels October 17 2026") go to that company's web search, never your texts, and through OpenRouter the app reads up
  to two of the pages the search found, on the phone, and sends their text with the draft. A rule for a team's games
  also checks their schedule when you save it, then every Monday and on each game's morning: only the search words (like
  "Hawks schedule") go to that company's web search, never your texts. When that search runs through OpenRouter, the
  app reads up to three of the pages the search found, on the phone, and sends their text to that company with the
  search words. Tapping Save rule is your yes to that rule's own
  checks and lookups; none run while Settings › AI › Web search is Off, and then you type the dates yourself. Each draft,
  lookup and check is an AI call you pay for, shown on the card before you save and in AI spending under Scheduled messages.
  Nothing is sent without your tap: a draft waits as a notification with Send, Change and Skip, goes out the way a reply
  does (Message AI's check, or your messaging app opened with the text filled in), and is never sent after its event
  starts.
- **Help.** Your question, the guide page for the screen you are on, the guide pages that match your question (up to
  two), the guide's list of pages and the last four questions and answers of the help chat go to the model you picked
  for help answers; never your texts.
- **The Message AI keyboard.** What you type stays on the phone. Only when you tap Reply ideas, Rewrite or Ask AI does
  it go to your AI company: the box's text and About you; in a chat it's sure of, who that person is to you (in a group,
  only the They are you set for its people); and for Reply ideas and Ask AI the chat's captured messages and the lines
  you kept from this keyboard (in a text conversation, your last 20 texts with that person). In the apps you turn on, the messages you send are kept on this
  phone as your side of the chat; never a password, a search box or a private box. A message sent while the keyboard
  isn’t sure of the chat waits on the phone for its chat, read by nothing until it is in one, and goes after 7 days if it
  never is. Voice typing runs on the phone; the audio never leaves it. Reply ideas
  sends what is in the box with the chat its strip names, as the app's own Reply ideas sends it (in a WhatsApp chat
  its captured messages and the lines you kept from this keyboard; in a text conversation up to your last 20 texts
  with that person), and General ideas only
  what is in the box. Rewrite sends what is in the box and, in a chat the keyboard is sure of, who that person is to
  you, as Rewrite in the app does, once for each of your three reply tones; never the chat's messages. Ask AI sends the
  question you type in its own panel with that chat's captured messages and the lines you kept from this keyboard (in
  a text conversation, your last 20 texts with that person), with who that person is to you, their birthday's month
  and day from their page (never the year) and whose birthday it is today or yesterday, as Ask AI about a conversation
  does in the app, never the screen, and its answer stays in the panel until you tap Insert. Its panel's box can paste
  what you copied (its paste icon, or a press and hold): the keyboard reads the clipboard then, and only then, and what
  it pastes goes nowhere until you tap the arrow, as anything you type there. When the keyboard only guesses the chat,
  Rewrite sends nothing about a
  person, and Reply ideas and Ask AI first ask which chat. Your first name and About you go along with all three, as
  they do with reply ideas. While Use My Voice is on, Reply ideas and Rewrite write in how you text that person (in a
  chat the keyboard is sure of, once it was learned), else in your general voice; Ask AI gets only how you text that
  person, in a chat it is sure of, never your general voice. The first of these taps asks first, once for each AI
  company, naming the company and what goes, and asks once more when what it says changes (as when the lines you kept
  began to go too, when who the person is began to go, and when Ask AI began to send a person's birthday); turning the
  keyboard on is not that OK. In a
  password, PIN, card, number or phone box, a box that asks for no learning, or the keyboard's Private mode, nothing
  goes at all, and nothing is kept. The keyboard keeps nothing else you type (only the messages you send, after Keep
  them), never reads the screen, reads the clipboard only when you paste into its Ask AI box yourself (never a copy
  marked sensitive, such as a password), and needs no network to type. A line kept from the keyboard is your
  side of its chat: Reply ideas, Ask AI, Catch me up and My Voice read it with that chat's messages, and it goes to your
  AI company only with them, on your tap, as your texts do. A line that still needs a chat is read by none of them, nor
  by About you, Home's insights or any AI call, until it is in a chat; asking which chat (the keyboard's "Which chat?")
  sends nothing. Voice typing (the keyboard's mic) uses only your phone's own
  on-device speech recognizer, never an online one: the words you say go into the box as if you typed them, nothing is
  recorded or kept, and nothing goes anywhere; it needs no network, and where the phone has no on-device recognizer the
  mic is greyed. The words it typed go to your AI company only as typed text does, when you tap Reply ideas, Rewrite or
  Ask AI.
- **OpenRouter's record of a call**: the call's own id, to read what OpenRouter charged for it. Never any text.
- **Your key alone**: when the app lists a company's or your own endpoint's models, reads your OpenRouter key's
  limits, or reads OpenAI's costs with an admin key, only the key goes, never any text. Picking a model of your own
  endpoint sends it one short test question the app wrote, to see that it can look up texts; never your texts.
- **Diagnostics (beta).** Off unless you turn on "Share diagnostics (beta)" (Settings › Privacy and data, in beta
  builds; the setup checklist asks once). Then about once an hour a log of what the app did, each event timed and
  numbered in order, goes to Message AI's own private inbox, which deletes it after 90 days: when it opens and how fast,
  which screens you use and for how long, each AI call's company, model, time, tokens, cost and whether it worked, how
  the message index and background jobs went, each message alert it catches (which app, what kind, whether it found its
  conversation, how long it took and whether it worked; for an alert that had not found it, a random id made for that
  alert, so a later check can say it found it and how long after), each learn (what it learned, what started it, how
  long, roughly how many texts, its cost and whether it worked), rough counts ("100-999 texts", never exact), the app's
  version and build number, your phone's make, model and Android version, your time zone's offset, how the app was
  opened (launcher, alert, widget, share), and a random id made when you turn it on. If the app crashes: the names of
  the code that failed and where, never the error's words, which part of the app, whether it was on screen, how long it
  had been running and whether memory was low. And why Android last closed the app (a freeze, a crash, low memory, you
  or the system), whether it was on screen, how much memory it used, and for a freeze where the code was stuck. Report a
  problem, only while this is on, sends what you choose when you tap Send: the screen you were on, what went wrong, your
  note (up to 280 characters, shown to you first) and the last 50 events not sent yet, all marked with one random report
  id. A report of an AI answer you save while this is on (Report this answer) goes too: what was wrong, which kind of
  answer (a chat's, reply ideas or help), the company and model, how old the answer was and your few words (a long
  number goes as _), marked with the report's own random id; nothing else rides along with it, and never the question,
  the answer or the messages it read. Send feedback, only while this is on, sends what you write when you tap Send: your
  note (up to 280 characters, shown to you first), the screen you were on and the last 50 events not sent yet, marked
  with one random id, and a screenshot only if you pick one from your gallery, each time. A screenshot shows whatever
  was on your screen, names and messages included: the phone re-saves it without its location or camera details, only
  the developer can open it, and it is deleted after 30 days. Your note, the screen, the app's build, your phone's model
  and Android version and counts of those events (never their contents) also become an issue in the beta's private
  GitHub repository, where the developer answers and the other beta testers can read it; Report a problem and Report
  this answer are filed there too, without your note. Issues are deleted after 90 days, or as soon as you turn this off.
  The developer reads the inbox and those issues with the help of Claude (Anthropic), never a screenshot. Never your
  messages, AI questions or answers, names, numbers, email addresses, contacts, photos (except a screenshot you add to
  Send feedback), keys, an error's words, or anything you type except the note you write in Report a problem, in Send
  feedback or in a report of an AI answer. The inbox runs on Cloudflare. Besides what is listed here, it keeps its own
  short record of each upload in Cloudflare's logs for 3 days: when it came, how long it took, how many events, and the
  same fixed words and numbers listed here (never your note, and the random id only as a short code made from it). It
  never keeps your internet address or where you are. Turning it off stops sending and deletes the install id on this
  phone; what was already sent is deleted from the inbox, with any screenshots, and your notes come off the beta's
  GitHub page; those 3-day records simply expire. Anything still waiting on the phone is deleted too.

Each of those goes over an encrypted connection (HTTPS) directly from your phone to that company, except a plain http
address you set inside your home network. We never see it.
Diagnostics (beta) is the one exception: it comes to us, over HTTPS too, and holds none of it, except whatever a
screenshot you add to Send feedback shows.

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
- **Your own endpoint:** an address you set yourself, a model on your own computer or a cloud gateway that speaks
  OpenAI’s format. What you ask goes to that address and nowhere else; what that server does with it is between you and
  it. Plain http is allowed only for an address inside your home network, where anyone on that network could read what
  goes.

Their own policies apply once a message reaches them. Message AI has no agreement with any of them beyond the key you
hold.

## What the app never does

- Never sends a message without your confirm. A reply you choose goes out through your messaging app: through its own
  Reply on the notification once you tap Send, or opened there with the text filled in for you to send. A scheduled
  message's draft waits for your tap the same way, and is never sent after its event starts.
- Never sends your messages, contacts, photos or keys to us, or to anyone you did not pick by adding a key or an
  address.
- Never runs advertising or tracking, and no analytics company's code is in the app. Share diagnostics (beta) is
  Message AI's own log of what the app did, off unless you turn it on. There is no account and no sign-in.
- In the demo ("Try a demo first"), nothing leaves the phone at all: three sample people, prepared answers.
- The Message AI keyboard never logs what you type, never reads the screen, reads the clipboard only when you paste into
  its Ask AI box yourself, and never does a box's Send by itself: putting an idea or an answer in the box is not sending
  it. Its voice typing never records what you say and never sends the audio anywhere: the phone's own recognizer turns
  it into words on the phone.

## Permissions, and why each is asked

- **SMS and MMS:** to read your texts into the index. Required for the app to be useful with your own messages.
- **Contacts:** names and birthdays for the numbers you text and the contacts you add to People, and the people you link.
- **Notification access** (optional): to see WhatsApp messages as they arrive. Nothing is sent back through it unless
  you tap Send on a reply, and then the reply goes through WhatsApp's own notification reply.
- **Call log** (optional): to know when you talked instead of texting.
- **Notifications:** for the app's own reminders and alerts.
- **The Message AI keyboard** (optional): one permission of its own, the microphone, only for voice typing. It is
  asked at your first tap on the keyboard's mic: first the keyboard's own card ("Type with your voice?", with Turn on
  voice), then Android's own ask, once. The phone's own on-device speech recognizer turns your voice into words; the
  audio never leaves the phone. Only Android's own keyboard list turns the keyboard on (Settings ›
  Keyboard opens it), after Android's warning that a keyboard it didn't make may collect what you type. It starts only
  after the phone's first unlock.

## Your controls

- **Settings › Privacy and data:** What leaves the phone, Reports (answers you reported: email one or all, delete
  any time), Delete all chats, Delete everything (the index, every chat, every key, My Voice, About you, your people
  and their links, your tones, captured messages, your lines kept from the keyboard, the words the keyboard learned and
  its recent emoji, reminders, scheduled messages, the
  AI spending log, setup progress and every report are
  removed and the app returns to setup; your first name stays; Share diagnostics (beta) goes back to off), and in beta
  builds Share diagnostics (beta) (off unless you turn it on; what turning it off deletes is under Diagnostics (beta)
  above) and Report a problem and Send feedback (both also in the ? help sheet's ⋮; they send nothing until you tap Send,
  and nothing at all while Share diagnostics (beta) is off).
- **Settings › Messages and alerts › Scheduled messages:** pause or delete any scheduled message (Delete with Undo);
  a paused one writes no drafts and runs no checks.
- **Settings › AI:** remove any key at any time; chats on that company stop at once.
- **Settings › Keyboard:** turn the Message AI keyboard on; Keep the messages you send (its own
  card, Not now or Keep them) and, once on, a switch for each messaging app; its strip's ⋮ has Private mode, and
  Android's keyboard settings turn it off. A press and hold on a word the keyboard learned, in its row of words, forgets
  it (with Undo). A line From your keyboard goes with a tap on its tag (Remove, with Undo).
  Home's card lists the lines that need a chat: one tap files them in a chat, Remove (with Undo) takes one out, and Not
  now hides the card until the next one; they go by themselves after 7 days with no chat.
  Delete everything removes every kept line, those waiting for a chat too, and asks the keyboard's question about your AI company, its Keep card and
  its voice card again (the microphone itself is Android's to turn off: Settings › Apps › Message AI › Permissions).
- **Settings › Messages and alerts › Clear notification history** removes the captured messages and the imported ones
  (a WhatsApp export's, an iMessage history's). An iMessage chat's ⋮ has Remove all iMessage chats.
- **Uninstalling the app** removes everything it kept.

## Children

Message AI is not directed at children under 13 and does not knowingly collect anything from them.

## Changes and contact

Changes to this page are dated at the top. Questions: open an issue on the project's GitHub page, or write to
Ray Deliman, Raymond.deliman@gmail.com.
