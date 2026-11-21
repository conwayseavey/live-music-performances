# Setlist building and sheet workflow

Audited against Conway's Contraband planning conversation on November 21, 2026. Later instructions in that conversation take precedence over earlier drafts.

## Reusable preferences

- Build the show from Conway's definite selections. In the selection phase, YES means a main-set song. Other marked candidates belong in Extras until selected.
- Default the singer to Conway unless a song is assigned to Parker or another named singer.
- Spread Parker's songs across the whole show and within each set. Avoid consecutive Parker songs when the repertoire allows it. Balance by set length and musical fit.
- Separate songs by the same artist. Include featured artists when checking repetition. Spread repeated artists across sets, then space any remaining repeats within a set.
- Use recognizable, confident openers. Start with songs the band can deliver cleanly, build momentum, place slower songs mid-set, and finish each set with a strong payoff.
- Vary tempo, feel, era and vocal intensity while keeping transitions practical. Avoid stacking ballads or demanding vocal songs. Singer changes can give each vocalist a rest.
- Keep strong audience singalongs for the later portion of the night and the final closer. Consider the venue and room response when choosing how quickly to raise energy.
- Check performance keys, arrangement versions, tuning and instrument changes before proposing seamless transitions. Estimate duration from the actual arrangements when available. Song counts alone establish no guaranteed playing time.
- Retain a song once unless Conway explicitly requests a reprise. Match titles and artists carefully, including title variants and different recordings.
- Preserve existing musical notes and charts. Research missing information and mark uncertain summaries for rehearsal verification. Existing Nashville-number summaries from this conversation were researched cues and have not been verified against the Jamzone arrangements.

## Show layout and sorting

1. Read the live sheet and identify the current show column by its header.
2. Put a Set 1, Set 2 and subsequent set header above each set. Reuse the existing header rows where suitable.
3. Include one blank spacer row below each set.
4. Put the Extras header immediately after the final set's spacer, with all remaining show candidates beneath it.
5. Replace YES and singer-name values in the show column with one continuous series of numeric order values. Include set headers, songs, blank spacer rows, Extras and extra songs.
6. Sort complete rows by that numeric show column, ascending. Include all populated columns so song metadata, other show assignments and formatting travel together. Keep the first sheet-header row fixed.
7. Filter the show column to nonblank values so the numbered spacers and headers remain visible.
8. Keep singer designations visible through the established text colors. Parker's song details are blue. Preserve that blue when moving or sorting songs.
9. Keep song and spacer fills white across the setlist display columns. Give set and Extras headers a consistent gray fill. Preserve the established formatting of other columns.
10. Keep order-column cells free of singer notes. Conway explicitly asked to remove the notes added during planning.

## Beyer sheet data conventions

- Populate OG Key, My Key, Name, Artist, Chord Prog and Year for added songs, using verified recording-specific information where available.
- Add a row when the intended song or version does not exist. Inspect plausible title variants before creating a duplicate.
- Put Ultimate Guitar URLs in the dedicated Ultimate Guitar Tabs column beside Notes throughout the sheet. Keep surrounding playing instructions in Notes when splitting a mixed cell.
- Preserve the distinction between an original catalog key and a saved performance key. A missing Jamzone preset needs an explicit verification status.
- For an A–E export, read the current column headers and current show selection from the live sheet. Preserve the requested columns and current order. Regenerate exports after later setlist changes if a current export is requested.

## Safe editing and verification

- Use the native GitHub and Google Sheets connections. Conway explicitly requested closing the cloud browser and using native GitHub access.
- Re-read headers and target rows immediately before a write. Column letters and row numbers can change when the user inserts, moves or sorts data.
- Resolve songs by title plus artist/version. Never reuse historical row numbers as current song identities.
- Bound writes to the necessary cells and fields. For color edits, update color fields alone. For note removal, clear only the requested notes.
- Capture affected values and formatting before editing. Restore by song identity and column header if a repair is needed.
- After sorting, verify every order number against its song, the requested set sizes, unique-song counts, headers, spacers, Extras, singer colors and filter.
- Recheck that no adjacent songs share an artist, including collaborations, then inspect wider clusters and singer spacing.
- Review fill colors after sorting. Preserve blue singer text and verify the order column has no notes.
- Keep databases, authentication preferences, tokens and cached audio outside GitHub. Save documentation and reusable code through the authorized native connection.

An earlier edit used stale column and row positions after the user moved columns and sorted rows. It overwrote Chunk values with singer names. The affected cells were restored by song identity and verified. This is the reason for the live-header and identity checks above.

## Contraband at Strat, December 4, 2026

These settings describe this show. Confirm the format for future shows.

- Four main sets with 16, 12, 12 and 12 songs, totaling 52 songs.
- Eight Parker songs, two per set, with spacing within the sets.
- Parker assignments are I Never Lie, Some Beach, You Should Probably Leave, Keep Your Hands to Yourself, Pride and Joy, Tennessee Whiskey, Honky Tonk Women and Toes.
- Toes was promoted to Set 4 and Seven Spanish Angels was moved to Extras to maintain the requested set sizes. Some Beach was reassigned to Parker.
- The accidental duplicate I'm Still a Guy was removed.
- The final structure has 80 numbered entries comprising 52 main songs, four set headers, four spacer rows, one Extras header and 19 extra songs.
- Honky Tonk Women's G to G-flat change began as an extraction test. It remained in the working sheet and should be checked against the intended performance key.
- The live Beyer sheet is authoritative for later changes. Earlier CSV exports predate the final sequencing and singer changes.

See [Jamzone key extraction](jamzone-setlist-workflow.md) for the database recovery process.
