# 🛫 Runway FOD Detection using Computer Vision and Drones

This project aims to automate **runway inspection** using drones equipped with computer vision algorithms for **Foreign Object Debris (FOD)** detection. The system enhances aviation safety by reducing human dependency and enabling 24/7 real-time surveillance.

## 🚀 Project Overview

Foreign Object Debris (FOD) on airport runways can pose significant risks to aircraft operations. This project leverages:

- Deep learning models (YOLOv8, UNet, CNNs)
- Real-world and synthetic image datasets
- Onboard processing on drones

to detect and classify FOD types like tools, animals, metal, and debris accurately.

## 📦 Dataset Strategy

### ✅ Public Dataset Review
Initial attempts to use public datasets were ineffective due to lack of diversity and quality.

### 🧠 Synthetic Data (Blender)
- Simulated scenarios using Blender.
- Lacked realism; models overfitted.

### 📸 Real-World Data Collection
- Captured high-resolution images from simulated and real-world scenarios.
- Annotated using Roboflow.
- Combined with synthetic augmentation for better robustness.

## 🧠 Model Exploration

We evaluated:
- YOLOv5 / YOLOv8
- Faster R-CNN
- SSD
- RetinaNet
- EfficientDet

### 🏆 Final Model: YOLOv8
- Fast and accurate (real-time ready)
- Anchor-free detection
- High precision on diverse datasets
- Easy integration and deployment

## 💻 Deployment

- Drones equipped with onboard computers (e.g., NVIDIA Jetson)
- Real-time detection during autonomous flights
- No post-processing needed

## 📈 Results

| Feature | Outcome |
|--------|---------|
| FOD Detection | High accuracy |
| Inference | Real-time on drone |
| Dataset | Hybrid of real and synthetic |
| Conditions | Performed under varied lighting & altitudes |

## ⚙️ Technical Stack

- **Languages**: Python, C++ (optional)
- **Frameworks**: PyTorch, Ultralytics YOLOv8, Blender
- **Tools**: Roboflow, OpenCV, PicaSim (drone sim)
- **Hardware**: Drones, Jetson Nano, high-res cameras

## 🧠 Key Learnings

- Custom datasets are crucial for generalization.
- YOLOv8 balances precision and speed.
- Real-time FOD alerts improve airport safety drastically.

## 🧪 Improvements & Future Work

- Improve dataset diversity (weather, lighting, airports)
- Multiclass FOD classification (bolt, bird, plastic)
- API server deployment for real-time updates
- Optimize for low-power edge devices
- Integrate with airport infrastructure for alerts and analytics

## 🧑‍🤝‍🧑 Team Contributions

Team members contributed in:
- Model training and tuning
- Drone piloting and testing
- Dataset collection and labeling
- Blender-based synthetic generation
- Post-processing and real-time integration

## 📜 License

This project is for academic and research purposes.

---

### ✈️ Enhancing Runway Safety Through Vision and Intelligence

