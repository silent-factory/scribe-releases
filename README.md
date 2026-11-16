# Scribe

Turns recordings into transcripts that show who said what. Everything runs on your Mac; recordings are never uploaded.

## Install

1. Download `Scribe_0.1.0_aarch64.dmg` from the [latest release](https://github.com/silent-factory/scribe-releases/releases/latest).
2. Open it and drag Scribe into Applications.
3. Open Scribe and click **Download and set up**. This happens once, takes a few minutes, and needs an internet
   connection and about 4.5 GB of free disk space.

## Use

Drop recordings on the window, or click it to choose files. Each transcript is saved next to its recording as
`<name> - transcript.txt`. Leave the language on "Detect automatically" unless it guesses wrong.

## Requirements

A Mac with Apple silicon (M1 or later) running macOS 13.3 or later.

## Credits

Speaker detection uses the pyannote `speaker-diarization-community-1` model (CC BY 4.0). Speech recognition uses
OpenAI's Whisper large-v3-turbo (MIT). Full notices are included in the app.
