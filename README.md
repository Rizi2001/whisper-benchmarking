# 🔬 Whisper vs Faster-Whisper Benchmarking

An **R&D-focused benchmarking repository** comparing **OpenAI Whisper** and **SYSTRAN Faster-Whisper** for local Speech-to-Text inference.

## 🎯 Purpose

Evaluate **accuracy, performance, and inference behavior** of:
- Whisper Large-V2
- Faster-Whisper Large-V2

All experiments are run **locally** using real audio samples.

## 🧪 Experiments Covered

- Inference comparison between Whisper and Faster-Whisper
- Audio format handling (OPUS → MP3)
- Language detection using Whisper base models
- Batch and single-audio transcription workflows

## 📂 Repository Structure

- `STT_Models_Comparison.ipynb`  
  → Side-by-side inference comparison (Whisper vs Faster-Whisper)

- `Whisper_Base_Model_Language_Detection.ipynb`  
  → Language detection experiments using Whisper base model

- `Whisper_Speech-to-Text.py`  
  → Script-based STT inference

- `opus_converter_mp3.py`  
  → Audio format conversion utility

- `audio/`  
  → Sample audio files used for evaluation

## 🛠️ Tech Stack

- Python  
- OpenAI Whisper  
- SYSTRAN Faster-Whisper  
- Jupyter Notebooks  
- FFmpeg

## 🧠 What This Demonstrates

- Model evaluation and benchmarking skills
- Practical understanding of speech models
- Performance-aware ML experimentation
- R&D workflows for applied ML systems

## 📌 Use Cases

- Selecting STT models for production systems
- Performance vs accuracy trade-off analysis
- Research and experimentation with speech models


