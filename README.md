1. Project Overview

TruthLens AI is an AI-powered misinformation intelligence platform designed to detect deepfake images and analyze suspicious digital content.

With the rapid rise of AI-generated media, it has become increasingly difficult to distinguish authentic content from manipulated content. TruthLens AI provides a solution by combining deepfake detection, image forensics, misinformation analysis, and visual intelligence tools in one unified dashboard.

The platform helps users verify digital content, detect manipulated media, and analyze misinformation trends through a clean and interactive AI interface.

What Problem Does It Solve?

Challenge                          TruthLens AI Solution
---------------------------------------------------------------------
AI-generated deepfake images       Automated deepfake detection system
Hidden image manipulation          Visual forensic heatmap analysis
Unverified digital content         AI authenticity scoring
Misinformation spread              Global misinformation visualization
Unverified news claims             AI fact-check assistant
Unreliable news sources            Credibility scoring system


2. Features

🧠 Deepfake Detection Engine

Upload an image and the AI model analyzes whether it is authentic or manipulated.

Output includes:
• Authenticity score
• Prediction result (Real / Fake)
• Confidence indicator


🔬 Image Forensics Heatmap

Generates a visual heatmap highlighting suspicious regions within the image.

Helps identify:
• Pixel inconsistencies
• Lighting mismatches
• Potential AI-generated artifacts


🌍 Misinformation Spread Visualization

Interactive global dashboard showing how fake content spreads across regions.

Displays:
• Country-level misinformation activity
• Spread intensity visualization
• Interactive world map


🤖 AI Fact-Check Assistant

Users can paste a news claim and the system estimates credibility probability.

Example Output

Claim: “New virus spreading globally”

Result:
Credibility Score: 34%
Status: Possible misinformation


📰 News Source Credibility Checker

Evaluate the trustworthiness of a news website.

Output includes:
• Trust Score (0-100)
• Risk level classification
• Credibility indicator


📊 Trending Fake Topics

Displays commonly circulating misinformation topics such as:

• Celebrity deepfake scandals
• Election misinformation
• Health rumors
• Cryptocurrency scams


👥 Community Reporting System

Users can report suspicious digital content to improve misinformation detection systems in future iterations.



3. Installation

Prerequisites

Python 3.9+
pip package manager


Setup

# 1 Navigate to the project directory

cd truthlens-ai


# 2 (Recommended) Create virtual environment

python -m venv venv

source venv/bin/activate      # macOS / Linux
venv\Scripts\activate         # Windows


# 3 Install required dependencies

pip install -r requirements.txt



4. Run the Application

Start the AI dashboard using Streamlit.

streamlit run webapp/app.py


The application will automatically open in your browser.



5. Demo Workflow

Run the following workflow for a full demonstration.

Step 1 — Launch the platform

streamlit run webapp/app.py


Step 2 — Enter the platform dashboard


Step 3 — Upload a suspicious image


Step 4 — View AI analysis results

Expected Outputs

• Authenticity score
• Prediction result (Real / Fake)
• AI forensic heatmap


Step 5 — Analyze misinformation spread

Interactive global map visualization


Step 6 — Fact-check a news claim

AI credibility estimation


Step 7 — Check credibility of a news source



6. Project Structure

truthlens-ai/
│
├── model
│   └── deepfake_detector.py      ← Deepfake detection model
│
├── webapp
│   └── app.py                    ← Streamlit dashboard application
│
├── assets
│   └── images / UI resources
│
├── outputs                       ← Generated visual outputs
│
├── requirements.txt
└── README.md



7. Tech Stack

Component                Technology
------------------------------------------------
Frontend Dashboard       Streamlit
Programming Language     Python
Computer Vision          OpenCV
Machine Learning         TensorFlow / NumPy
Data Processing          Pandas
Visualization            Plotly
Image Handling           Pillow



8. AI Design Principles

TruthLens AI follows responsible AI development principles.

Transparency  
Clear authenticity scoring and visual explanations.

Explainability  
Heatmaps highlight suspicious image regions.

Reliability  
Models analyze image patterns for deepfake artifacts.

Accountability  
Users can report suspicious content.

Ethical AI  
Focus on misinformation detection and
