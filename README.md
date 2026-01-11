# Speech-to-Reasoning Pipeline Using Whisper and Quantized LLMs

This repository presents an **end-to-end speech-to-reasoning pipeline** that converts spoken audio into meaningful, logically structured responses using **OpenAI Whisper** for speech recognition and **quantized large language models** for reasoning.

The system is designed to run efficiently in **GPU-constrained environments such as Google Colab**, with a focus on memory optimization and practical AI system design.

---

## Project Overview

Speech-based AI systems typically require significant computational resources.  
This project demonstrates how speech understanding and logical reasoning can be combined efficiently by leveraging **automatic speech recognition (ASR)** and **low-precision large language models**.

The pipeline first transcribes audio input into text using Whisper and then processes the transcription using a **quantized reasoning-focused LLM**, producing structured and meaningful responses.

---

## Architecture Overview

1. **Audio Input**
   - User provides spoken input in common audio formats

2. **Speech-to-Text (ASR)**
   - OpenAI Whisper transcribes audio into text
   - Audio resampling and encoding handled efficiently

3. **Prompt Construction**
   - Transcribed text is formatted into a reasoning-oriented prompt

4. **Reasoning with Quantized LLM**
   - A dynamic 4-bit quantized LLM performs logical reasoning or question answering
   - Memory-efficient inference enabled via quantization

5. **Output Generation**
   - Final response is generated and displayed

6. **GPU Memory Monitoring**
   - VRAM usage tracked to demonstrate efficiency

---

## Technologies Used

- **Python**
- **OpenAI Whisper (ASR)**
- **Unsloth Dynamic 4-bit Quantized LLMs**
- **Hugging Face Transformers**
- **PyTorch**
- **Librosa**
- **Google Colab (GPU Execution)**

---

## Why Quantized LLMs

- Significantly reduce GPU memory usage
- Enable large models to run on limited hardware
- Maintain strong reasoning performance
- Suitable for real-time and cost-effective AI systems

---

## Key Features

- End-to-end speech-to-reasoning pipeline
- Efficient audio transcription
- Logical and structured AI responses
- Low-VRAM optimized inference
- Clean and modular notebook design

---

## How to Run

1. Open the notebook in **Google Colab**
2. Enable GPU runtime
3. Install required dependencies
4. Upload or record an audio file
5. Run cells sequentially to:
   - Transcribe audio
   - Perform reasoning
   - Display final output

---

## Use Cases

- Voice-based question answering
- AI assistants with speech input
- Accessibility-focused applications
- Research and educational demos

---

## Author

Developed as part of an **AI internship project**, focusing on speech processing, reasoning systems, and efficient LLM deployment.
