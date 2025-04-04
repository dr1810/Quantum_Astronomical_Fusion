# Quantum_Astronomical_Fusion
# 🌌 Quantum Astronomical Fusion

A novel deep learning framework fusing classical MLP and time-series models using quantum gates for the classification of astronomical transient light curves. This project explores quantum-inspired model fusion for enhanced performance in multimodal astrophysical data analysis.

---

## 📌 Highlights

- 🔮 **Quantum Gate Fusion** of classical MLP and LSTM models
- 📈 Tested on PLAsTiCC Astronomical Lightcurve Dataset
- 🧠 Ablation study with standalone MLP, LSTM, and fused models
- 🧪 Accuracy vs Inference Time comparison
- ⚛️ Integration with TensorFlow Quantum (TFQ)
- 📝 Licensed under Creative Commons Attribution 4.0 International (CC BY 4.0)

---

## 🧬 Model Architecture

- **MLP Branch**: Handles static metadata (e.g., redshift, photoz)
- **LSTM Branch**: Processes time-series light curve data
- **Quantum Fusion Layer**: Inspired by quantum gates for feature fusion
- **Re-fusion Strategy**: Split → fuse → split → final fusion

---

## 📁 Dataset

- **PLAsTiCC (Photometric LSST Astronomical Time-series Classification Challenge)**
- Subset used from Hugging Face Datasets:  
  [`MultimodalUniverse/plasticc`](https://huggingface.co/datasets/MultimodalUniverse/plasticc)

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/dr1810/Quantum_Astronomical_Fusion.git
cd Quantum_Astronomical_Fusion

# (Optional) Create a virtual environment
python3 -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
