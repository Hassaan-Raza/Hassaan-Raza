<div align="center">

# Hey, I'm Hassaan 👋

### AI/ML Engineer · Building LLMs, Agents & Real-world AI Systems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hassaan_Raza-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hassaan-raza-00124031a)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-HassaanRaza--445-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/HassaanRaza-445)

</div>

---

Final year Software Engineering student based in Lahore, Pakistan. I build AI things and ship them.

Most of what I know came from just starting and figuring it out along the way. Currently focused on LLMs, agentic systems, and anything that involves making models actually do something useful in the real world.

---

## What I work with

```
LLMs & GenAI    →  PyTorch · HuggingFace · LangChain · LangGraph · CrewAI · Agno
Frameworks      →  Streamlit · FastAPI · Gradio
Cloud & Deploy  →  Google Cloud Run · Docker · HuggingFace Spaces
Vision          →  OpenCV · TensorFlow · EfficientNet · ResNet · InceptionV3
APIs & Models   →  Gemini · Veo · OpenAI · Groq · MCP Servers
Languages       →  Python · SQL
```

---

## Things I've built

### 🧠 NanoCodeGPT
GPT-style transformer built entirely from scratch in PyTorch. No pretrained weights, no APIs. Every layer written manually — attention heads, positional embeddings, transformer blocks, the training loop. Trained on 8,000 Python functions on a free Colab T4 GPU. Train loss dropped from 10.9 → 0.13 in under an hour.

[![Demo](https://img.shields.io/badge/Live_Demo-streamlit-FF4B4B?style=flat-square&logo=streamlit)](https://nanocodegpt.streamlit.app)
[![HuggingFace](https://img.shields.io/badge/Model-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/HassaanRaza-445/NanoCodeGPT)

---

### ⚖️ VerdictAI
RAG powered legal document intelligence system. Upload any contract, NDA, lease, or agreement and get instant clause-referenced answers in plain English. Red flag detection with HIGH, MEDIUM, and LOW severity ratings. Obligation and rights extraction, deadline mapping, party analysis, and an overall risk score with a full category breakdown. Built on a custom RAG pipeline — documents chunked and embedded with HuggingFace sentence transformers, indexed in ChromaDB, retrieved via vector similarity search, and passed to Gemma 4 31B via Ollama Cloud with a legal domain system prompt. Every answer cites the actual clause it came from.

[![Demo](https://img.shields.io/badge/Live_Demo-streamlit-FF4B4B?style=flat-square&logo=streamlit)](https://verdictai-9zjwujsqyk2gsccfdpf9an.streamlit.app)

---

### 💼 Jobee — AI Job & Internship Radar
Built to solve a real problem: job boards are built for San Francisco, not Lahore. Jobee reads your CV, figures out who you are as a candidate, then hits 7 job boards at once and ranks everything by how well it actually fits you. Not just by keyword — by your real skills, your location, your role type. Jobs in your city come first. Worldwide remote comes next. Country-restricted listings sink to the bottom automatically. Built with semantic similarity scoring using sentence-transformers and a 6-tier geo-proximity ranking system.

[![Demo](https://img.shields.io/badge/Live_Demo-streamlit-FF4B4B?style=flat-square&logo=streamlit)](https://jobeee.streamlit.app)

---

### 🔬 MediScan
Multimodal AI clinical diagnostic suite. Upload any X-ray, MRI, CT scan, or medical report. Gemini Vision returns a structured diagnosis with severity, confidence, and key findings. Nano Banana 2 generates an annotated anatomical body map. Veo 3.1 produces personalised rehabilitation exercise videos. Three modalities, one pipeline.

[![Demo](https://img.shields.io/badge/Live_Demo-streamlit-FF4B4B?style=flat-square&logo=streamlit)](https://mediscan-ettdj7rsjvqmolqcoz8sh9.streamlit.app)

---

### 🗺️ WayFairy — Agentic AI Travel Planner
Multi-agent AI travel itinerary generator built with CrewAI and Streamlit. Four specialized agents run sequentially — a logistics researcher finds real hotels and checks visa requirements; a local guide finds interest-matched activities and restaurants; a packing specialist generates a weather-aware list using live data from wttr.in; a master planner synthesizes everything into a day-by-day itinerary with a full budget breakdown. Every recommendation comes from live web search, not memorized training data.

[![Demo](https://img.shields.io/badge/Live_Demo-streamlit-FF4B4B?style=flat-square&logo=streamlit)](https://agenticaitravelplannerapp-ilzec6imxgjkequvn9bdkp.streamlit.app)

---

### 🏢 ERP Chatbot & Sales Assistant
Built professionally for **Eccountant**, a real company. Multi-company ERP AI assistant connecting directly to Eccountant's MySQL database on AWS RDS. Three specialized agents handle sales queries, inventory risk assessment, and cash flow analysis across their live data. Intent routing, schema discovery, write-protected DB access, CSV export, and a demo mode built in. A separate CEO-facing sales assistant handles natural language queries across revenue, customers, and products with persistent chat history. Powered by Llama 3.1 8B via OpenRouter.

---

### 🌍 MoonPulse
Real-time global intelligence dashboard pulling live weather, air quality, earthquake alerts, currency rates, and global news. Gemini generates smart city briefings and travel safety scores from real-time data. Deployed on Google Cloud Run.

[![Demo](https://img.shields.io/badge/Live_Demo-Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white)](https://moonpulse-636010656116.us-east4.run.app)

---

### 🐍 Pythonaut — AI Python Tutor
Multi-agent AI tutoring system built with CrewAI and Streamlit. Six specialized agents handle teaching, code review, curriculum planning, quiz generation, query routing, and conversation. Each agent has a distinct role and DuckDuckGo web search for fetching up-to-date resources.

[![Demo](https://img.shields.io/badge/Live_Demo-streamlit-FF4B4B?style=flat-square&logo=streamlit)](https://pythonautpythonteacher-avrff3ruyvpnqueadyn6it.streamlit.app)

---

### 🧑‍💻 C++ Tutor
Direct fork of Pythonaut retargeted for C++. Same six-agent CrewAI architecture with C++ specific resources, Core Guidelines instead of PEP 8, and coverage of memory management and pointer usage.

[![Demo](https://img.shields.io/badge/Live_Demo-streamlit-FF4B4B?style=flat-square&logo=streamlit)](https://cplusplusteacher.streamlit.app)

---

### 📈 IPL Win Probability Predictor
Machine learning model that predicts IPL match win probability in real time. Built with Python and deployed as a web app.

[![Demo](https://img.shields.io/badge/Live_Demo-streamlit-FF4B4B?style=flat-square&logo=streamlit)](https://ipl-win-probability-predictor-pythonapp.streamlit.app)

---

### 🏠 Bangalore House Price Predictor
End-to-end ML project predicting Bangalore property prices. Includes data cleaning, feature engineering, model training, and a web app for live predictions.

[![Demo](https://img.shields.io/badge/Live_Demo-streamlit-FF4B4B?style=flat-square&logo=streamlit)](https://bangalore-house-prediction-4xumqunuiqv8eglkkh7rvv.streamlit.app)

---

### 📦 Inventory Risk Predictor
ML model that assesses inventory risk levels for businesses. Flags low-stock and out-of-stock situations and generates risk alerts.

[![Demo](https://img.shields.io/badge/Live_Demo-streamlit-FF4B4B?style=flat-square&logo=streamlit)](https://inventoryriskpredictor.streamlit.app)

---

### 🥔 Potato Disease Classifier
CNN-based image classifier that diagnoses potato plant diseases from leaf photos — Early Blight, Late Blight, or Healthy. TensorFlow model trained at 256×256, served via Streamlit with confidence scores.

[![Demo](https://img.shields.io/badge/Live_Demo-streamlit-FF4B4B?style=flat-square&logo=streamlit)](https://potatodisease-kkz4ybyejdw2uitrszqjeq.streamlit.app)

---

### 🔓 UMT CAPTCHA Auto-filler
Browser extension (Chrome/Firefox) that automatically reads and fills CAPTCHA fields on UMT's student portal. Includes retry logic, MutationObserver for dynamic CAPTCHAs, and DOM event simulation.

---

## GitHub Stats

<div align="center">

![Hassaan's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Hassaan-Raza&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=00C9A7&icon_color=00C9A7&text_color=C9D1D9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Hassaan-Raza&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=00C9A7&text_color=C9D1D9)

</div>

---

<div align="center">

*Building things that work. Shipping things that matter.*

</div>
