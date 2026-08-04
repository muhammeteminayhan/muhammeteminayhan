<h1 align="center">Muhammet Emin Ayhan</h1>

<p align="center">
  <b>Computer Vision &amp; Machine Learning Engineer</b>
</p>

<p align="center">
  BSc Computer Engineering — Selçuk University, 2026 · GPA 3.56 / 4.00
</p>

<p align="center">
  Perception systems that have to work outside the notebook: object detection, ALPR,
  pose geometry, tracking and sensor fusion — measured against ground truth, shipped in Docker.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/muhammet-emin-ayhan-a6a171251/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:aemin8343@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</p>

---

## 👋 About

I build **computer vision and machine learning systems** — mostly perception problems where
the input is messy and the output has to be trustworthy: a vehicle passing a roadside camera
at night, a UAV that has lost GPS, a chest X-ray, a milling process on the factory floor.

What I care about in a model is not the training curve but **what it does on data it has never
seen** — so most of the projects below report measured numbers against held-out ground truth,
including the cases where the system is deliberately silent instead of guessing.

- 🎯 Focus: **object detection & tracking · ALPR · classical CV · sensor fusion & state estimation**
- 🛠 Day-to-day: `PyTorch` · `Ultralytics YOLO` · `OpenCV` · `TensorFlow/Keras` · `scikit-learn` · `Docker`
- ✈️ AI contributor on **TEKNOFEST 2026** teams (aviation AI, road-safety AI, autonomous ground vehicle)
- 📫 **aemin8343@gmail.com**

## 🚀 Featured Projects

| Project | What it does | Measured result | Stack |
| --- | --- | --- | --- |
| [**Roadside Driver-Behaviour Analytics**](https://github.com/muhammeteminayhan/bidatalar-5g-akilli-yol-guvenligi) | Identifies a vehicle (body type, **plate**, colour) and detects driver-caused safety violations from a single night-time pass — through the windshield | **Precision 1.00 · zero false positives** (F1 0.77) | `YOLO11` · `EasyOCR` · `OpenCV` · `Docker/CUDA` |
| [**GPS-Denied UAV Localization**](https://github.com/muhammeteminayhan/gps-denied-uav-localization) | Neural dead reckoning — estimates a fixed-wing UAV's position from onboard sensors alone when GPS is gone | **44.4 m mean error after 4.5 min without GPS** (vs 328.8 m baseline) | `PyTorch` · `LSTM` · `Sensor fusion` |
| [**Deep Learning Practice**](https://github.com/muhammeteminayhan/deep-learning-practice) | CV &amp; NLP mini-projects: pneumonia detection via transfer learning, YOLOv8 vehicle tracking, CNN classification, RAG | Confusion matrix &amp; sample predictions in-repo | `TensorFlow` · `YOLOv8` · `FAISS` |
| [**Image Processing from Scratch**](https://github.com/muhammeteminayhan/image-processing-gui) | Convolution, Canny, histogram equalisation and morphology written **in raw NumPy** — no OpenCV filter calls — behind a PyQt5 UI | 16 algorithms, hand-implemented | `NumPy` · `PyQt5` |
| [**MACHINOVA — CFRP Ra Prediction**](https://github.com/muhammeteminayhan/MACHINOVA-CFRP-Ra-Prediction) | Surface-roughness prediction for CFRP milling — TUSAŞ *Lift Up* graduation project, with a desktop app and REST API | **CV R² = 0.978**, RMSE 0.012 µm | `scikit-learn` · `RSM` · `Flask` |
| [**Variant Pathogenicity Classification**](https://github.com/muhammeteminayhan/saglikta-yapay-zeka) | Missense genetic variants → pathogenic / benign, with ~55% missing features and a train/test prior shift | Leakage-controlled CV · SHAP explainability | `XGBoost` · `LightGBM` · `CatBoost` · `Optuna` |

**Also worth a look:**
[kalman-filter-tutorial](https://github.com/muhammeteminayhan/kalman-filter-tutorial) — from-scratch KF &amp; EKF with 7 worked examples including a real drone flight log ·
[LungCancerClassification](https://github.com/muhammeteminayhan/LungCancerClassification) — CatBoost, mean AUC 0.94 ·
[INGHub-Datathon-2025](https://github.com/muhammeteminayhan/INGHub-Datathon-2025) — churn prediction ·
[YeniGokboru](https://github.com/muhammeteminayhan/YeniGokboru) — PyQt5 + OpenCV live-camera control UI

> 🔒 Ongoing **TEKNOFEST 2026** competition work — *Artificial Intelligence in Aviation*
> (object detection + visual odometry) and the **İKA** autonomous ground vehicle
> (ROS 2 / Nav2 / SLAM) — stays in private repositories until the competitions close.

## 🛠 Tech Stack

**Computer Vision & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Ultralytics YOLO](https://img.shields.io/badge/Ultralytics_YOLO-00B3B3?style=flat-square&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![EasyOCR](https://img.shields.io/badge/EasyOCR-4B8BBE?style=flat-square&logoColor=white)

**Machine Learning & Data**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=flat-square&logoColor=black)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black)
![Optuna](https://img.shields.io/badge/Optuna-2E5B88?style=flat-square&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-1E88E5?style=flat-square&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Engineering & Platforms**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-41CD52?style=flat-square&logo=qt&logoColor=white)

<sub><b>Also comfortable with</b> — full-stack and mobile work from earlier projects:
Java / Spring Boot · Flutter · SwiftUI · C# / .NET · SQL · Firebase.
See <a href="https://github.com/muhammeteminayhan/hatma">hatma</a> (published Flutter app),
<a href="https://github.com/muhammeteminayhan/skillswap">skillswap</a>,
<a href="https://github.com/muhammeteminayhan/java-spring-samples">java-spring-samples</a>,
<a href="https://github.com/muhammeteminayhan/flutter-apps">flutter-apps</a>,
<a href="https://github.com/muhammeteminayhan/csharp-coursework">csharp-coursework</a>,
<a href="https://github.com/muhammeteminayhan/swiftui-playground">swiftui-playground</a>.</sub>

---

<p align="center"><i>Open to Computer Vision / Machine Learning Engineer roles — remote or Türkiye-based.</i></p>
