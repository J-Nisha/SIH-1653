# Smart India Hackathon Workshop
# Date:10/03/2025
## Register Number:212223040133
## Name:Nisha.J
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
```
1. Smart Question Generator
 Use AI-driven algorithms to generate tailored questions based on a candidate’s resume, job role, and expertise. The system ensures dynamic and adaptive questioning to assess in-depth knowledge.

2. AI-Powered Response Evaluation
 Implement NLP (Natural Language Processing) to analyze candidate responses, grading them on relevance, depth, clarity, and technical accuracy.

3. Virtual Interview Coach
 Develop a virtual assistant that offers real-time feedback to candidates on their responses, communication skills, and body language using AI-driven sentiment analysis.

4. Expert Question Quality Analyzer
 AI assesses the quality and relevance of questions asked by interviewers to ensure unbiased and effective evaluation. It provides insights on improvement areas for interview panels.

5. Interactive Interview Simulation
 Create an AI-powered boardroom simulation where candidates undergo a mock interview with virtual AI-driven experts before appearing for the real interview.
6. Bias Detection System
 Implement AI-driven bias detection that ensures fairness in hiring by flagging potentially biased questions or responses that could impact decision-making.
7.  AI-Powered Interview Summary Report
 Automatically generate a structured report post-interview, summarizing candidate performance, strengths, weaknesses, and final suitability score.
```

## Proposed Solution / Architecture Diagram
![Screenshot 2025-03-10 034941](https://github.com/user-attachments/assets/ae059965-40a3-4140-aadb-c910c8b554ec)





## Use Cases
```
Use Case 1: AI-Assisted Candidate Evaluation
Actors: Candidate, Expert Panel, AI System
Flow:
Candidate submits details.
AI suggests structured questions.
Candidate answers in real-time (text/audio).
AI scores responses for accuracy and relevance.
Final score determines candidate suitability.
Use Case 2: Expert Performance Assessment
Actors: Expert Panel, AI System
Flow:
AI assesses expert questions for relevance.
System provides feedback on alignment with the candidate’s field.
Experts receive a relevancy score, helping in refining future assessments.
Use Case 3: Automated Interview Report Generation
Actors: Interview Panel, HR, AI System
Flow:
AI generates a post-interview summary.
Detailed scoring with candidate strengths/weaknesses is provided.
Report assists in final selection and promotions.

```



## Technology Stack
```
Frontend:	React.js / Angular / Vue.js for an interactive interview interface
Backend	:Python (FastAPI/Django) / Node.js for API handling
AI/NLP Processing:	OpenAI GPT, BERT, LLMs for question generation & response evaluation
Speech Processing:	Google Speech-to-Text / Whisper (for voice interviews)
Database:	PostgreSQL / MongoDB for storing questions, responses, and scores
Authentication:	OAuth 2.0 / JWT for secure login
Cloud Deployment:	AWS / Azure / GCP for scalable hosting
```


## Dependencies
```
NLP Models: Pre-trained AI models for evaluating responses.
Expert Input: Continuous feedback from subject-matter experts for AI training.
Data Security & Compliance: Secure storage of candidate data per government regulations.
Infrastructure Support: Cloud-based or on-premise infrastructure for high availability.
```

