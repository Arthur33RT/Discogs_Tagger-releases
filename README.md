# Discogs_Tagger
Windows (WPF, .NET 8) desktop app for retrieving and tagging audio files with Discogs metadata.
It reads the `DISCOGS_RELEASE_ID` embedded by a prior MusicBrainz Picard pass, fetches the full
release from the Discogs API, and writes the **Discogs-owned** metadata into your mp3/FLAC files
without ever touching Picard/MusicBrainz-owned fields.
