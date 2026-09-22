# Encrypted Projects - "Malbolge" Source Text Saved as .rb

One file, present twice. The content is a header comment claiming encrypted Malbolge and then a
single ~17,500-character run of printable ASCII chosen from the punctuation-heavy end of the range -
source text for an esoteric self-modifying language, not Ruby. The `.rb` extension and the folder
name are part of the joke; nothing here parses as Ruby.

**Suggested repo name:** `malbolge-esolang-rb`
**Stack:** none runnable here - esoteric-language source text (header claims Malbolge); no interpreter bundled
**Status:** archived
**Last modified:** 2019-12-04

## What it does

- `________.rb` and `________ (1).rb` - 17,532 bytes each, and byte-identical (same MD5). One is a
  duplicate download or a careless copy; the file name uses eight underscores so the two are
  indistinguishable in most listings.
- First line is `#HighlyEncypted"Malebolge-Ahura`; the rest is one unbroken statement of about 17,500
  characters.
- As with the Python-named sibling folder, the alphabet is wider than Malbolge's own (94 distinct
  printable characters), so the header's claim should be read as a label the author chose, not a
  guarantee a given interpreter accepts it.

## Layout

```
________.rb        17,532 bytes of esolang text
________ (1).rb    byte-identical copy
```

## Notes

- Delete one of the two files if this ever becomes a repo; a duplicate that differs only by
  ` (1)` in the name is confusing and adds nothing.
- The sibling `Py/Encrypted Projects` folder holds two more files in the same style with the same
  header abbreviations, so all three are one experiment stored twice.
- Nothing to strip before publishing: no credentials, no URLs, no hostnames - just text that will
  look like a corrupted file to anyone who has not read this.
