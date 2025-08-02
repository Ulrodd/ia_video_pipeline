# ia_video_pipeline

![Whisper](https://img.shields.io/badge/Whisper-AI-blue)
![ffmpeg](https://img.shields.io/badge/ffmpeg-video-green)

## Description
Pipeline Python pour la génération automatisée de sous-titres :  
- Transcription audio (Whisper)
- Traduction (API DeepL ou modèles open source)
- Génération de sous-titres synchronisés (SRT)
- Montage final (incrustation des sous-titres, ajout logo/titre)

## Stack technique
- Python
- Whisper (OpenAI)
- ffmpeg (via moviepy ou subprocess)
- DeepL API (ou modèles HuggingFace/transformers selon config)

## Fonctionnalités
- Gestion des vidéos (listing, déplacement, extraction audio)
- Transcription automatique (Whisper)
- Extraction et génération de sous-titres (avec ou sans timecode)
- Traduction automatique (API/model)
- Montage vidéo : incrustation texte, titres, logo, fusion audio/vidéo
- Correction manuelle possible (via widgets Jupyter)

## Installation

```bash
git clone https://github.com/Ulrodd/ia_video_pipeline.git
cd ia_video_pipeline
```

Toutes les fonctions d'importations sont dans le notebook :-)