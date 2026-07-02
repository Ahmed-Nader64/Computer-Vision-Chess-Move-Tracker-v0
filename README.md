
# ♟️ Computer Vision Chess Move Tracker v0

A powerful AI-powered system that automatically detects and tracks chess moves from video footage using fine-tuned YOLO11 computer vision models. Transform your chess games into PGN files, analyze moves with Stockfish, and get comprehensive game statistics.

<img width="1201" height="842" alt="image" src="https://github.com/user-attachments/assets/a73ded5d-e971-4b68-a3dd-ed1ec1f24d9b" />

## 🎯 Features

- **Real-time Move Detection**: Uses fine-tuned YOLO11 models to detect chess pieces and board position
- **Automatic Move Validation**: Validates moves according to official chess rules
- **Multi-format Export**: Save results as PGN, JSON, CSV, or FEN
- **Stockfish Analysis** (optional): Integrate Stockfish engine for move quality analysis
- **Opening Recognition**: Automatically identifies chess openings (ECO classification)
- **Game Statistics**: Comprehensive analytics including player accuracy and move classification
- **Interactive Visualization**: Live board preview and move history display
- **Streamlit Web UI**: User-friendly interface for video processing and analysis

## 📦 Installation

### Requirements
- Python 3.9+
- OpenCV 4.x
- Chess library
- Ultralytics YOLO11
- Streamlit (for web UI)

### Setup

```bash
# Clone the repository
git clone https://github.com/Ahmed-Nader64/Computer-Vision-Chess-Move-Tracker-v0.git
cd Computer-Vision-Chess-Move-Tracker-v0

# Install dependencies
pip install -r requirements.txt

# Optional: Install Stockfish for engine analysis
# On macOS:
brew install stockfish

# On Ubuntu:
sudo apt-get install stockfish

# On Windows: Download from https://stockfishchess.org/download/
