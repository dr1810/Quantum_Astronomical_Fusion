# Quantum_Astronomical_Fusion

# Quantum Astronomical Fusion

**Author:** Dharun Ramesh  
**License:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the full implementation of our **Quantum-Enhanced Fusion Model** combining classical MLP and LSTM-based time series models with quantum circuit fusion layers, applied on the PLAsTiCC Astronomical Classification dataset.

> ⚠️ This work is developed and maintained entirely by Dharun Ramesh and is protected under Creative Commons License (CC-BY 4.0). Reuse or publication of any part of this work without proper attribution is a violation of the license terms.

---

## 📌 Citation

Please cite this repository as follows:

```bibtex
@software{ramesh2025quantumfusion,
  author = {Dharun Ramesh},
  title = {Quantum Astronomical Fusion},
  year = {2025},
  version = {1.0.0},
  url = {https://github.com/dr1810/Quantum_Astronomical_Fusion},
  license = {CC-BY-4.0}
}



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
