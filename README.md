# Lenny's Podcast Transcripts Archive

A database repository containing transcripts from [Lenny's Podcast](https://www.lennyspodcast.com/), open-sourced by Lenny Rachitsky.

## Data Location

All transcripts are stored in the `transcripts/` folder.

## Data Format

- **File format:** Plain text (`.txt`)
- **Naming convention:** `{Guest Name}.txt` (e.g., `Ada Chen Rekhi.txt`)
- **Content structure:** Timestamped dialogue with speaker labels
  ```
  Speaker Name (HH:MM:SS):
  Transcript text...
  ```
- **Total transcripts:** 286 episodes

## Data Description

Lenny's Podcast features interviews with world-class product leaders and growth experts sharing insights on building and growing successful products. Topics include:

- Product management and strategy
- Growth and marketing
- Startup building and scaling
- Leadership and career development
- Company culture and team building

## Source

Original transcripts open-sourced by Lenny Rachitsky: https://t.co/DwBhryFF7d

## Usage with OpenProse

This repository is structured as a database for OpenProse program execution. Programs can access transcript data at:

```
./transcripts/*.txt
```

Each file contains a complete episode transcript with timestamps and speaker attribution.
