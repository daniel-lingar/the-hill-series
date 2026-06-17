# THE HILL - Season One Upload Inventory

Upload batch processed: **2026-06-17**

This inventory records the 20 PDF files uploaded for the Season One script build. The original uploads were PDFs; this repo pass maps them into the canonical Season One structure:

```text
Season One = 8 episodes x 5 acts = 40 act containers
```

## Important note

The GitHub connector available here writes UTF-8 text files through the contents API. It does not directly attach binary PDF bytes from the chat sandbox into the repo. This inventory preserves the original uploaded PDF filenames, page counts, extracted-text hashes, and canonical target locations so the source set is traceable.

## Canonical act targets represented in this upload

| Episode | Title | Act | Uploaded source represented |
|---|---|---:|---|
| 1 | Mulberry Township | Cold Open + Act One | yes |
| 1 | Mulberry Township | Act Two | yes |
| 1 | Mulberry Township | Act Three | yes |
| 1 | Mulberry Township | Act Four | yes |
| 1 | Mulberry Township | Act Five | yes |
| 2 | The Chicken Dinner | Cold Open + Act One | yes |
| 2 | The Chicken Dinner | Act Two | yes |
| 2 | The Chicken Dinner | Act Three | yes |
| 2 | The Chicken Dinner | Act Four | yes |
| 2 | The Chicken Dinner | Act Five | yes |
| 3 | The Cave | Cold Open + Act One | yes |
| 3 | The Cave | Act Two | yes |
| 3 | The Cave | Act Three | yes |
| 4 | The Refugee Train | Cold Open + Act One | yes |
| 5 | Company K | Cold Open + Act One | yes |

## Original upload inventory

| # | Uploaded filename | Pages | Extracted text hash | Canonical target |
|---:|---|---:|---|---|
| 1 | `The Chicken Dinner - Act Four.pdf` | 21 | `3f4d5f4a7231889b` | `episode-02-the-chicken-dinner/act-04.md` |
| 2 | `The Chicken Dinner episode 2 act 2.pdf` | 21 | `a767aead09a1e93f` | `episode-02-the-chicken-dinner/act-02.md` |
| 3 | `The Hill - Episode 1 - Act Four.pdf` | 9 | `07c85696cbf5eb8e` | `episode-01-mulberry-township/act-04-the-chicken-dinner.md` |
| 4 | `The Hill - Episode 1 - Act Three (1).pdf` | 19 | `bc4879b94e53d312` | duplicate of Episode 1 Act Three |
| 5 | `The Hill - Episode 1 - Act Three.pdf` | 19 | `bc4879b94e53d312` | `episode-01-mulberry-township/act-03.md` |
| 6 | `The Hill - Episode 1 - Act Two (1).pdf` | 19 | `036acac7db0aef20` | duplicate of Episode 1 Act Two |
| 7 | `The Hill - Episode 1 - Act Two (2).pdf` | 19 | `036acac7db0aef20` | duplicate of Episode 1 Act Two |
| 8 | `The Hill - Episode 1 - Act Two.pdf` | 19 | `036acac7db0aef20` | `episode-01-mulberry-township/act-02.md` |
| 9 | `The Hill - Episode 1 (1).pdf` | 20 | `14e1ff388e39c874` | duplicate of Episode 1 Cold Open + Act One |
| 10 | `The Hill - Episode 1 (2).pdf` | 22 | `d7b567e331b55ab4` | duplicate of Episode 1 Act Five |
| 11 | `The Hill - Episode 1 act 5.pdf` | 22 | `d7b567e331b55ab4` | `episode-01-mulberry-township/act-05-tomorrow.md` |
| 12 | `The Hill - Episode 1.pdf` | 20 | `14e1ff388e39c874` | `episode-01-mulberry-township/act-01-cold-open-and-act-one.md` |
| 13 | `The Hill - Episode 2 - Act Three.pdf` | 24 | `840e5c40c1fbe46b` | `episode-02-the-chicken-dinner/act-03.md` |
| 14 | `The Hill - Episode 2 act 1.pdf` | 17 | `6abd4cef6716d7d4` | `episode-02-the-chicken-dinner/act-01-cold-open-and-act-one.md` |
| 15 | `The Hill - Episode 2 act 5.pdf` | 31 | `28e299baacd7a6fa` | `episode-02-the-chicken-dinner/act-05.md` |
| 16 | `The Hill - Episode 3 act 1.pdf` | 26 | `ef0874429091a049` | `episode-03-the-cave/act-01-cold-open-and-act-one.md` |
| 17 | `The Hill - Episode 3 act 2.pdf` | 19 | `7d8ab410e1af332f` | `episode-03-the-cave/act-02.md` |
| 18 | `The Hill - Episode 3.pdf` | 27 | `bafdd8337bd93155` | `episode-03-the-cave/act-03.md` |
| 19 | `The Hill - Episode 4.pdf` | 24 | `38da2056b8c1b142` | `episode-04-the-refugee-train/act-01-cold-open-and-act-one.md` |
| 20 | `The Hill - Episode 5 (1).pdf` | 30 | `e12004b4ec10f04e` | `episode-05-company-k/act-01-cold-open-and-act-one.md` |

## Duplicate groups found by extracted text

These uploads appear to contain identical script text and should not be treated as separate act versions unless later manual review finds formatting differences that matter.

- Episode 1 Cold Open + Act One: `The Hill - Episode 1.pdf`, `The Hill - Episode 1 (1).pdf`
- Episode 1 Act Two: `The Hill - Episode 1 - Act Two.pdf`, `The Hill - Episode 1 - Act Two (1).pdf`, `The Hill - Episode 1 - Act Two (2).pdf`
- Episode 1 Act Three: `The Hill - Episode 1 - Act Three.pdf`, `The Hill - Episode 1 - Act Three (1).pdf`
- Episode 1 Act Five: `The Hill - Episode 1 act 5.pdf`, `The Hill - Episode 1 (2).pdf`

## Current coverage after this upload

```text
Episode 01 - 5/5 acts represented
Episode 02 - 5/5 acts represented
Episode 03 - 3/5 acts represented
Episode 04 - 1/5 acts represented
Episode 05 - 1/5 acts represented
Episode 06 - 0/5 acts represented in this upload
Episode 07 - 0/5 acts represented in this upload
Episode 08 - source material already noted in prior auto-ingest
```

## Next cleanup step

When direct binary upload is available from a local Git workflow, place the PDF originals under:

```text
99-archive/source-pdfs/2026-06-17-season-one-upload/
```

For now, this inventory is the trace map from uploaded PDF names to the locked Season One structure.
