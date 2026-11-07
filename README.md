# Beat-Sync Keyframe Generator (`beat-sync-keyframe-gen`)

A lightweight open-source utility designed for mobile motion graphics creators and short-form video editors using **Alight Motion** and **CapCut**. 

## Features
- **Automated BPM & Transient Detection:** Identifies hard bass drops and percussion hits in high-tempo audio tracks (Phonk, Electronic, Drum & Bass).
- **XML Keyframe Export:** Generates ready-to-import timing markers and shake/scale keyframe XML structures.
- **Low-Spec Friendly:** Runs smoothly on dual-core laptops and Android Termux environments without heavy GPU overhead.

## Quick Usage
```bash
python beatsync.py --input track.mp3 --sensitivity 0.75 --format alight-xml

