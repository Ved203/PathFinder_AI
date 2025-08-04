#  🔍 Agentic AI for Personalized Course Pathways - PathfinderAI

PathfinderAI is an intelligent AI-powered assistant that helps learners build personalized learning paths aligned with their career goals, interests, and current skill levels. Built on IBM Watsonx.ai and powered by Retrieval-Augmented Generation (RAG), it dynamically adapts recommendations as users progress—acting like a smart, evolving personal mentor.


![AI Overview](ai.png)
---

## 🧩 Problem Statement

In the digital education era, students are overwhelmed by thousands of available online courses and platforms. Many struggle to decide:
- Where to begin?
- Which course matches their career goals?
- How to avoid irrelevant or poorly sequenced learning?

Without personalized guidance, learners often feel lost and unmotivated, leading to wasted time and ineffective outcomes.

---

## 💡 Proposed Solution

**PathfinderAI** solves this problem by acting as an Agentic AI Coach:
- It interacts with students to understand their goals (e.g., becoming a frontend developer, AI engineer, UX designer).
- It assesses current knowledge and skill levels.
- It builds a personalized learning roadmap using trusted course material.
- It adapts the roadmap over time based on learner feedback, engagement, and goal updates.
- It only responds to learning-related queries and politely filters unrelated content.

---

## 🧠 Technologies Used

- IBM Watsonx.ai Studio  
- IBM Granite Foundation Model (LLM)  
- Retrieval-Augmented Generation (RAG)  
- IBM Cloud Object Storage  
- Vector Index for document-based search  
- NLP for user query understanding  

---

## ☁️ IBM Cloud Services Used

- Watsonx.ai Studio  
- IBM Granite Model  
- Watsonx Vector Index  
- IBM Cloud Lite Account  
- IBM IAM (Identity and Access Management)  
- IBM Cloud Object Storage  

---

## 👥 End Users

- High school and college students  
- Early-career professionals  
- Career switchers in tech and design  
- Learning platforms and MOOC users  
- Academic mentors and advisors  

---

## 🌟 WOW Factors

- Uses RAG to deliver document-grounded, skill-based course recommendations  
- Adapts course paths in real-time as learners grow and shift focus  
- Filters unrelated or off-topic queries with polite responses  
- Multilingual and voice-based features (planned)  
- Recommends high-quality courses from sources like Coursera, edX, IBM SkillsBuild  
- Acts like a mentor, not just a chatbot  

---

## 🧪 Key Features

- Personalized and evolving course roadmap  
- Smart skill-gap analysis before recommendations  
- Pulls from real educational content (PDFs, APIs, trusted platforms)  
- Filters queries outside the learning domain  
- Roadmap improves via ongoing user feedback and metrics  

---

## 🚀 How It Works

1. Learner inputs their interest (e.g., "I want to be a cybersecurity analyst")  
2. Granite LLM understands the intent and context  
3. Vector Index retrieves relevant course content from uploaded PDFs or sources  
4. Agent generates structured learning path with goals and stages  
5. Learner feedback is incorporated for continuous roadmap refinement  

---

## 📌 How to Deploy on IBM Cloud

1. Sign in to [IBM Cloud Lite](https://cloud.ibm.com)  
2. Open Watsonx.ai Studio  
3. Create a new AI agent project  
4. Upload curated learning content (PDFs, notes, syllabus, etc.)  
5. Create and configure a Vector Index  
6. Restrict topic scope to learning/career guidance only  
7. Test using the preview panel  
8. Deploy using web snippet, Streamlit app, or integration in a mobile/web frontend  

---

## 🖼️ Screenshots

- 🔹 Personalized Chat Interface  
- 🔹 Course Roadmap Output  
- 🔹 Agent Settings and Configuration  
- 🔹 Off-topic Query Handling  
- 🔹 Deployment Flow in Watsonx  

> _You can embed screenshots like:_  
> `![Roadmap Output](./images/roadmap_output.png)`

---

## 🛣️ Future Scope

- WhatsApp and mobile app chatbot integration  
- Speech-to-text for voice-based input  
- Monthly learning progress reports  
- Peer group and mentor matchmaking  
- Multilingual expansion via Watson Language Translator  
- Real-time progress visualization dashboard  

---

## 🔗 Useful Links

- [IBM Watsonx.ai Studio](https://www.ibm.com/products/watsonx-ai)  
- [IBM Cloud Lite](https://cloud.ibm.com/registration)  
- [IBM SkillsBuild](https://skillsbuild.org)  
- [Coursera](https://www.coursera.org)  
- [edX](https://www.edx.org)  

---

