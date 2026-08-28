# Privacy Policy

**Last updated: August 28, 2026**

Drikus Demo Deck is built to hold your unfinished songs, not your data. This
policy is short because the app doesn't do much with either.

## The short version

- No accounts, no sign-in, no user IDs.
- No analytics, no crash reporting, no advertising, no third-party SDKs of
  any kind.
- Nothing is uploaded to a server we run. There is no server.
- Your recordings, sessions, and notes live only in the app's storage on
  your device (and in your iCloud/device backups, if you have those turned
  on at the iOS level — that's Apple's backup system, not something this
  app controls).

## What the app touches, and why

**Microphone.** Used only when you tap record, to capture audio onto a
track. Recordings are written straight to the app's storage on your device.

**Speech recognition (iOS 26+, on-device only).** If you ask the app to
transcribe a take — so you can later search for a song by a word you
remember — that transcription runs entirely on your phone's Neural Engine.
No audio or text is sent anywhere for this. If your device or iOS version
doesn't support on-device transcription, the app simply hides the feature
rather than falling back to a cloud service.

**Location (used once per app launch, only if you allow it).** The app asks
for your approximate location a single time per launch, purely so it can
suggest a street name (e.g. "Stockton St") for a new session's title —
finding a demo later is easier with a real name than a timestamp. Turning
this into a street name uses Apple's own reverse-geocoding service, which
means your coordinates are sent to Apple, not to us, for that one lookup.
The app keeps only the resulting street name, never the raw coordinates,
and never sends location data anywhere else. You can decline the location
permission entirely; the app falls back to a plain name instead.

**Files you import or export.** Importing audio (from Files, or a shared
Voice Memo) and exporting/sharing a mix both go through the standard iOS
Files and Share Sheet UI. Where that file goes — Messages, Mail, AirDrop,
saved to Files — is entirely your choice each time; the app doesn't send it
anywhere on its own.

## Data retention and deletion

Everything the app creates lives in its own storage on your device. Delete
a session in the app, or delete the app itself, and that data is gone.
There's no separate copy anywhere for us to retain or delete on your
behalf, because we never had one.

## Changes to this policy

If what the app collects or does ever changes, this page will change with
it, and the "Last updated" date above will move. Given the app's whole
premise is staying off the network, we don't expect that to happen often.

## Questions

Open an issue in this repository: [drikus-demo-deck-public/issues](https://github.com/drikusroor/drikus-demo-deck-public/issues)
