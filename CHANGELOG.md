# Changelog

## v1.0.0

First release of Castmorphic Subtitles. The app was previously published
under a different name; this is where its version history starts.

- Paste a YouTube URL, pick a subtitle language and a format, get the
  file. The video itself is never downloaded -- `skip_download` is
  hardcoded on.
- Formats: SRT, VTT, TXT (plain transcript, timestamps stripped), and
  Raw.
- Ships as a single AppImage that draws its own window. Qt's WebEngine
  is bundled, so nothing has to be installed on first run. The only
  host requirement is `python3` 3.10 or newer, which every current
  Linux desktop ships; if it is missing or too old, the app says so in
  a dialog rather than failing quietly.
- Checks GitHub for its own updates, and can download and swap in a new
  AppImage from inside the app.
- Carries Castmorphic's name, colours and mark. The app is free and
  standalone, and needs no Castmorphic account.
