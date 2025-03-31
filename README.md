# 🌱 DigitalWeeds: Smart Detection of *Amaranthus palmeri* with AI, Drones & Mobile Tech

**DigitalWeeds** is an AI-powered system that leverages drone imagery and mobile applications to detect and monitor *Amaranthus palmeri* infestations in agricultural fields across Spain. The project integrates remote sensing, deep learning models, and real-time field data to support precision agriculture and weed management.

---

## 📸 Overview

- **AI Model**: Trained to detect *Amaranthus palmeri* from drone and smartphone images.
- **Drone Module**: Collects high-resolution aerial images.
- **Mobile App**: Displays detection maps and allows manual field validation.
- **Web Dashboard (optional)**: For centralized monitoring and reporting.

---

## 🚀 Features

- Real-time weed detection using drone and mobile inputs  
- Geolocation tagging of infected zones  
- Offline mode for field usage  
- Farmer-friendly interface with visual alerts  
- Integration-ready API for farm management platforms

---

## 📂 Project Structure

```
digitalweeds/
│
├── ai_model/              # Trained model and training scripts
├── drone_module/          # Scripts for drone image capture and preprocessing
├── mobile_app/            # Source code for Android/iOS app
├── backend_api/           # Flask/FastAPI server for AI inference
├── web_dashboard/         # Web interface for visualization (optional)
├── data/                  # Sample datasets for training and testing
└── docs/                  # Diagrams, presentations, and reports
```

---

## 🧠 AI Model

- Framework: PyTorch / TensorFlow  
- Input: Multispectral or RGB drone images  
- Output: Weed segmentation mask / bounding boxes  
- Architecture: YOLOv8 / DeepLabV3+ (configurable)  

---

## 📱 Mobile App

- Built with: Flutter / React Native  
- Features:
  - Real-time map view with weed detection
  - Image upload & feedback
  - Field notes with GPS

---

## 🛠️ Installation

### Backend
```bash
cd backend_api
pip install -r requirements.txt
python app.py
```

### Mobile App
Follow instructions in `mobile_app/README.md`

### Drone Image Processing
```bash
cd drone_module
python preprocess.py --input images/ --output tiles/
```

---

## 🌍 Deployment

- Docker setup available
- Tested with DJI drones and Android devices
- Supports integration with QGIS / Google Earth Engine

---

## 📊 Results

Add before/after visualizations, detection accuracy, performance benchmarks here.

---

## 📝 License

MIT License © 2025 DigitalWeeds Team

---

## 🤝 Acknowledgements

- European Union AgriTech Innovation Fund  
- Collaborators: University of XYZ, DroneTech Labs, AgroAI Spain

---

## 📬 Contact

For collaborations, questions or contributions, contact:  
**project.digitalweeds@yourdomain.com**
