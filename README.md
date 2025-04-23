# 📄 Resume Parser: Empowering Job Seekers to Build Stronger Resumes

## 🚀 Elevator Pitch

Many job seekers face resume rejections due to poor formatting, missing key details, or not aligning their resumes with industry standards. Without clear insights into what makes a resume effective, candidates struggle to present their skills and experiences in a way that resonates with recruiters and applicant tracking systems (ATS). 

This project aims to build a web-based Resume Parser that analyzes resumes and provides structured feedback to job seekers. Using Natural Language Processing (NLP) and Machine Learning, our tool extracts key resume sections (skills, experience, education) and offers suggestions to enhance ATS compatibility, improve clarity, and meet recruiter expectations.

By helping users craft ATS-friendly, recruiter-approved resumes, we aim to increase interview success rates and reduce rejection due to formatting and content issues.

---

## 🛠 Installation Instructions

To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Tirth401/cs5661-dsproject-Resume-Parser.git
   cd cs5661-dsproject-Resume-Parser
   ```
2. **Create and activate a virtual environment::**
   ```bash
   python -m venv venv
   venv\Scripts\activate  # On Windows
   # source venv/bin/activate  # On macOS/Linux
   ```
3. **Install the required dependencies:::**
   ```bash
    pip install -r requirements.txt
   ```
## Project Structure

```text
.
├── data/                  # Dataset storage and documentation
│   ┗── data_card.md       # Metadata and dataset documentation
├── notebooks/             # Analysis and modeling experiments
├── src/                   # Production-ready codebase
├── static/                # Frontend assets (CSS, JS, images)
├── templates/             # Web UI components
├── requirements.txt       # Python dependencies
├── app.py                 # Main application entrypoint
├── README.md              # Project overview and setup instructions
└── .gitignore             # Version control configuration
```
## 👥 Team Members & Roles

| **Name**         | **Role**                                      |
|-------------------|-----------------------------------------------|
| Yash Shah        | Backend Development, Resume Parsing Logic     |
| Jenil Shah       | Project Coordination, Sentiment Analysis & Reporting |
| Vrajesh Shah     | Web Application Development                   |
| Tirth Shah       | Data Collection and Preprocessing             |
| Bhaven Chheda    | Frontend & UI Design                          |
| Kritagya Kumra   | Evaluation, Testing & Deployment              |
| Vatsal Bhimani   | NLP Modeling & Resume Feedback System         |

## 📦 What This Repo Contains

- **Scripts** for resume extraction and preprocessing
- **NLP modules** handling parsing and feature extraction
- **Resume evaluation** tools for scoring and ATS-friendliness
- **Jupyter notebooks** documenting data exploration and modeling
- **Web interface** supporting resume uploads and feedback
- **Data Card** detailing dataset source, structure, and limitations

## 📚 Dataset & Documentation

The dataset includes real-world resumes in **PDF, DOCX, and TXT formats**. Full transparency about the data is provided in `data_card.md`, covering:

- Data source
- Feature details
- Preprocessing steps
- Known limitations
- Ethical considerations

For more on Data Cards: [Google Data Cards Playbook](https://developers.google.com/machine-learning/data-card)
