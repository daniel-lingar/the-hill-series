# THE HILL — Season One Structure

## Canonical Season Rule

**Season One has 8 episodes.**

**Each episode has 5 acts.**

This is the locked working architecture for Season One.

---

## Season One Episode Grid

| Episode | Working Slot | Act Count | Status |
|---|---:|---:|---|
| Episode 1 | `episode-01` | 5 acts | Pilot / foundation |
| Episode 2 | `episode-02` | 5 acts | Outline/script slot |
| Episode 3 | `episode-03` | 5 acts | Existing Act Four material recovered |
| Episode 4 | `episode-04` | 5 acts | Outline/script slot |
| Episode 5 | `episode-05` | 5 acts | Outline/script slot |
| Episode 6 | `episode-06` | 5 acts | Outline/script slot |
| Episode 7 | `episode-07` | 5 acts | Outline/script slot |
| Episode 8 | `episode-08` | 5 acts | Existing PDF material present in auto-ingest |

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
├── episode-01/
│   ├── act-01.md
│   ├── act-02.md
│   ├── act-03.md
│   ├── act-04.md
│   └── act-05.md
├── episode-02/
│   ├── act-01.md
│   ├── act-02.md
│   ├── act-03.md
│   ├── act-04.md
│   └── act-05.md
├── episode-03/
│   ├── act-01.md
│   ├── act-02.md
│   ├── act-03.md
│   ├── act-04.md
│   └── act-05.md
├── episode-04/
├── episode-05/
├── episode-06/
├── episode-07/
└── episode-08/
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
