# Codebook for annotation

This markdown explains the content of each column of the file `data/voice_all_guides_for_annotation.csv`:

- `unique_id` : a unique identifier for each entry; this was generated based on row names prior to randomization
- `fieldguide` : the identifier of the field guide
- `english_common` : the English common name of the bird as listed in the field guide
- `voice` : the voice section as we digitized it using typing or using the All About Birds database
- `voice_bounded` : prior to annotation this is just a copy of the `voice` section; it is meant to be filled with semicolons to separate different sound objects
- `typo` : whether a genuine typo has been fixed, e.g., "whisle" -> "whistle"
- `fixes` : whether anything else has been fixed, e.g., bracketing, trailing spaces etc.
- `warblish` : three levels: 1) NO (no obvious warblish), 2) YES (an existing warblish that was already flagged with ** during digitization), 3) NEW (a warblish that we missed); please see `annotation_manual.pdf` for more discussion of what we count as warblish in this step of the process
- `comment` : free text: any comments for anything strange, questions, cases the annotator wants to discuss or revisit, or cases that are noteworthy in some other fashion

