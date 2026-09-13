# Sotto Notes — Privacy

Sotto Notes stores your recordings, transcripts, summaries, and chat in **your own
private iCloud database** (Apple CloudKit) and on your devices. Titles, summaries, speaker
names, tags, and chat are stored as encrypted fields; transcript and audio files are stored
as iCloud assets, encrypted at rest by Apple.

The developer runs no server and receives nothing: no accounts, no analytics, no crash
reports, no identifiers. Transcription and summaries are produced on a Mac you control,
using software you install there.

The microphone is used only while you record. On-device speech recognition (iOS 26 and
later) is used only to produce a draft transcript on your device.

Deleting a meeting in the app deletes it from your iCloud database and from all your
devices. Removing the app from all devices and deleting its iCloud data in Settings ›
Apple Account › iCloud removes everything.

Questions: open an issue at https://github.com/pouladi-ca/sotto.
