# Insightify 🎥📝

A Gradio app that:
- Extracts YouTube captions (preferred)
- Falls back to Whisper audio transcription (optional)
- Summarizes using HuggingFace Transformers
- Translates summaries to multiple languages
- Exports results to Word/PDF
- Shows an embedded YouTube preview (iFrame)

## Features
- Smart caching: update summary length/model without re-processing the video
- GPU → CPU fallback for stability
- Cleans transcript to remove quiz/Q&A parts for better summaries

## Setup
### 1) Create a virtual environment (optional)
```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# mac/linux:
source .venv/bin/activate
