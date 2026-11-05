# 🛣️ RoadGuard
### AI-Based Road Damage Assessment and Intelligent Maintenance Prioritization System

## 📌 About the Project

RoadGuard is an AI-based road damage assessment and maintenance prioritization system developed to improve road inspection and infrastructure management. It uses deep learning and computer vision to identify road defects such as potholes and cracks from images and videos.

The system assesses damage severity, associates detected defects with GPS locations, visualizes road conditions through GIS maps, and supports authorities in planning and prioritizing maintenance activities.

## 🎯 Objectives

- Automate road damage detection using deep learning.
- Identify different types of road defects.
- Assess the severity of detected damage.
- Map road defects using GPS coordinates.
- Visualize damaged road locations through GIS.
- Support maintenance planning and prioritization.
- Generate inspection reports for authorities.

## ✨ Key Features

- **Road Damage Detection:** Detects potholes and different types of cracks from images.
- **Video Inspection:** Processes road videos to identify damage across video frames.
- **Severity Assessment:** Categorizes detected damage based on its estimated severity.
- **GIS Mapping:** Displays road damage locations on an interactive map.
- **Maintenance Prioritization:** Helps identify roads requiring attention.
- **Authority Dashboard:** Supports inspection monitoring and maintenance management.
- **Reports:** Provides road inspection and maintenance-related reports.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Frontend:** Streamlit
- **Deep Learning:** YOLOv8, PyTorch, Ultralytics
- **Computer Vision:** OpenCV
- **Data Processing:** NumPy, Pandas
- **Database:** SQLite
- **GIS and Mapping:** Folium, GeoPandas, OSMnx

## 🏗️ Project Structure

```text
RoadGuard/
│
├── backend/
├── frontend/
├── infrastructure/
├── ml/
├── sample_data/
├── scripts/
├── docs/
├── .env.example
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Caib-4394/Main-project-Road-Guard-.git
```

### 2. Navigate to the Project

```bash
cd Main-project-Road-Guard-
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

### 4. Activate the Environment

Windows:

```bash
.venv\Scripts\activate
```

### 5. Install Dependencies

Use the project's actual dependency file:

```bash
pip install -r requirements.txt
```

### 6. Run the Application

Use the actual application entry point configured in the project. For a Streamlit entry point, the command may be:

```bash
python -m streamlit run app/main.py
```

## 🔍 Expected Outcome

RoadGuard aims to reduce the effort involved in manual road inspections by providing automated defect detection, severity assessment, location-based visualization, and maintenance decision support.

## 🚀 Future Enhancements

- Improve detection accuracy with a larger and more diverse dataset.
- Enhance severity assessment using validated road damage measurements.
- Improve GPS-based road segment identification.
- Introduce more advanced maintenance prediction methods.
- Support real-time road inspection and monitoring.

## 👩‍💻 Project

**Project Name:** RoadGuard  
**Project Type:** Final-Year Major Project  
**GitHub:** [Caib-4394](https://github.com/Caib-4394)

---

*RoadGuard – Towards safer roads through intelligent inspection and maintenance.*
