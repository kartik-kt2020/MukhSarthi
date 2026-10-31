# MukhSarthi

### AI-Assisted Oral Health Screening for Rural Communities

**Making oral health screening more accessible, understandable, and inclusive.**

MukhSarthi is an AI-assisted oral health screening platform designed to support the early identification of suspicious oral lesions, particularly in underserved and rural communities.

The platform aims to empower individuals, ASHA workers, and healthcare facilitators with accessible screening tools, multilingual support, and actionable guidance to encourage timely medical evaluation.

> **Important:** MukhSarthi is a screening-support project, not a diagnostic tool. AI-generated results cannot confirm or rule out oral cancer. A qualified healthcare professional must evaluate suspicious findings.

---

## The Problem

Oral cancer can become life-threatening when detected at an advanced stage. However, many people in rural communities face barriers to timely screening and medical consultation, including:

* Limited access to healthcare facilities and screening services.
* Low awareness of early warning signs.
* Language and communication barriers.
* Delays in seeking medical attention.
* Difficulties accessing reliable health information.

These challenges highlight the need for accessible, community-oriented oral health screening support.

## Our Solution

MukhSarthi aims to bridge the gap between communities and healthcare services through an accessible web and mobile-friendly platform.

By combining AI-assisted image analysis, multilingual health education, and screening guidance, the platform aims to help users recognize potentially concerning oral health findings and take appropriate next steps.

## Key Features

* **AI-Assisted Oral Image Screening:** Analyze oral images for suspicious visual patterns, subject to model availability and validation.
* **Accessible User Experience:** Simple interface designed for people with varying levels of digital literacy.
* **Multilingual Support:** Designed to support Hindi, English, Tamil, Telugu, and Bengali.
* **ASHA Worker Support:** A community-oriented workflow to assist ASHA workers with awareness, screening assistance, and follow-up guidance.
* **Health Awareness:** Educational information about oral health, warning signs, and risk factors.
* **Screening Guidance:** Clear next-step recommendations for seeking professional medical evaluation.
* **Privacy-Conscious Design:** Aim to minimize personal data collection and protect sensitive health information.
* **Responsive Interface:** Designed for accessibility across smartphones, tablets, and desktops.

## How It Works

1. **Open the Platform:** The user or an authorized healthcare facilitator accesses MukhSarthi.
2. **Understand the Process:** The platform explains the screening workflow, consent, and limitations.
3. **Capture or Upload an Image:** An oral image may be submitted with appropriate consent and image-quality checks.
4. **AI-Assisted Analysis:** The image is processed by the screening model, if available.
5. **Review the Output:** The platform presents the screening output with appropriate uncertainty and limitations.
6. **Take the Next Step:** Users receive guidance on seeking professional evaluation when needed.

**A negative or low-risk model output must never be treated as proof that cancer is absent.** Persistent ulcers, unusual patches, lumps, bleeding, or other concerning symptoms warrant professional evaluation.

## AI & Machine Learning

MukhSarthi is intended to incorporate computer vision and machine learning for oral image analysis.

The planned AI pipeline may include:

* Dataset collection from ethically sourced and appropriately licensed data.
* Image quality assessment and preprocessing.
* Image classification or lesion detection.
* Model training and validation.
* Performance evaluation on independent datasets.
* Integration of model inference into the application backend.

Model development should prioritize clinically meaningful sensitivity, specificity, calibration, robustness, and evaluation across different lighting conditions, skin tones, image qualities, and populations.

The project must not claim diagnostic accuracy or clinical effectiveness without supporting validation evidence.

## Technology Stack

The final technology stack may evolve during development.

Potential components include:

* **Frontend:** React, Vite, TypeScript
* **Styling:** Tailwind CSS
* **Backend:** Python, FastAPI
* **AI/ML:** PyTorch, TensorFlow, or compatible computer vision frameworks
* **Database:** MongoDB or another suitable database
* **Deployment:** A suitable frontend and backend hosting platform
* **Version Control:** Git and GitHub

Update this section to reflect the technologies actually implemented.

## Getting Started

### Prerequisites

Install the following tools:

* Node.js and npm
* Python 3.10+ (depending on project dependencies)
* Git

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
cd YOUR_PROJECT_FOLDER
```

### 2. Frontend Setup

Navigate to the frontend directory:

```bash
cd frontend
npm install
npm run dev
```

Open the local development URL shown in your terminal.

### 3. Backend Setup

Open another terminal and navigate to the backend directory:

```bash
cd backend
```

Create a virtual environment:

**Windows:**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux/macOS:**

```bash
python3 -m venv venv
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start the backend, assuming the application entry point is `main.py` and the FastAPI instance is named `app`:

```bash
uvicorn main:app --reload
```

The exact setup commands may vary depending on the final project structure.

##  Project Structure

An example structure:

```text
MukhSarthi/
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.ts
│
├── backend/
│   ├── main.py
│   ├── requirements.txt
│   ├── models/
│   ├── routes/
│   └── services/
│
├── ml/
│   ├── training/
│   ├── evaluation/
│   └── inference/
│
├── docs/
│
├── .gitignore
├── README.md
└── LICENSE
```

*This is a suggested structure, not a representation of the current repository.*

##  Privacy & Responsible AI

Health information and oral images can be sensitive.

MukhSarthi aims to follow these principles:

* Obtain informed consent before image collection or processing.
* Collect only necessary information.
* Avoid exposing personal or health information in public repositories.
* Secure sensitive data in transit and at rest.
* Apply appropriate access controls and retention policies.
* Avoid using identifiable patient images for training without appropriate permissions.
* Communicate the limitations of AI-generated screening results.
* Encourage professional medical evaluation rather than self-diagnosis.

##  Our Mission

Our mission is to make oral health awareness and screening support more accessible to underserved communities.

We envision a future where technology helps community healthcare workers, individuals, and healthcare providers work together to encourage earlier evaluation and better access to care.

## Roadmap

* [ ] Develop the frontend and responsive interface.
* [ ] Implement backend APIs.
* [ ] Integrate multilingual support.
* [ ] Develop the image upload and capture workflow.
* [ ] Establish an ethically sourced dataset.
* [ ] Train and evaluate an AI screening model.
* [ ] Integrate model inference.
* [ ] Implement secure data handling.
* [ ] Add ASHA worker-oriented workflows.
* [ ] Conduct usability and accessibility testing.
* [ ] Plan clinical validation and expert review.
* [ ] Evaluate deployment readiness.

## Team

Built by our team of four as part of a 24-hour hackathon.

* [Kartik Kumar]
* [Atharva kumar]
* [Pranjal srivastav]
* [Rishi malhan]

## Disclaimer

MukhSarthi is a healthcare technology project intended to support awareness and screening workflows.

It is not a substitute for professional medical advice, diagnosis, or treatment.

The AI system, if implemented, may produce false-positive and false-negative results. No screening outcome should be used independently to make clinical decisions.

Clinical use would require appropriate validation, clinical oversight, privacy safeguards, and compliance with applicable regulations.

**MukhSarthi — Supporting healthier communities through accessible technology.**
