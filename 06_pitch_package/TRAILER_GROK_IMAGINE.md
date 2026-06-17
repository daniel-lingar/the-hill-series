# THE HILL — Grok Imagine Shot List (14 × 10s)

Use this file in Grok Imagine: **generate frame 1** → **animate 10s** → **add dialogue in edit** (Imagine does not lip-sync).

| Setting | Value |
|---------|-------|
| `aspect_ratio` | `9:16` (vertical social) — use the same on every shot |
| `duration` | `10` |
| Workflow | `image_gen` → `image_to_video` → VO/SFX in post |

**Style lock** — weave into every `image_gen` prompt (do not paste as tags only):

> Cinematic Southern gothic, 1864 Arkansas Ozarks, muted earth tones, natural light, film grain, photoreal, dread not spectacle, no modern objects.

---

## Step 0 — Base images (generate once, then `image_edit`)

| Ref | Generate in | Reuse in |
|-----|-------------|----------|
| **HORNER** — Dr. John Turner Horner, 34, physician, sharp tired face, period shirt | Clip 09 | Clips 10–12 via `image_edit` |
| **OLD MAN** — elderly Arkansas man, porch rocker, cracked memory face | Clip 13 | Clip 03 (1942 half), Clip 10 VO cover |
| **FIELD** — wide potato patch, homestead, ridge timber | Clip 04 | Clip 14 via `image_edit` (add phone, modern shirt) |

---

## CLIP 01 — THE LAST MEAL

### image_gen
`aspect_ratio: 9:16`

A wide static shot inside a Horner farmhouse dining room at night. A whole roasted chicken sits untouched on an iron platter at the center of a pine table, lit by a low kerosene lamp. Family members sit in chair backs around the table, their faces in partial shadow. Through the back window, a dark ridge silhouette cuts the night sky. Cinematic Southern gothic, 1864 Arkansas Ozarks, muted earth tones, natural light, film grain, photoreal, dread not spectacle, no modern objects.

### image_to_video
`duration: 10`

The camera makes a slow push-in toward the chicken on the table. The lamp flame flickers once. No one moves.

### audio (post)

| Time | Speaker | Line |
|------|---------|------|
| 0:01.5–0:06.5 | NARRATOR (VO) | Johnson County. Eighteen sixty-four. Before the violence… there was dinner. |

**sfx:** skillet hiss at 0:00

---

## CLIP 02 — THE WARNING

### image_gen
`aspect_ratio: 9:16`

From inside a dark farmhouse doorway, we look out into harsh August daylight. A woman in an apron stands in the foreground with her back to camera, wringing her hands. The yard beyond the door frame is overexposed and empty. Cinematic Southern gothic, 1864 Arkansas Ozarks, muted earth tones, natural light, film grain, photoreal, dread not spectacle.

### image_to_video
`duration: 10`

The woman takes one slow step toward the light. The camera holds on the doorway frame.

### audio (post)

| Time | Speaker | Line |
|------|---------|------|
| 0:01.5–0:05.0 | LOUIS (1864, on-screen) | Whatever you do… don't go up to the house in the daytime. |
| 0:05.0–0:08.0 | NARRATOR (VO) | But the mother was killing a chicken. The food was in the kitchen. |

**optional second shot** (if you cut to timber line for LOUIS): young man with horse pointing at house, two older men listening — same style lock, `image_gen` then cut in edit.

---

## CLIP 03 — HERE THEY COME

### image_gen (1864)
`aspect_ratio: 9:16`

A barefoot seven-year-old boy runs toward camera from a low porch angle, one arm pointing up a dirt road. A dust plume rises in the background under August heat. Fear is clear on his face. Cinematic Southern gothic, 1864 Arkansas Ozarks, photoreal film grain, dread not spectacle.

### image_to_video (1864)
`duration: 10`

The boy runs three steps toward camera and stops, still pointing. Dust drifts in the road behind him.

### image_gen (1942 — optional cut, or use OLD MAN ref + image_edit)
`aspect_ratio: 9:16`

A summer night on a weathered Arkansas porch. An elderly man sits in a rocking chair while a young girl rests on the wooden step. Fireflies drift in the dark trees beyond the porch light. Cinematic Southern gothic, 1942, photoreal.

### image_to_video (1942)
`duration: 10`

The camera makes a slow push-in on the old man's face. He stares past camera into the trees. The girl stays still on the step.

### audio (post)

| Time | Speaker | Line |
|------|---------|------|
| 0:01.5–0:03.5 | CHILD (1864, on-screen) | Here they come, Grandpap— |
| 0:03.5–0:08.5 | OLD MAN (1942, on-screen) | Wasn't long till about twenty rebels came riding up. |

---

## CLIP 04 — I SURRENDER

### image_gen
`aspect_ratio: 9:16`

A gray-bearded farmer in suspenders stands center frame in a potato field, hands raised with open palms at shoulder height. Potato plants reach his chest. Twenty distant horse silhouettes wait at the tree line through August haze. Cinematic Southern gothic, 1864 Arkansas Ozarks, photoreal wide shot, dread not spectacle.

### image_to_video
`duration: 10`

The farmer holds his surrender pose, then collapses forward out of frame. The camera stays static.

### audio (post)

| Time | Speaker | Line |
|------|---------|------|
| 0:01.5–0:04.5 | SPENCER (1864, on-screen) | I surrender! |
| 0:05.5–0:09.0 | NARRATOR (VO) | They shot him down in the potato patch. |

**sfx:** one dry gunshot at 0:04.5

---

## CLIP 05 — THE RIDGE

### image_gen
`aspect_ratio: 9:16`

At dusk in a potato field, two women drag an injured man between the rows. He bleeds at the head; they hold him under the arms. The farmhouse recedes behind them as they move toward dark ridge timber. Cinematic Southern gothic, 1864 Arkansas Ozarks, photoreal, dread not spectacle.

### image_to_video
`duration: 10`

The camera tracks slowly sideways, following the women as they pull the man toward the tree line.

### audio (post)

| Time | Speaker | Line |
|------|---------|------|
| 0:01.5–0:04.0 | NARRATOR (VO) | They beat his son in the field and left him for dead. |
| 0:04.0–0:08.5 | NARRATOR (VO) | The women carried him toward the ridge — not the house. |

---

## CLIP 06 — THE CAVE

### image_gen
`aspect_ratio: 9:16`

Inside a cave overhang at night, an injured man lies on a quilt, his face swollen, eyes open. A woman kneels beside him with a wet cloth. A child sleeps against the rock wall. Water drips on stone; dim blue moonlight touches the cave mouth. Cinematic Southern gothic, 1864 Arkansas Ozarks, photoreal intimate shot, dread not spectacle.

### image_to_video
`duration: 10`

The woman wrings the cloth once. The man's fingers twitch. The camera pushes slowly toward their hands.

### audio (post)

| Time | Speaker | Line |
|------|---------|------|
| 0:01.5–0:05.5 | NARRATOR (VO) | He lived eight days in a hole in the hill. |
| 0:05.5–0:08.5 | MARY ANN (1864, whisper) | We already are. |
| 0:08.5–0:10.0 | NARRATOR (VO) | While the county stayed quiet. |

---

## CLIP 07 — PARTIES KNOWN

> **Note:** Do not ask Imagine to render exact tombstone text — it will garble. Show carving in progress; add final inscription in post.

### image_gen
`aspect_ratio: 9:16`

A close-up of gloved hands chiseling a fresh limestone tombstone in a daytime Arkansas cemetery. Granite dust falls from the stone. Only partial letters are visible — illegible fragments, not full sentences. Cinematic Southern gothic, 1864, photoreal macro, dread not spectacle.

### image_to_video
`duration: 10`

The chisel strikes twice. The camera pulls back slowly to reveal more of the stone, still without readable full text.

### audio (post)

| Time | Speaker | Line |
|------|---------|------|
| 0:01.5–0:05.5 | CARVER (O.S.) | …killed August the tenth… |
| 0:05.5–0:08.0 | NARRATOR (VO) | By parties known to his family. Carved in stone. |
| 0:08.0–0:10.0 | NARRATOR (VO) | Not in court. |

**edit:** overlay correct inscription text on stone at 0:06+

---

## CLIP 08 — THE SILENCE

### image_gen
`aspect_ratio: 9:16`

An empty sheriff's office in daytime. A top-down view shows an open ledger with a blank page and a dry feather pen. At eye level, the room is vacant. A framed oil portrait of a Confederate colonel wearing a sheriff badge hangs on the wall. Dust floats in window light. Cinematic Southern gothic, 1864 Arkansas Ozarks, photoreal, dread not spectacle.

### image_to_video
`duration: 10`

The camera pans slowly up from the ledger to the portrait. An empty street shows through the door glass. No one enters.

### audio (post)

| Time | Speaker | Line |
|------|---------|------|
| 0:01.5–0:05.0 | NARRATOR (VO) | The sheriff held the county. The war held the hills. |
| 0:05.0–0:08.5 | NARRATOR (VO) | The law never came. |

---

## CLIP 09 — TWENTY NAMES

### image_gen
`aspect_ratio: 9:16`

Inside a barn at night, a candle sits on a crate beside an unfurled Union muster roll. A doctor, about 34, leans over the paper while a burly man stands opposite with arms crossed. One finger rests on the names. Their faces catch the candlelight. Cinematic Southern gothic, 1864 Arkansas Ozarks, photoreal medium shot, dread not spectacle.

### image_to_video
`duration: 10`

The doctor's finger moves slowly across three names on the paper. The candle flickers. The camera holds static.

### audio (post)

| Time | Speaker | Line |
|------|---------|------|
| 0:01.5–0:06.5 | HORNER (1864, on-screen) | Twenty men in my father's field. Twenty names on paper. |
| 0:06.5–0:09.0 | HORNER (1864, on-screen) | Not enough… not yet. |

---

## CLIP 10 — THE SQUAD

### image_gen
`aspect_ratio: 9:16` · use **HORNER** ref + `image_edit` if available

Four saddled horses wait in a barn at pre-dawn. A small wiry man holds the reins. The doctor checks a pistol. A burly man mounts. A thin hard-eyed man watches the dark tree line behind them. Cinematic Southern gothic, 1864 Arkansas Ozarks, photoreal, dread not spectacle.

### image_to_video
`duration: 10`

The horses walk slowly into black timber. One horse exhales visible breath. The camera follows from behind.

### audio (post)

| Time | Speaker | Line |
|------|---------|------|
| 0:01.5–0:05.5 | OLD MAN (1942, VO) | Dad had a squad of men… Wash Middleton and Fate Arnold… desperate men. |
| 0:05.5–0:08.5 | HORNER (1864, on-screen) | Then we learn the rest. |

---

## CLIP 11 — LEADER ESCAPES

### image_gen
`aspect_ratio: 9:16` · use **HORNER** ref + `image_edit`

Late day in a cornfield. Stubble rows cut through smoke haze. A doctor raises a pistol, his hand trembling. A rider silhouette waits on the ridge line forty yards away. Two men stand between the corn rows. Cinematic Southern gothic, 1864 Arkansas Ozarks, photoreal tension, dread not spectacle.

### image_to_video
`duration: 10`

The pistol fires wide. The doctor throws the pistol down. The rider spurs into timber and vanishes. The camera stays static.

### audio (post)

| Time | Speaker | Line |
|------|---------|------|
| 0:01.5–0:04.5 | NARRATOR (VO) | He picked out the leader… |
| 0:06.0–0:09.0 | ARNOLD (1864, on-screen) | You let him go. |
| 0:06.0–0:09.0 | HORNER (1864, on-screen) | I didn't let him go. |

---

## CLIP 12 — THE COUNT

### image_gen
`aspect_ratio: 9:16` · use **HORNER** ref + `image_edit`

At the edge of a cornfield at dusk, four unbadged men stand in a line, blood on their shirt cuffs. The doctor stands center, looking down. A burly man waits beside him. Stubble field stretches behind them. Cinematic Southern gothic, 1864 Arkansas Ozarks, photoreal group portrait, dread not spectacle.

### image_to_video
`duration: 10`

The camera pushes slowly in on the doctor's face. Wind moves the corn slightly. The men do not smile.

### audio (post)

| Time | Speaker | Line |
|------|---------|------|
| 0:01.5–0:05.5 | HORNER (1864, on-screen) | Twenty in the field. One in the rows. |
| 0:05.5–0:07.5 | HORNER (1864, on-screen) | Nineteen left. |
| 0:07.5–0:09.5 | MIDDLETON (1864, on-screen) | Then we're not done. |
| 0:07.5–0:09.5 | HORNER (1864, on-screen) | We're started. |

---

## CLIP 13 — THE THREE

### image_gen
`aspect_ratio: 9:16` · **OLD MAN** base ref

A summer night on an Arkansas porch. An elderly man rocks in a chair while a girl about ten sits on the wooden step with her knees up. Crickets implied; dark trees beyond the porch light. Cinematic Southern gothic, 1942, photoreal two-shot, dread not spectacle.

### image_to_video
`duration: 10`

The girl leans forward slightly. The old man keeps staring at the trees. The camera pushes in slowly. He does not answer.

### audio (post)

| Time | Speaker | Line |
|------|---------|------|
| 0:01.5–0:06.5 | OLD MAN (1942, on-screen) | They killed seventeen out of the twenty bushwhackers. |
| 0:06.5–0:09.0 | GIRL (1942, on-screen) | What happened to the other three? |
| 0:09.0–0:10.0 | *(silence)* | |

---

## CLIP 14 — TITLE

### image_gen
`aspect_ratio: 9:16` · use **FIELD** ref + `image_edit`

A present-day Arkansas potato field from the same angle as the historical scene. A man in a work shirt stands at the edge of a crop row, phone in hand, screen showing a map pin. August heat shimmers; the ridge tree line fills the background. Cinematic photoreal Southern gothic, dread not spectacle.

### image_to_video
`duration: 10`

The man pockets his phone without tapping the screen. He looks up at the ridge. The camera tilts slowly up from his hands to the tree line.

### audio (post)

| Time | Speaker | Line |
|------|---------|------|
| 0:01.5–0:04.5 | DANIEL (present, on-screen) | The county never wrote it down. |
| 0:04.5–0:07.5 | DANIEL (present, on-screen) | That's why the hills are still waiting. |

**end card (edit):** black 1.5s · title THE HILL · tagline Before the violence, there was dinner.

---

## FFmpeg stitch (after export)

```bash
printf "file 'clip01.mp4'\nfile 'clip02.mp4'\n..." > list.txt
ffmpeg -f concat -safe 0 -i list.txt -c copy the-hill-trailer.mp4
```

Same resolution and fps on every clip — stream copy only.

---

## Quick paste — image_gen only

```
01 Wide dining room night, untouched roasted chicken on iron platter, kerosene lamp, family in shadow, dark ridge through window, Southern gothic 1864 Ozarks, 9:16.

02 Woman in apron back to camera in dark doorway, harsh August yard beyond, wringing hands, Southern gothic 1864, 9:16.

03a Boy barefoot running low porch angle pointing up dirt road, dust plume, scared face, 1864 Ozarks, 9:16.
03b Elderly man rocking chair, girl on porch step, fireflies, 1942 Arkansas night, 9:16.

04 Gray-bearded farmer hands raised in potato field, horse silhouettes at tree line, August haze, 9:16.

05 Two women drag injured bleeding man between potato rows toward dark ridge at dusk, 9:16.

06 Injured man on quilt in cave, woman with wet cloth, child asleep on rock, moon at cave mouth, 9:16.

07 Gloved hands chiseling limestone tombstone, granite dust, partial illegible letters only, cemetery day, 9:16.

08 Empty sheriff office, blank ledger top-down, Confederate colonel portrait with badge on wall, dust in window light, 9:16.

09 Barn night, candle on crate, Union muster roll, doctor and burly man over names, 9:16.

10 Four saddled horses pre-dawn barn, doctor checking pistol, men mounting, dark timber behind, 9:16.

11 Cornfield late day, doctor trembling with pistol, rider silhouette on ridge, smoke haze, 9:16.

12 Four unbadged men line at cornfield edge dusk, blood on cuffs, doctor center looking down, 9:16.

13 Elderly man rocking, girl on porch step knees up, summer night trees beyond, 1942, 9:16.

14 Present-day potato field same angle, man work shirt phone with map pin, ridge behind, August heat, 9:16.
```

## Quick paste — image_to_video only (10s each)

```
01 Slow push-in toward chicken. Lamp flickers once. No one moves.
02 Woman one slow step toward daylight. Camera holds doorway.
03a Boy runs three steps, stops pointing. Dust drifts.
03b Slow push-in on old man's face. Girl still on step.
04 Farmer holds surrender pose, collapses forward. Static camera.
05 Slow lateral track follows women toward timber.
06 Woman wrings cloth once. Man's fingers twitch. Slow push to hands.
07 Chisel strikes twice. Slow pull back on stone.
08 Slow pan up from ledger to portrait. Empty street through door.
09 Finger moves across three names. Candle flickers. Static.
10 Horses walk into timber. Visible breath. Slow follow from behind.
11 Pistol fires wide. Rider vanishes into ridge. Static.
12 Slow push-in on doctor's face. Wind in corn.
13 Girl leans forward. Old man stares at trees. Slow push-in.
14 Phone pocketed. Look up at ridge. Slow tilt up to tree line.
```