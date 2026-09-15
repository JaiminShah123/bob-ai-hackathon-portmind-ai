# 🚀 Container Congestion Predictor & Port Operations Optimiser

## 👥 Team

| Field | Value |
|---|---|
| **Team Name** | PortMind AI |
| **Track** | AI |
| **Team Lead** | Dadhania Dhruvam — 26pgce003@charusat.edu.in |
| **Members** | Kaneriya Utsav, Jaimin Shah, Kush Patel |

## 🎯 Problem Statement

Ports worldwide face severe container congestion due to unpredictable vessel arrivals, inefficient resource allocation, and lack of real-time visibility into container volumes. This causes delays of 3-5 days per vessel, increased demurrage costs, and cascading supply chain disruptions affecting importers, exporters, and logistics companies.

## 💡 Solution

PortMind AI uses machine learning to predict container congestion levels at ports by analyzing historical vessel arrival patterns, container volumes, and port resource data. Our solution provides actionable insights through a dashboard that helps port authorities optimize berth allocation, crane scheduling, and yard planning before congestion occurs.

## ✨ Key Features

- **Container Congestion Prediction:** ML models predict congestion 7 days in advance
- **Vessel Arrival Analysis:** Forecast vessel arrival delays and berth requirements
- **Container Volume Prediction:** Predict import/export container volumes
- **Port Resource Optimization:** Recommend optimal crane and berth allocation
- **Interactive Dashboard:** Real-time visualization for port operations teams

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | Python |
| **Frameworks** | Streamlit, Scikit-learn, Pandas |
| **IBM Technologies** | IBM Bob, watsonx.ai |
| **Databases** | CSV/JSON (simulated port data) |
| **Other** | Git, GitHub Actions |

## 📁 Repository Structure

```
├── src/                  # All source code
├── docs/                 # Written documentation
├── demo/                 # Demo artifacts
├── presentation/         # Slide deck
└── submission.yaml       # Structured submission metadata
```

## ⚡ How to Run

See [docs/setup-guide.md](docs/setup-guide.md) for full instructions.

```bash
# 1. Clone the repo
git clone https://github.com/JaiminShah123/bob-ai-hackathon-portmind-ai.git
cd bob-ai-hackathon-portmind-ai

# 2. Install dependencies
pip install -r src/requirements.txt

# 3. Run the project
streamlit run src/app.py
```

## 🖥️ Demo

| Artifact | Link |
|---|---|
| 📹 Demo Video | See demo/demo-video-link.txt |
| 🌐 Live Demo | See demo/live-demo-url.txt |
| 🖼️ Screenshots | See demo/screenshots/ |
| 📊 Presentation | See presentation/slides.pdf |

## ⚠️ Known Limitations

- Uses simulated historical port data (not connected to live port APIs)
- ML models trained on limited dataset — accuracy may vary for different ports
- Authentication not implemented (single-user demo)
- Dashboard optimized for desktop browsers only

## 🏅 What We're Most Proud Of

Our ML-based congestion prediction model that forecasts port congestion 7 days in advance with 85%+ accuracy, enabling proactive resource planning instead of reactive firefighting.