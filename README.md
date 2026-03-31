# 🇬🇧 PhonemeBase — British English Sound Learning Platform

> *Because learning sounds makes you stand out. British RP is the foundation — master it first.*

**🔗 Live site → [rp-phonetics-guide.vercel.app](https://rp-phonetics-guide.vercel.app/)**

---

## What is this?

Most people learn English by memorizing spelling. That's backwards.

**PhonemeBase** starts where language actually starts — **sound**. Specifically, the 44 phonemes of **Received Pronunciation (RP) British English** — the clearest, most documented accent in the world, and the reference point for every major pronunciation dictionary (Oxford, Cambridge, Longman).

If you can hear and reproduce these 44 sounds, you can read IPA transcriptions, learn any English accent faster, and stop guessing how a word sounds. This project is the foundation of a larger phonetics learning platform, built in stages.

---

## Current Build — v1 (Live)

A fully interactive web reference for all 44 RP British phonemes.

### The 44 sounds

**20 Vowels**
- 7 Short vowels — ɪ e æ ɒ ʌ ʊ ə
- 5 Long vowels — iː ɑː ɔː uː ɜː
- 8 Diphthongs — eɪ əʊ aɪ aʊ ɔɪ ɪə eə ʊə

**24 Consonants**
- 6 Plosives — p b t d k ɡ
- 9 Fricatives — f v θ ð s z ʃ ʒ h
- 2 Affricates — tʃ dʒ
- 3 Nasals — m n ŋ
- 4 Approximants — l r j w

### Features
- Click any card → modal with IPA symbol, keyword word, articulation tip, and example words
- Live British audio pulled from the Free Dictionary API (Google UK MP3s)
- Click any example word to hear it in a British accent
- Colour-coded by phoneme category with scroll-triggered animations
- Fully responsive — works on mobile

---

## Why British RP?

RP is non-rhotic (the 'r' in "car" is silent — pure vowel, no American curl), has clearly distinct vowel lengths, and is the basis for every major pronunciation dictionary. Once you have RP internalized, you have the *map*. You can navigate to any other accent — American, Australian, Scottish — by understanding what changed and why.

Most learners skip phonetics entirely and wonder why their pronunciation stays stuck. This platform skips that mistake.

---

## Roadmap

### Phase 2 — Structured Learning Paths
- Guided lessons by difficulty and frequency (not alphabetical)
- Minimal pair drills: ship/sheep, bit/bet, cat/cut — the contrasts that trip learners up most
- IPA transcription exercises: type the phonetic transcription of a word

### Phase 3 — ML Models
- **Pronunciation scoring** — record yourself, compare to native British audio using MFCCs and spectrograms
- **Pattern detection** — identify which phonemes a specific learner consistently gets wrong
- **Personalised practice queue** — spaced repetition based on your error patterns, not a fixed syllabus

### Phase 4 — Full Learning Platform
- User accounts with progress tracking
- Phoneme confusion heatmaps (your personal weak zones)
- Syllable stress and connected speech (reduction, linking, elision)
- Transcription mode — type IPA from audio, graded in real time

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML/CSS/JS — single file, zero dependencies |
| Fonts | Playfair Display, DM Sans, DM Mono (Google Fonts) |
| Audio | Free Dictionary API → Google UK MP3s |
| Hosting | Vercel |

---

## Run locally

```bash
# Clone and open — no install needed
open british_phonemes.html

# Or serve locally to avoid browser audio policy issues
python3 -m http.server 8000
# → http://localhost:8000/british_phonemes.html
```

---

> Most people can't hear the difference between /ɪ/ and /iː/ until someone points it out. After that, they can never un-hear it. That's the whole point of this project.

*Sounds come before spelling. Always.*
