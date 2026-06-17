# THE HILL — Season One Structure

## Canonical Season Rule

**Season One has 8 episodes.**

**Each episode has 5 acts.**

This is the locked working architecture for Season One.

---

## Season One Episode Grid

| Episode | Working Title | Act Count | Current source coverage |
|---|---|---:|---|
| Episode 1 | Mulberry Township | 5 acts | 5/5 acts represented in 2026-06-17 upload |
| Episode 2 | The Chicken Dinner | 5 acts | 5/5 acts represented in 2026-06-17 upload |
| Episode 3 | The Cave | 5 acts | 3/5 acts represented in 2026-06-17 upload; prior Act Four material also exists in auto-ingest |
| Episode 4 | The Refugee Train | 5 acts | Cold Open + Act One represented in 2026-06-17 upload |
| Episode 5 | Company K | 5 acts | Cold Open + Act One represented in 2026-06-17 upload |
| Episode 6 | TBD | 5 acts | Open script slot |
| Episode 7 | TBD | 5 acts | Open script slot |
| Episode 8 | TBD | 5 acts | Existing PDF material present in prior auto-ingest |

---

## Episode Act Template

Every Season One episode should follow this container unless deliberately changed later:

```text
Episode XX — Working Title
├── Act One
├── Act Two
├── Act Three
├── Act Four
└── Act Five
```

## Permanent folder plan

```text
01-season-one/
├── SEASON_ONE_STRUCTURE.md
├── 00_UPLOAD_INVENTORY_2026-06-17.md
├── episode-01-mulberry-township/
│   ├── act-01-cold-open-and-act-one.md
│   ├── act-02.md
│   ├── act-03.md
│   ├── act-04-the-chicken-dinner.md
│   └── act-05-tomorrow.md
├── episode-02-the-chicken-dinner/
│   ├── act-01-cold-open-and-act-one.md
│   ├── act-02.md
│   ├── act-03.md
│   ├── act-04.md
│   └── act-05.md
├── episode-03-the-cave/
│   ├── act-01-cold-open-and-act-one.md
│   ├── act-02.md
│   ├── act-03.md
│   ├── act-04.md
│   └── act-05.md
├── episode-04-the-refugee-train/
├── episode-05-company-k/
├── episode-06/
├── episode-07/
└── episode-08/
```

## 2026-06-17 upload map

A batch of 20 uploaded PDFs was mapped into the Season One structure. The trace inventory is here:

```text
01-season-one/00_UPLOAD_INVENTORY_2026-06-17.md
```

Coverage from that upload:

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

## Existing material to map into the structure

Current auto-ingest files already in GitHub:

```text
00_INBOX/auto-ingest/the-hill/2026-06-15/
```

Known matches:

- `Season One - Episode Guide_1.pdf` → Season guide / episode grid source
- `The Hill - Episode 8 (4)_1.pdf` → Episode 8 source material
- `The_Hill_Ep3_Act4_Canonical_Merge_1.md` → Episode 3 / Act Four source material
- `The Hill Series Overview_1.pdf` → series overview / pitch source
- `THE_HILL_SEASON_ONE_COMPLETE_SCRIPT_SYSTEM (1)_1.zip` → archive package for full season script system

## Rule going forward

Do not treat Season One as open-ended.

Season One is now:

```text
8 episodes × 5 acts = 40 act containers
```

Everything should be sorted into those 40 containers or into supporting folders such as pitch, research, characters, setting, and archive packages.
