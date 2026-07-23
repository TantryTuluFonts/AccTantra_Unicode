# Tulu-Tigalari (AccTantra) Keyboard — Typing Guide

**Version:** 1.4.2 · **Engine:** Keyman 15.0+ · **Script:** Tulu-Tigalari (Unicode U+11380–U+113FF)

---

## What is this keyboard?

This keyboard lets you type in the **Tulu-Tigalari script** — the classical script of the Tulu language and historically used to write Sanskrit texts along the Tulu Nadu coast. It follows the **AccTantra / Mallige** input convention, which maps letters phonetically onto a standard QWERTY keyboard.

If you already type Kannada, Malayalam, or Devanagari on a phonetic keyboard, you will feel at home immediately. The vowels, consonants, and matras all work on the same phonetic logic.

---

## Core idea: how Indic keyboard input works

Every Indic script has two kinds of vowels:

- **Independent vowels** — used at the start of a syllable (e.g. the word *aḍḍe* begins with an independent A).
- **Vowel signs (matras)** — the same vowel attached to a consonant (e.g. the ā in *kā* is not the letter A, it is the ā-sign sitting on top of KA).

This keyboard handles that automatically. You never have to think about which form to use — just type the consonant, then the vowel, and the right form appears.

---

## Vowels

### Independent vowels (no consonant before them)

Type these when the vowel begins a syllable on its own.

| Keys | Tulu-Tigalari | Devanagari | Kannada | Malayalam | Sound |
|------|--------------|------------|---------|-----------|-------|
| `a` | 𑎀 | अ | ಅ | അ | short a |
| `aa` | 𑎁 | आ | ಆ | ആ | long ā |
| `i` | 𑎂 | इ | ಇ | ഇ | short i |
| `I` | 𑎃 | ई | ಈ | ഈ | long ī |
| `u` | 𑎄 | उ | ಉ | ഉ | short u |
| `U` | 𑎅 | ऊ | ಊ | ഊ | long ū |
| `e` | 𑎋 | ए | ಎ | എ | short e |
| `E` | 𑎎 | ऐ | ಏ | ഏ | long ē |
| `o` | 𑎐 | ओ | ಒ | ഒ | short o |
| `O` | 𑎑 | ओ | ಓ | ഓ | long ō |
| `R` | 𑎆 | ऋ | ಋ | ഋ | vocalic ṛ |
| `RR` | 𑎇 | ॠ | ೠ | ൠ | vocalic ṝ (long) |

> `aa` works by upgrading: press `a` once to get short A, press `a` again immediately and it becomes long Ā. This mirrors how many South Indian phonetic keyboards work.

> `RR` works the same way: `R` gives ṛ, press `R` again and it becomes ṝ.

---

### Vowel signs (matras) — after a consonant

When you type a vowel key **immediately after a consonant**, the keyboard automatically inserts the correct matra form. You do not type anything different — the context is detected for you.

| Keys | Sign attaches as | Devanagari example | Kannada | Malayalam | Result |
|------|------------------|--------------------|---------|-----------|--------|
| `ka` | ā-matra | का | ಕಾ | കാ | kā |
| `ki` | i-matra | कि | ಕಿ | കി | ki |
| `kI` | ī-matra | की | ಕೀ | കീ | kī |
| `ku` | u-matra | कु | ಕು | കു | ku |
| `kU` | ū-matra | कू | ಕೂ | കൂ | kū |
| `ke` | e-matra | के | ಕೆ | കെ | ke |
| `kE` | ai-matra | कै | ಕೈ | കൈ | kai |
| `ko` | o-matra | को | ಕೊ | കൊ | ko |
| `kO` | ō-matra | को | ಕೋ | കോ | kō |
| `kR` | ṛ-matra | कृ | ಕೃ | കൃ | kṛ |
| `kRR` | ṝ-matra | कॄ | ಕೄ | കൄ | kṝ |

> There is no short-a matra in this script (as in most Brahmic scripts — the inherent vowel *is* the short a). So `ka` gives the ā sign, which is the only explicit matra needed for a-class vowels. The bare consonant (with virama) represents the pure consonant without any vowel.

---

## Consonants

All consonants are on their phonetically expected QWERTY key. Aspirated consonants (kh, gh, ch …) are on **Shift** of the same key.

### Velars — k, kh, g, gh, ṅ

| Keys | Tulu-Tigalari | Devanagari | Kannada | Malayalam | Letter |
|------|--------------|------------|---------|-----------|--------|
| `k` | 𑎒 | क | ಕ | ക | ka |
| `K` | 𑎓 | ख | ಖ | ഖ | kha |
| `g` | 𑎔 | ग | ಗ | ഗ | ga |
| `G` | 𑎕 | घ | ಘ | ഘ | gha |
| `z` | 𑎖 | ङ | ಙ | ങ | ṅa (velar nasal) |

### Palatals — c, ch, j, jh, ñ

| Keys | Tulu-Tigalari | Devanagari | Kannada | Malayalam | Letter |
|------|--------------|------------|---------|-----------|--------|
| `c` | 𑎗 | च | ಚ | ച | ca |
| `C` | 𑎘 | छ | ಛ | ഛ | cha |
| `j` | 𑎙 | ज | ಜ | ജ | ja |
| `J` | 𑎚 | झ | ಝ | ഝ | jha |
| `Z` | 𑎛 | ञ | ಞ | ഞ | ña (palatal nasal) |

### Retroflex stops — ṭ, ṭh, ḍ, ḍh

| Keys | Tulu-Tigalari | Devanagari | Kannada | Malayalam | Letter |
|------|--------------|------------|---------|-----------|--------|
| `q` | 𑎜 | ट | ಟ | ട | ṭa |
| `Q` | 𑎝 | ठ | ಠ | ഠ | ṭha |
| `w` | 𑎞 | ड | ಡ | ഡ | ḍa |
| `W` | 𑎟 | ढ | ಢ | ഢ | ḍha |

### Dentals — t, th, d, dh, n; retroflex ṇ

| Keys | Tulu-Tigalari | Devanagari | Kannada | Malayalam | Letter |
|------|--------------|------------|---------|-----------|--------|
| `t` | 𑎡 | त | ತ | ത | ta |
| `T` | 𑎢 | थ | ಥ | ഥ | tha |
| `d` | 𑎣 | द | ದ | ദ | da |
| `D` | 𑎤 | ध | ಧ | ധ | dha |
| `n` | 𑎥 | न | ನ | ന | na |
| `N` | 𑎠 | ण | ಣ | ണ | ṇa (retroflex nasal) |

### Labials — p, ph, b, bh, m

| Keys | Tulu-Tigalari | Devanagari | Kannada | Malayalam | Letter |
|------|--------------|------------|---------|-----------|--------|
| `p` | 𑎦 | प | ಪ | പ | pa |
| `P` | 𑎧 | फ | ಫ | ഫ | pha |
| `b` | 𑎨 | ब | ಬ | ബ | ba |
| `B` | 𑎩 | भ | ಭ | ഭ | bha |
| `m` | 𑎪 | म | ಮ | മ | ma |

### Semivowels and sibilants — y, r, l, v, ś, ṣ, s, h

| Keys | Tulu-Tigalari | Devanagari | Kannada | Malayalam | Letter |
|------|--------------|------------|---------|-----------|--------|
| `y` | 𑎫 | य | ಯ | യ | ya |
| `r` | 𑎬 | र | ರ | ര | ra |
| `l` | 𑎭 | ल | ಲ | ല | la |
| `L` | 𑎳 | ळ | ಳ | ള | ḷa (retroflex l) |
| `v` | 𑎮 | व | ವ | വ | va |
| `S` | 𑎯 | श | ಶ | ശ | śa (palatal sibilant) |
| `x` | 𑎰 | ष | ಷ | ഷ | ṣa (retroflex sibilant) |
| `s` | 𑎱 | स | ಸ | സ | sa |
| `h` | 𑎲 | ह | ಹ | ഹ | ha |

---

## The virama (halant) — ending a syllable or making a pure consonant

In Tulu-Tigalari, there are two viramas:

- **Chandravirama** — the crescent-shaped virama, used on most consonants.
- **Suryavirama** — the looped virama, used on the "surya" class of consonants (k, g, ṭ, ṇ, t, d, n, m, h, bh, ḷ, r).

The keyboard handles the choice **automatically**. You just press `A` (Shift+A) after a consonant and the right one appears.

| Situation | Keys | Result |
|-----------|------|--------|
| Pure consonant (any) | consonant + `A` | consonant + appropriate virama |
| Bare virama (no consonant) | `A` | chandravirama |

Examples:

| Keys | Result | Note |
|------|--------|------|
| `kA` | 𑎒𑏎 | KA with chandravirama |
| `rA` | 𑎬𑏏 | RA with suryavirama (auto-detected) |
| `nA` | 𑎥𑏎 | NA with suryavirama (auto-detected) |
| `tA` | 𑎡𑏎 | TA with suryavirama (auto-detected) |

---

## Conjuncts — joining two consonants

When two consonants join without a vowel between them, you use the **conjoiner** (`[` key). The keyboard also provides a shortcut: typing a virama and then the next consonant automatically upgrades the virama into the correct conjoiner.

### Method 1 — virama auto-upgrade (recommended)

Type: **first consonant + `A` + second consonant**

The chandravirama/suryavirama is automatically replaced by the conjoiner U+113D0.

| Keys | Result | Kannada equivalent |
|------|--------|--------------------|
| `kAk` | 𑎒𑏐𑎒 | ಕ್ಕ (kka) |
| `kAt` | 𑎒𑏐𑎡 | ಕ್ತ (kta) |
| `rAk` | 𑎬𑏐𑎒 | ರ್ಕ (rka) |
| `nAt` | 𑎥𑏐𑎡 | ನ್ತ (nta) |

### Method 2 — explicit conjoiner

Type: **first consonant + `[` + second consonant**

Use `[` (the conjoiner key) when you want more control, or when you need to insert a conjoiner without going through a virama first.

### Repha

Repha is automatically handled by font, nevertheless for more control, the repha form (r-above) is typed with `]`.

| Keys | Result | Equivalent |
|------|--------|------------|
| `]k` | 𑏑𑎒 | र्क / ರ್ಕ with above-form |

### Zero-width non-joiner (ZWNJ)

To prevent two consonants from forming a conjunct, insert a ZWNJ with `X` (Shift+X) between them.

| Keys | Result |
|------|--------|
| `kAXk` | 𑎒𑏏 + ZWNJ + 𑎒 — two separate ka's, not a conjunct |

---

## Diacritics — anusvara, visarga, candra anunasika

| Keys | Mark | Devanagari | Kannada | Malayalam | Use |
|------|------|------------|---------|-----------|-----|
| `M` (Shift+M) | anusvara | ं | ಂ | ം | nasal resonance |
| `H` (Shift+H) | visarga | ः | ಃ | ഃ | breathy h-sound |
| `MM` | candra anunasika | ँ | ಁ | — | nasalised vowel |

The `MM` sequence works like the vowel doublers: type `M` once for anusvara, press `M` again immediately and it upgrades to the candra anunasika.

Examples:

| Keys | Result | Devanagari equivalent |
|------|--------|-----------------------|
| `kaM` | 𑎒𑎸𑏌 | कां |
| `kaH` | 𑎒𑎸𑏍 | काः |
| `kaMM` | 𑎒𑎸𑏊 | काँ |

---

## Special marks — Shrii and Om Pushpikas

The Tulu-Tigalari script has two decorative invocation marks called **pushpikas**, traditionally written at the head of manuscripts.

### Om Pushpika (𑏗)

Spell out the syllable **Om** and end with `A`:

```
o  m  A  →  𑏗
```

That is: `o` (independent O) + `m` (MA consonant) + `A` (virama-key) → Om Pushpika.

### Shrii Pushpika (𑏘)

Spell out **ShrI** (SHA + conjoiner + RA + long-I):

```
S  [  r  I  →  𑏘
```

That is: `S` (SHA) + `[` (conjoiner) + `r` (RA) + `I` (long II) → Shrii Pushpika.

---

## Punctuation

| Keys | Mark | Name |
|------|------|------|
| `.` or `,` | 𑏔 | Danda (single) |
| `/` or `<` or `>` | 𑏕 | Double danda |
| `;` | ; | Literal semicolon |

---

## Numbers

| Keys | Tulu-Tigalari digit | Kannada digit | Value |
|------|---------------------|---------------|-------|
| `0` | 𑃆 | ೦ | 0 |
| `1` | 𑃇 | ೧ | 1 |
| `2` | 𑃈 | ೨ | 2 |
| `3` | 𑃉 | ೩ | 3 |
| `4` | 𑃊 | ೪ | 4 |
| `5` | 𑃋 | ೫ | 5 |
| `6` | 𑃌 | ೬ | 6 |
| `7` | 𑃍 | ೭ | 7 |
| `8` | 𑃎 | ೮ | 8 |
| `9` | 𑃏 | ೯ | 9 |

Shift+number gives the **Tulu-Tigalari native numerals** (U+113F0–U+113F9):

| Keys | Tulu-Tigalari native |
|------|----------------------|
| `!` (Shift+1) | 𑏱 |
| `@` (Shift+2) | 𑏲 |
| … | … |
| `)` (Shift+0) | 𑏰 |

---

## Complete key reference

### Unshifted keys

| Key | Output | Key | Output |
|-----|--------|-----|--------|
| `a` | 𑎀 (independent short A) | `n` | 𑎥 (NA) |
| `b` | 𑎨 (BA) | `o` | 𑎐 (independent O) |
| `c` | 𑎗 (CA) | `p` | 𑎦 (PA) |
| `d` | 𑎣 (DA) | `q` | 𑎜 (ṬA) |
| `e` | 𑎋 (independent E) | `r` | 𑎬 (RA) |
| `f` | f (unmapped) | `s` | 𑎱 (SA) |
| `g` | 𑎔 (GA) | `t` | 𑎡 (TA) |
| `h` | 𑎲 (HA) | `u` | 𑎄 (independent U) |
| `i` | 𑎂 (independent I) | `v` | 𑎮 (VA) |
| `j` | 𑎙 (JA) | `w` | 𑎞 (ḌA) |
| `k` | 𑎒 (KA) | `x` | 𑎰 (ṢA) |
| `l` | 𑎭 (LA) | `y` | 𑎫 (YA) |
| `m` | 𑎪 (MA) | `z` | 𑎖 (ṄA) |
| `[` | 𑏐 (conjoiner) | `]` | 𑏑 (repha) |
| `,` | 𑏔 (danda) | `.` | 𑏔 (danda) |
| `/` | 𑏕 (double danda) | `;` | ; (semicolon) |

### Shifted keys

| Keys | Output | Keys | Output |
|------|--------|------|--------|
| `A` | 𑏎 (virama / halant) | `N` | 𑎠 (ṆA) |
| `B` | 𑎩 (BHA) | `O` | 𑎑 (independent OO / ō) |
| `C` | 𑎘 (CHA) | `P` | 𑎧 (PHA) |
| `D` | 𑎤 (DHA) | `Q` | 𑎝 (ṬTHA) |
| `E` | 𑎎 (independent EE / ē) | `R` | 𑎆 (vocalic ṛ) |
| `G` | 𑎕 (GHA) | `S` | 𑎯 (ŚA) |
| `H` | 𑏍 (visarga) | `T` | 𑎢 (THA) |
| `I` | 𑎃 (independent II / ī) | `U` | 𑎅 (independent UU / ū) |
| `J` | 𑎚 (JHA) | `V` | (unmapped) |
| `K` | 𑎓 (KHA) | `W` | 𑎟 (ḌDHA) |
| `L` | 𑎳 (ḶA retroflex) | `X` | 𑆃 (ZWNJ) |
| `M` | 𑏌 (anusvara) | `Y` | (unmapped) |
| `Z` | 𑎛 (ÑA) | | |

---

## Typing examples — word by word

Below are some examples showing exactly what keys to press.

### tulu (𑎡𑎲𑎬𑎬)
```
t  u  l  u
```
TA + u-matra + LA + u-matra

### kaara (𑎒𑎸𑎬)
```
k  aa  r  a
```
KA + ā-matra (via `a`) + RA + ā-matra (via `a`)

> Remember: `a` after a consonant gives the ā matra. So `ka` = kā, `ra` = rā.

### nakShatra (𑎥𑎒𑏐𑏐𑎰𑎡𑎬)
```
n  k  A  x  A  t  r  a
```
NA + virama-auto → conjoiner + ṢA + virama-auto → conjoiner + TA + RA + ā-matra

### shrii (𑎯𑏐𑎬𑎺)
```
S  [  r  I
```
ŚA + conjoiner + RA + ī-matra

---

## Backspace behaviour

The keyboard has smart backspace. When you delete over a consonant+matra unit, the first backspace removes the matra and leaves the bare consonant. A second backspace removes the consonant. This matches how other Indic keyboards behave and keeps the text logically consistent.

---

## Keys that pass through unchanged

Any key not listed above outputs its normal ASCII character. This includes: `` ` `` `~` `-` `_` `=` `+` `'` `"` `\` `|` and all function keys.

---

## Quick-start cheat sheet

```
VOWELS (standalone)          CONSONANTS (unshifted = plain, Shift = aspirate)
  a  = short A (𑎀)            k/K  g/G  z      (velar)
  aa = long Ā  (𑎁)            c/C  j/J  Z      (palatal)
  i  = I  (𑎂)                 q/Q  w/W  N      (retroflex stops + ṇ)
  I  = Ī  (𑎃)                 t/T  d/D  n      (dental)
  u  = U  (𑎄)                 p/P  b/B  m      (labial)
  U  = Ū  (𑎅)                 y  r  l  L  v   (semivowels)
  e  = E  (𑎋)                 S  x  s  h      (sibilants + ha)
  E  = Ē  (𑎎)
  o  = O  (𑎐)             VIRAMA / HALANT
  O  = Ō  (𑎑)               A (Shift+A)  →  virama (auto chandravirama or suryavirama)
  R  = ṛ  (𑎆)
  RR = ṝ  (𑎇)             CONJUNCTS
                             consonant + A + consonant   →  conjunct (virama auto-upgrades)
MATRAS (after consonant)     [  →  explicit conjoiner
  ka  = kā    kR  = kṛ       ]  →  repha
  ki  = ki    kRR = kṝ       X  →  ZWNJ (prevent conjunct)
  kI  = kī
  ku  = ku    DIACRITICS     PUNCTUATION
  kU  = kū      M = anusvara   ,  .  →  danda
  ke  = ke      H = visarga    /  <  >  →  double danda
  kE  = kai    MM = candra     ;  →  semicolon (literal)
  ko  = ko
  kO  = kō
```
