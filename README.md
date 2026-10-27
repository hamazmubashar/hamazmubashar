# Hi, I'm Hamaz 👋

I'm a data scientist and AI engineer from Lahore. I build things end to end, from messy raw data to an app someone can actually click through, and I care most about the decision a model supports, not just its score.

Before data science I worked in healthcare revenue-cycle operations, handling claims, accounts receivable and weekly reporting. That's where I learned that data is only useful when it changes what someone does next.

I'm open to **remote roles in data science, data analytics and AI/LLM engineering**. → [LinkedIn](https://www.linkedin.com/in/hamazmubashar)

---

### Projects

**AI engineering: LLMs, retrieval and automation**

| Project | What it does | Built with | Try it |
|---|---|---|---|
| [**FlowPilot AI**](https://github.com/hamazmubashar/flowpilot-ai) | Lead-intake automation where n8n and a local LLM do the busywork (scoring, qualifying, drafting replies) and a named person approves every message. Nothing is ever sent automatically. | n8n · FastAPI · Ollama · Docker | [Live demo](https://flowpilot-hamaz.duckdns.org) |
| [**Knowledge Assistant**](https://github.com/hamazmubashar/knowledge-assistant) | Q&A over company PDFs. Every answer sentence is checked against the page it cites, and people only see documents their role allows. Built for a client against agreed targets. | FastAPI · pgvector · Ollama · Docker | [Live demo](https://knowledge-assistant-demo.streamlit.app) |
| **LeadFlow AI** | A lead-management system for small sales teams: import, score and track leads, with AI-drafted outreach that waits for human approval. | FastAPI · SQLite · Ollama · Docker | [Live demo](https://leadflow-hamaz.duckdns.org) · code on request |

**Data science and machine learning**

| Project | What it does | Built with | Try it |
|---|---|---|---|
| [**RetailPulse 360**](https://github.com/hamazmubashar/RetailPulse360) | Decision support for a 190-store shoe chain: demand forecasting, stock transfers between stores, discount strategy, and the rupee value of each decision. | LightGBM · pandas · Streamlit | [Live app](https://retailpulse360.streamlit.app) |
| [**FraudDetection360**](https://github.com/hamazmubashar/FraudDetection360) | Fraud scoring on 590K real transactions, with the block/allow cutoff chosen by what each mistake costs. Catches 71% of fraud at the lowest total cost. | LightGBM · MySQL · Power BI · Streamlit | [Live app](https://frauddetection360.streamlit.app) |
| [**StreamIntel 360**](https://github.com/hamazmubashar/streamintel360) | Eight models for a streaming platform (churn, forecasting, recommendations, poster genres, sentiment, LLM briefings, Q&A, explainability) behind one API. | TensorFlow · scikit-learn · FastAPI · Streamlit | [Live app](https://streamintel360-h5l8i2mdn5sfphbwsvcsyg.streamlit.app/) |
| [**Telco Churn Prediction**](https://github.com/hamazmubashar/telco-customer-churn-prediction) | What drives telecom churn, seven models compared, and retention ideas to act on. The simplest model won. | scikit-learn · XGBoost · Keras | — |

Currently building **VisionOps AI**, visual quality inspection for a manufacturing line.

---

### How I work

- **Start from the business decision.** In fraud detection, I set the cutoff from the cost of each kind of mistake, not a default 0.5.
- **Say what doesn't work.** Every README has a limitations section, and I report held-out results even when they're worse.
- **Keep people in charge of AI.** In my automation projects the model drafts and a person decides.
- **Ship it.** Almost every project ends in something you can open in a browser.

### Tools I use

**Data and ML:** Python, SQL (MySQL, PostgreSQL), pandas, NumPy, scikit-learn, LightGBM, XGBoost, TensorFlow / Keras
**LLMs and automation:** RAG, pgvector, Ollama, Gemini, n8n, FastAPI
**Shipping:** Docker, Streamlit, Plotly, Power BI, pytest, Git, Oracle Cloud
