# SID Music Collection

A curated database of Commodore 64 SID music compositions from the golden age of 8-bit gaming (1983-2019).

## About

The SID (Sound Interface Device) was the legendary sound chip used in Commodore 64 computers. This repository documents classic game soundtracks, their composers, and provides links to resources for listening and exploring these timeless pieces.

## Repository Structure

```
sid/
├── sid.yaml          # Main database with metadata for all compositions
├── music/            # MP3 audio files (28 tracks)
└── screenshots/      # Game screenshots (PNG)
```

## Database Format

The `sid.yaml` file contains structured metadata for each composition:

- **title** - Name of the game or composition
- **composer** - Original creator(s)
- **year** - Release year
- **subtunes** - Individual tracks with:
  - DeepSID links for online playback
  - YouTube/SoundCloud links
  - MP3 file references
  - Original inspiration (when the SID version was based on existing music)
- **screenshots** - Associated game artwork

## Collection Stats

- **93** catalogued compositions
- **28** MP3 audio files included
- **4** game screenshots
- Years covered: **1983-2019**

## Featured Composers

Some of the legendary SID composers represented in this collection:

- Ben Daglish
- Rob Hubbard
- Martin Galway
- Jeroen Tel
- Chris Hülsbeck
- Jonathan Dunn
- Fred Gray
- Matt Gray

## External Resources

- [DeepSID](https://deepsid.chordian.net/) - Online SID player and archive
- [High Voltage SID Collection](https://hvsc.c64.org/) - The largest collection of SID music

## Usage

Browse `sid.yaml` to explore the collection. Each entry includes direct links to listen via DeepSID or other platforms.

Example entry:
```yaml
- title: Forbidden Forest
  composer: Paul Norman
  year: 1983
  subtunes:
    - track: 1
      deepsid: https://deepsid.chordian.net/?file=/MUSICIANS/N/Norman_Paul/Forbidden_Forest.sid
      mp3: forbidden_forest_01.mp3
  screenshots:
    - forbidden_forest.png
```

## License

This repository documents and catalogs SID music for historical and educational purposes. Original compositions remain the property of their respective creators.
