# 📄 Data Card: Resume Parsing Dataset

## 📌 Dataset Name (Acronym)
**Resume Parsing Dataset**

A dataset composed of extracted resume information aimed at supporting the development of an NLP-based resume parser. This data includes structured and semi-structured fields derived from real-world resumes such as skills, education, job history, and extracurricular activities. The motivation behind this dataset is to facilitate automated feedback systems that help job seekers craft better resumes and improve their chances in applicant tracking systems (ATS).

---

## 🔗 Dataset Link
To be added after upload  
Example: [GitHub Repo](https://github.com/Tirth401/cs5661-dsproject-Resume-Parser)

---

## 👥 Data Card Author(s)
- Yash Shah — Contributor
- Jenil Shah — Contributor
- Vrajesh Shah — Contributor
- Tirth Shah — Contributor
- Bhaven Chheda — Contributor
- Kritagya Kumra — Contributor
- Vatsal Bhimani — Contributor

---

## 🏢 Authorship

### Publishers
- California State University, Los Angeles

### Industry Type(s)
- Academic - Tech

---

## 📞 Contact Detail(s)

**Publishing POC**: Jenil Shah  
**Affiliation**: California State University, Los Angeles  
**Contact**: jenil@example.edu  
**Mailing List**: resumeparser-team@university.edu  
**Website**: [Resume Parser Project](https://github.com/Tirth401/cs5661-dsproject-Resume-Parser)

---

## 🌍 Dataset Overview

### Data Subject(s)
- Non-Sensitive Data about people (resume content like education, experience, skills)

---

## 📸 Dataset Snapshot

| Category                | Value       |
|------------------------|-------------|
| Size of Dataset         | ~9,544 records |
| Number of Instances     | 9,544        |
| Number of Fields        | 35           |
| Labeled Classes         | N/A (structured fields) |
| Number of Labels        | N/A          |
| Avg. Labels Per Record  | N/A          |
| Human Labels            | Yes          |
| Algorithmic Labels      | No           |

_Above: Snapshot of extracted structured resume content from multiple formats._

---

## 📄 Content Description

The dataset consists of structured information extracted from resumes. Key fields include:
- Skills
- Educational background
- Job history (companies, positions, durations)
- Career objectives
- Extracurriculars
- Locations and responsibilities

Fields like `responsibilities`, `career_objective`, and `skills` are suitable for text analysis and NLP tasks such as classification, clustering, or sentiment analysis.

---

## 📊 Descriptive Statistics (Example - Resume Text Field)

| Statistic | Responsibilities |
|-----------|------------------|
| count     | 9544             |
| mean      | —                |
| std       | —                |
| min       | —                |
| 25%       | 0.583            |
| 50%       | 0.683            |
| 75%       | 0.793            |
| max       | 0.970            |

_Above: Example statistics for semantic or ATS-compatibility scoring (normalized range)._

---

## 🔒 Sensitivity of Data

### Sensitivity Type(s)
- **User Content**: Yes (resume information)
- **User Metadata**: No direct identifiers retained (anonymized)

---

## 📝 Additional Notes

- The dataset has missing values in some fields (e.g., extracurriculars, career objectives) which may affect completeness.
- Source resumes were anonymized before processing to ensure privacy.
- Suitable for educational use, modeling, or proof-of-concept resume recommendation engines.

---
