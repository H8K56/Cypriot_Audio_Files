# Zooniverse Audio Hosting

This repository contains audio files intended for use in a Zooniverse project. The files are hosted publicly via GitHub and linked via `manifest.csv` for ingestion by the Panoptes command-line client.

## 🔊 Audio Files

- All audio files are located in the `audio/` directory and are encoded in `.mp3` format using a target bitrate of `16k` to reduce file size while maintaining speech clarity.
- Each folder contains sub folders of the chunk audio and its transcription 

## 📝 Manifest File

The `manifest.csv` file contains the public HTTPS URLs to each audio file, along with optional metadata (e.g. title, location, catalog ID). This file can be used with the Zooniverse Panoptes CLI to upload external subjects.

### Example `manifest.csv`

```csv
URL,Title
https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/main/audio/audio1.mp3,Audio Clip 1
https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/main/audio/audio2.mp3,Audio Clip 2
