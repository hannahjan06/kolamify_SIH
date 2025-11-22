<h1 align="center">Kolamify AI</h1>

<p align="center">
  Cultural Intelligence Meets Creative Technology
</p>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/hannahjan06/kolamify_SIH" alt="last commit">
  <img src="https://img.shields.io/github/languages/top/hannahjan06/kolamify_SIH?color=ed7b33&label=top%20language" alt="Python">
  <img src="https://img.shields.io/github/languages/count/hannahjan06/kolamify_SIH?label=languages" alt="languages">
</p>

<p align="center">
  Built using:
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flask-black?style=for-the-badge&logo=flask&logoColor=white">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
  <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript%20Canvas-007ACC?style=for-the-badge">
</p>

## Overview

Kolamify AI is an interactive cultural heritage platform focused on preserving and modernizing the South Indian art form known as Kolam. The system combines machine learning, generative design, and guided educational interaction to help users explore, create, and understand traditional Kolam patterns in a structured and meaningful way.

The project functions as more than a utility; it serves as a digital cultural archive and creative tool.

---

## Core Features

* **Kolam Classification**
  Upload a Kolam image and receive an automated classification of its motif and style using a fine-tuned EfficientNetB0 model.

* **Kolam Generation**
  Use AI-assisted pattern generation to explore variations and new design structures.

* **Interactive Drawing Canvas**
  A web-based drawing tool that enables users to create, save, and refine their own Kolam patterns directly in the browser.

* **AI Chat Interface**
  A research-focused conversational assistant providing historical context, technique guidance, symbolism explanations, and cultural interpretation.

* **Mood-Based Pattern Recommendations**
  Suggests design styles based on preference categories such as symmetry, complexity, and color impact.

---

## How It Works

1. Users upload or draw a Kolam.
2. The input is processed through a Python Flask backend.
3. Classification is performed using a TensorFlow model.
4. Optional AI APIs support conversation and generative logic.
5. Results are rendered in the interface and optionally stored client-side.

---

## Project Structure

```bash
kolam_app/
│
├── app.py                        # Flask backend
├── requirements.txt              # Dependencies
├── Procfile                      # Deployment support
│
├── models/
│   └── kolam_classifier.keras    # Pretrained EfficientNetB0 model
│
├── static/
│   ├── css/
│   └── js/
│
├── templates/
│   └── index.html                # Main interface
│
└── notebooks/                    # Training and preprocessing notebooks
```

---

## Getting Started

### Prerequisites

* Python 3.8+
* Flask and TensorFlow installed
* API key for chatbot integration (optional)

### 1. Clone the Repository

```bash
git clone https://github.com/hannahjan06/kolamify_SIH.git
cd kolam_app
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Application

```bash
python app.py
```

Application will be accessible at:

```
http://127.0.0.1:5000/
```

---

## Usage

* Upload an existing Kolam pattern for classification
* Generate variations using AI-assisted logic
* Draw and export custom Kolam designs
* Use the AI assistant to study cultural and design aspects
* Explore algorithm-based recommendations for inspiration or learning

---

## Tech Stack

| Layer            | Technologies                        |
| ---------------- | ----------------------------------- |
| Frontend         | HTML, CSS, JavaScript (Canvas API)  |
| Backend          | Python Flask                        |
| Machine Learning | TensorFlow/Keras (EfficientNetB0)   |
| AI Assistant     | OpenAI / Gemini (optional)          |
| Deployment       | Vercel (frontend), Render (backend) |

---

## Roadmap

* Mobile-optimized redesign
* Multi-language support including regional Indian languages
* Generative adversarial model for automated pattern synthesis
* User accounts, saving history, and community gallery
* Dataset expansion for additional motif types and accuracy improvements

---

## Contributing

Contributions are welcome in model performance, UI enhancements, dataset curation, or cultural research expansion. Submit a pull request with clear documentation of changes.

---

## Acknowledgements

* Cultural heritage documentation initiatives and Kolam research publications
* TensorFlow and open-source tooling community
* Design and accessibility research in creative interfaces

---

### Team DebugDivas

* Hannah Janawa
* Avantika Mogha
* Gargi Sharma
* Ekta Yadav
* Ankita Behera
* Anshita Yadav
