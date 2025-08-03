# LearnMate: AI-Powered Personalized Learning Coach

![LearnMate Demo Screenshot](https://github.com/niyati666/LearnMate_Agent/blob/main/Images/Deployed_Agent.png)  
*LearnMate*

## 📌 Overview
LearnMate is an **Agentic AI** that acts as a personalized learning coach, helping students navigate the overwhelming landscape of online courses. It:
- Interviews students to assess **interests** (e.g., Frontend Development, Cybersecurity) and **skill levels**.
- Dynamically generates **adaptive learning roadmaps** using IBM Granite.
- Tracks progress and adjusts recommendations in real-time.

## 🎯 Problem Statement
Students waste **40% more time** on mismatched courses due to:
- Lack of personalized guidance.
- Static learning paths that ignore progress.
- Overwhelm from 1000s of course options.

## ✨ Key Features
| Feature | Description |
|---------|-------------|
| **Adaptive Pathways** | Course recommendations evolve based on quiz scores/time spent. |
| **Multimodal Learning** | Suggests videos, articles, or projects tailored to learning style. |
| **Career Alignment** | Recommends skills with high job-market demand (e.g., AI, Cloud). |
| **Progress Analytics** | Visual dashboards for students/mentors. |

## 🛠 Technology Stack
### Core Components
- **IBM Granite**: NLP for student interactions and dynamic roadmap generation.
- **IBM Watsonx.ai**: Fine-tuned learning pathway models.
- **IBM Cloudant (Lite)**: Stores student profiles and progress history.
- **IBM Cloud Lite**: Hosting and API endpoints.

### APIs Integrated
- Coursera/edX (course metadata)
- LinkedIn Learning (optional for career trends)

## 🚀 Installation
### Prerequisites
- IBM Cloud account (Lite tier)
- Python 3.10+

### Steps
1. Clone the repo:
   ```
   git clone https://github.com/[yourusername]/LearnMate.git
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt

4. Configure IBM Cloud credentials in config.ini:

```ini
[IBM]
API_KEY = your_ibm_cloud_api_key
WATSONX_PROJECT_ID = your_project_id
```
4. Run the demo:
```bash
python app.py
```

## 📊 Results
![LearnMate Demo Screenshot](https://github.com/niyati666/LearnMate_Agent/blob/main/Images/Result_1.png)
![LearnMate Demo Screenshot](https://github.com/niyati666/LearnMate_Agent/blob/main/Images/Result_2.png)
![LearnMate Demo Screenshot](https://github.com/niyati666/LearnMate_Agent/blob/main/Images/Mockup_personalised_Dashboard_1.png)
![LearnMate Demo Screenshot](https://github.com/niyati666/LearnMate_Agent/blob/main/Images/Mockup_personalised_Dashboard_2.png)

## 🌟 Future Work
- AI Tutor Integration: Real-time coding assistance.
- Scholarship Matching: Recommends funding opportunities.
- VR Labs: Hands-on practice for fields like cybersecurity.

## 📜 IBM Certifications
![IBMAIFundamentals](https://github.com/niyati666/LearnMate_Agent/blob/main/Images/Getting_Started_with_AI.png)
*Getting Started with AI*
![RAG Lab Completion Certificate](https://github.com/niyati666/LearnMate_Agent/blob/main/Images/RAG.png)

## 🤝 How to Contribute
1. Fork the repository.
2. Submit PRs for:
- Enhanced course recommendation algorithms.
- Additional LMS platform integrations.
3. Report bugs via Issues.

## ✨ Credits
Developed as part of Edunet IBM internship projects.
