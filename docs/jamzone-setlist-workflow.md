# Live music performances

## Export a Jamzone setlist with performance keys

1. Export the setlist CSV from the Jamzone web library. Keep the original order, versions, artists, years and catalog keys.
2. Close the song player and quit Jamzone on the Mac where the performance settings are current. Copy the file at ~/Library/Containers/com.recisio.jamzone.ios/Data/Library/Application Support/default.realm to a working directory.
3. Open the copy with a compatible Realm reader. Export Song and JamPreset as JSON arrays. In Song, identify the title and artist fields by checking known titles. Join the two tables on their numeric id fields. The pitch field in JamPreset is a signed semitone offset. Internal binary offsets vary between saves.
4. Match CSV entries to Song by title and artist, keeping version distinctions. For each matched id, transpose the catalog tonic by pitch modulo 12 and retain its major/minor quality. Keep a saved zero distinct from a missing preset. For a missing preset, carry forward the catalog key and leave the offset blank. Flag ambiguous or unmatched songs.
5. Verify a known changed song against the player. The December 2026 snapshot had Honky Tonk Women in G with pitch −1, yielding G♭. Confirm intentional test edits before the show.
6. Save the CSV with Key, Original Key and Transpose (semitones). For the Beyer Master Setlist, match title and recording, retain existing Nashville charts, mark each unique song once, and filter the show column to X. Remove accidental duplicates from the show CSV and use singer names for show assignments.

Keep Realm databases, preferences, authentication tokens and cached audio outside this repository.
