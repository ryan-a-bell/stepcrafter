# StepCrafter 🛠🎵  
_“Craft your steps, command the rhythm.”_

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

StepCrafter is an open‑source **DDR/StepMania chart generator & visualizer**.  
Upload audio, tweak parameters, preview arrows in real‑time, then export `.sm` files for StepMania, Project OutFox, or any SM‑compatible engine.

## ✨ Features
| Category | Highlights |
| -------- | ---------- |
| **Audio Analysis** | • BPM / onset / RMS detection (librosa)<br>• Waveform, spectrogram & waterfall plots |
| **Chart Crafting** | • Easy / Medium / Hard templates<br>• Manual arrow placement & live editing<br>• Import `.sm` to overlay / remix |
| **Live Preview** | • Streamlit UI with audio scrubbing |
| **Export / Import** | • `.sm` writer & parser |
| **Pluggable Pipeline** | • Pure‑Python backend—extend with ML / DSP ideas |

## 🚀 Quick Start
```bash
git clone https://github.com/<ORG>/stepcrafter.git
cd stepcrafter
python -m venv .venv
source .venv/bin/activate    # Windows: .venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
```

## 🏗 Architecture
See [`docs/ARCHITECTURE.md`](docs/ARCHITECTURE.md).

## 🤝 Contributing
See [`CONTRIBUTING.md`](CONTRIBUTING.md).

## ⚖️ License
MIT
