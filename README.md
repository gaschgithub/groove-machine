# groove-machine

🧮 **Theoretical / Conceptual Project**

## Overview

**groove-machine** represents a future research direction emerging from my work on microrhythm analysis and timing in popular music.

The project proposes an algorithmic system that, once the workflow for microrhythmic analysis is fully automated, is capable of analyzing a set of musical references and extracting high-level groove characteristics in order to generate new groove iterations.

Rather than modeling rhythm solely as a sequence of onsets, the project is grounded in perceptual, spectral, and dynamic considerations that shape how groove is experienced.

---

## Goals

In theory, the groove machine would:

- Locate not only onsets, but **P-centers (perceptual centers)** of events, and analyze their **inter-onset interval (IOI)** relationships to determine groove inflection points.
- Factor in **amplitude differences** to identify and model **dynamic accent placement**.
- Perform **spectral analysis** to relate timbral characteristics to specific rhythmic functions within a groove.
- Use the extracted information to enable **new groove generation**, informed by the analyzed references.

Given sufficient reference material, the system should be able to analyze grooves from different musical traditions and generate new, stylistically informed variations.

---

## Motivation

The project explores the possibility of generating **hybrid “heir” grooves** by combining and permuting microrhythmic features extracted from multiple genres.

This approach aims to exploit structural and perceptual commonalities across musical practices, offering a computational perspective on how new grooves can emerge from existing rhythmic knowledge.

---

## Tools (planned)

- **Python** (NumPy, pandas, matplotlib)
- **Essentia** (audio feature extraction, spectral and temporal descriptors)
- **Symbolic music processing** (MIDI-based representations)
- **Music Information Retrieval (MIR) techniques**
- **Sonic Visualiser** (analysis and validation)
- Optional: **machine learning methods** (clustering or generative modeling)

---

## References

- Toussaint, G. (2002). A mathematical analysis of African, Brazilian and Cuban clave rhythms. Bridges:
Mathematical Connections in Art, Music, and Science, 157–168. January 8, 2025, from: https://archive.bridgesmathart.org/2002/bridges2002-157.html#gsc.tab=0

---

## Status

**Status:** 🧮 Future Development  

This project is currently theoretical and intended for development **during/after a Sound and Music Computing (SMC) Master**, as part of a broader research trajectory in microrhythm, groove, and algorithmic music systems.

---

## License

All rights reserved. This repository is made public for viewing and academic evaluation purposes only.
