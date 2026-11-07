<!-- Copied from the Disuse repo, store/PRIVACY.md. That file is the source:
     change it there, then copy it here again. -->

# Privacy policy — Disuse

**Last updated: 7 November 2026**

**Applies to: Disuse for Android, version 0.14.1 and later**

## The short version

Disuse has no account, no server of its own, no analytics and no ads.
Everything you put into it stays on your phone, with one exception: when you
tap **Scan**, the photo of your page is sent to Google's Gemini, with your own
Gemini API key, so it can read it. Google may keep those photos and use them to improve its AI, and people at
Google may review them. So scan notes, not anything private.

Disuse is for adults (18 and over).

## What Disuse stores on your phone

Everything below lives in the app's own private storage on your device.

- **Subjects** you chose or created: names, tags, descriptions.
- **Questions and answers** you write, scan or paste, and any pictures you add
  to an answer. Answers are kept sealed (encrypted) with a key held on the
  device; this is how the app keeps an answer hidden until you have tried,
  not a security promise about the phone itself.
- **Drafts** of questions you have not finished, and an answer you were
  typing, kept for up to an hour so it survives the app being closed.
- **Chunks**: the groupings you make, their names and members.
- **Review history**: when you answered, what you wrote, how it felt
  (Forgot / Hard / Easy), and the schedule worked out from that.
- **Explain Mode runs**: how long you spoke and the moments you marked as
  stuck, with any note you typed about them. The recording itself is deleted
  when you leave the screen (see below).
- **Settings**: whether the reminder is on, onboarding progress, which
  explanations you have seen, Scan's answer styles.
- **Your Gemini API key**, if you add one for Scan. It is sent only to
  Google, with each scan, and never goes into a backup file.
- **A local crash log**: if the app crashes, the error type and where it
  happened in the code. It contains none of your questions, answers,
  recordings or subject names.

## Recordings and dictation

**Explain Mode** records your voice and **Dictate** turns speech into text.
Both use a speech model built into the app, on the phone. The audio is never
sent anywhere. Explain Mode recordings are kept only while their screen is
open, so you can play them back, and are deleted when it closes; anything
left over is removed the next time the app starts.

## What leaves the phone

### 1. Pages you scan, sent to Google

Scan reads a page of notes and suggests questions from it. **Scan it**, in an
answer field, copies your handwriting into text. Both only happen when you tap
them, and both work the same way:

- The photo (up to three pages at a time) is sent straight from your phone to
  Google's **Gemini API**, with the API key you created in Google AI Studio
  and pasted into Disuse. The request is yours, made under your key and your
  agreement with Google; it does not pass through any server of Disuse's, and
  the developer never sees it. Your questions, answers and review history are
  not sent with it, only the photo, a fixed instruction and your key.
- Google's free Gemini service may **keep the photos and the text it returns,
  use them to improve Google's products and AI models, and have people review
  them**, separated from any account. Do not scan anything personal or
  confidential. See the [Gemini API terms](https://ai.google.dev/gemini-api/terms)
  and [Google's privacy policy](https://policies.google.com/privacy).
- If your key belongs to a Google Cloud project with billing turned on,
  Google's paid terms apply to it instead, and Google does not use paid
  requests to improve its products. Which applies is between you and Google.
- The **document scanner** that takes the photo is Google's ML Kit, part of
  Google Play services. ML Kit sends Google diagnostic and usage information
  (device and app information, performance figures), not the photos
  themselves.

If you never use Scan, none of this happens, and Disuse never asks for a key.

### 2. Files you choose to save

**Backup** writes a file containing everything listed above, and **Keep a copy
automatically** writes one each week to a folder you pick. Where it goes from
there is your choice; Disuse does not upload it. The file includes the key
that unseals your answers, so you can lock it with a passphrase. Treat an
unlocked backup as sensitive. **Questions as text** saves your questions and
answers as a plain file you can share.

### 3. Feedback and crash reports you send

These open your own email app with a message already written. Nothing is
sent unless you tap send there. The message contains the app version, the
device model and Android version, and for a crash, the error and where in the
code it happened. Never your questions, answers, recordings or subjects.

**Report a suggestion**, under Scan's results, works the same way, and its
message also carries the suggestion you are reporting (the topic, the
question and the answer as Scan wrote them), because that is what the report
is about. Not the photo, and nothing else from your library. You see it in
your email app before anything is sent, and can cut it there.

There is nothing else: no tracking, no advertising ID, no analytics, no
crash-reporting service.

## Permissions

- **Microphone**: Explain Mode and Dictate. Audio stays on the phone.
- **Notifications**: one reminder, scheduled on the phone, when questions are
  due. There is no push service. You can turn it off.
- **Run at startup**: puts the reminder back after the phone restarts.
- **Internet**: for Scan only.
- **Vibration**: small taps of feedback, and the reminder.

The camera is used by Google's document scanner, which asks for it itself.
Disuse does not ask for location, contacts, storage-wide access or any
identifier.

## Children

Disuse is for adults. It is not directed at children, and Google's Gemini
API, which Scan uses with your own key, may only be used by people 18 and
over.

## Where it is available

Disuse is offered everywhere Google Play is. Everything except Scan works the
same in every country, with no key and no connection.

In the European Economic Area, the United Kingdom and Switzerland, Google's
terms allow only its paid Gemini service, so Scan there needs a key from a
Google Cloud project with billing turned on. Paid requests are not used to
improve Google's products (see "Pages you scan" above).

## Deleting your data

Uninstalling Disuse deletes everything it stored on the phone. There is no
server copy and no account to close. Backup files you saved are yours to
delete. Photos already sent through Scan are held by Google under its own
terms; Disuse keeps no copy and cannot reach them. You can delete your
Gemini API key in Google AI Studio at any time, and remove it from Disuse in
Settings.

## Changes

If Disuse ever sends anything new, this policy will say so before that
version ships.

## Contact

rahul0x.work@outlook.com
