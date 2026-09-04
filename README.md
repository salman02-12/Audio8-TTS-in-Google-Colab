# 🎙️ Audio8-TTS: Free & Fast Zero-Shot Voice Cloning in Google Colab

This repository contains an easy-to-use Google Colab notebook for running **Audio8-TTS**. This AI tool allows you to turn text into highly realistic speech and perform zero-shot voice cloning using only a short audio clip. It runs completely for free in Google Colab using a T4 GPU.

**🎥 Watch the Tutorial:** [Fastest Voice Clone for FREE | Text to Speech AI](https://www.youtube.com/watch?v=hjX7bYoCY7w) by [@CoinNoin](https://www.youtube.com/@CoinNoin)

**🚀 Run in Colab:** [Open Google Colab Notebook](https://colab.research.google.com/drive/1ZJ7Y0M1238D15V49MhlkFEC4bqHFqMR9?usp=sharing)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/salman02-12/Audio8-TTS-in-Google-Colab/blob/main/Audio8-TTS%20%40CoinNoin.ipynb)
---

## ✨ Features Supported in this Notebook

This notebook makes it easy to run Audio8-TTS without complex coding. 

*   **Multi-Language Support:** Cantonese, Chinese, Dutch, English, French, German, Italian, Japanese, Korean, Polish, Spanish.
*   **Two Model Options:** 
    *   `Audio8-TTS-Preview-0.6B (High Quality)`
    *   `Audio8-TTS-Preview-0.1B (Fast/Hybrid)`
*   **Standard Text-to-Speech:** Generate high-quality speech without a reference voice.
*   **Zero-Shot Voice Cloning:** Clone a voice by simply providing a target script, a short `.wav` reference audio, and the exact transcript of that reference audio.

## 🛠️ How to Use

1. Open the [Colab link](https://colab.research.google.com/drive/1ZJ7Y0M1238D15V49MhlkFEC4bqHFqMR9?usp=sharing).
2. Go to **Runtime > Change runtime type** and ensure **T4 GPU** is selected.
3. **Step 1:** Run the cell to install the necessary dependencies (PyTorch, Transformers, etc.).
4. **Step 2:** Select your preferred model (0.6B for quality, 0.1B for speed) from the dropdown and run the cell to load it. 
5. **Step 3 (Standard TTS):** Type your target text and run the cell to generate audio.
6. **Step 4 (Voice Cloning):** 
    *   Type the text you want generated.
    *   Type the *exact* transcript of the reference audio you are about to use.
    *   Run the cell and you will be prompted to upload your reference `.wav` file. The AI will then generate your cloned audio!

## 🤝 Credits
* **Tutorial & Notebook Creator:** [CoinNoin](https://www.youtube.com/@CoinNoin)
* **Underlying AI Model:** [Audio8-TTS](https://huggingface.co/AutoArk-AI/Audio8-TTS-Preview-0.6b)
