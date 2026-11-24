# Reformationsbibeln AAC audio

AAC-LC 64 kbps mono (M4A) verse audio for the KOINO Bible reader.

- `catalog-aac.json` lists every chapter. Converted chapters use `container: "m4a"`; chapters not converted yet still point at the original MP3 releases.
- `chapters/<bookId>/<chapter>-<revision>/` holds one M4A per verse and the chapter manifest.
- The source masters are the MP3 releases in [`akhansson88/reformationsbibeln-audio`](https://github.com/akhansson88/reformationsbibeln-audio).

Files are served directly from `raw.githubusercontent.com`; no build step is required.
