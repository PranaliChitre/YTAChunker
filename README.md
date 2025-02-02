YTAChunker

🚀 1st Runner-Up at NMIMS Datathon 3.0 (2025) 🎉Developed by Your Name, Teammate 1, Teammate 2, and Teammate 3

📌 Overview

YTAChunker is a Python-based application that processes YouTube videos by extracting their audio and segmenting it into smaller, meaningful chunks. This segmentation is performed using advanced speech-to-text transcription, semantic analysis, and silence detection techniques. The project also includes Q&A and summarization features powered by the Groq API for LLaMA.

🔥 Features

✅ Audio Segmentation - Extracts and splits audio based on speech patterns and silence intervals.✅ Multiple Segmentation Strategies - Offers various chunking methods like Whisper-based segmentation and semantic segmentation.✅ YouTube Video Processing - Automatically downloads videos and extracts audio.✅ Speech-to-Text Transcription - Uses Whisper AI and LangChain for accurate text conversion.✅ Q&A and Summarization - Leverages Groq API for LLaMA to provide insightful answers and summaries from extracted text.✅ TypeScript Interface - Ensures robust and scalable interaction for handling audio processing tasks.

🛠️ Installation

Prerequisites

Ensure you have Python 3.8+ and a virtual environment set up. Install dependencies with:

"""pip install -r requirements.txt"""

Additionally, install the following external dependencies:

FFmpeg (for audio processing)

sudo apt install ffmpeg  # Linux
brew install ffmpeg      # macOS
choco install ffmpeg     # Windows (via Chocolatey)

yt-dlp (for downloading YouTube videos)

pip install yt-dlp

Ensure you have a Groq API key to use LLaMA-based features. Set it as an environment variable:

export GROQ_API_KEY="your_api_key_here"

(For Windows, use set GROQ_API_KEY="your_api_key_here" in Command Prompt.)

🚀 Usage Guide

1️⃣ Download YouTube Video & Extract Audio

python app/utils/downloader.py --url "<YouTube Video URL>"

2️⃣ Segment Audio

Choose from different segmentation strategies:

Whisper Chunking:

python app/utils/whisper_chunking.py --audio temp/audio.wav

Semantic Segmentation:

python app/utils/semantic_audio_segmenter.py --audio temp/audio.wav

3️⃣ Q&A and Summarization

Run the LLaMA-powered Q&A module:

python app/utils/groq_client.py --audio temp/audio.wav

Generate a summary of the extracted content:

python app/utils/llama_segmenter.py --audio temp/audio.wav

👨‍💻 Team Members

Your Name

Teammate 1

Teammate 2

Teammate 3

🏆 Achievements

🧈 1st Runner-Up at NMIMS Datathon 3.0 (2025)🚀 Recognized for cutting-edge AI-driven speech segmentation, Q&A and summarization features, and robust TypeScript integration.

🐜 License

This project is licensed under the MIT License.

⭐ If you found this project useful, don’t forget to star the repo! ⭐

