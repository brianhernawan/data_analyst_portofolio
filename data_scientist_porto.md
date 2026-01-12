# 🧠 Data Science Portfolio — Brianca Hernawan  
### *Role: Data Scientist at BBF Meat Shop (Retail & E‑Commerce)*  
*(2024 – 2026)*

---

## 🏪 About the Organization
**BBF Meat Shop (daging.id)** is an Indonesian omni‑channel retailer specializing in premium fresh meat
products for both retail and HORECA sectors.  
Operating a Shopify‑based e‑commerce ecosystem with regional fulfillment centers,
BBF combines physical retail and digital channels to provide high‑quality protein delivery services.

As a **Data Scientist**, I focused on transforming operational, marketing, and product
data into decision‑driven insights and intelligent systems supporting growth, efficiency, and automation.

---

## 💼 Key Projects & Achievements

### 1. Demand Forecasting & Cold‑Chain Optimization
**Problem:** Overstock and wastage of perishable SKUs due to volatile demand (Ramadan, Eid).  
**Approach:**
- Integrated 2M+ records from POS and Shopify API.
- Built **XGBoost** / **Prophet** forecasting models incorporating seasonal trends and weather data.
- Automated reports to Google Sheets via Tableau API.

**Impact:**  
- Reduced chilled product waste by **32 %**, increased inventory turnover from **5.1× → 7.6×**.  

**Tech:** Python, scikit‑learn, Prophet, Tableau, GCP, REST APIs

---

### 2. NLP‑Driven Review Analysis
**Goal:** Detect complaints and customer sentiment across marketplaces.  
**Method:**
- Built an **IndoBERT**‑based sentiment classifier with 7 000 labeled reviews.
- Automated keyword extraction for product QA teams.
- Deployed alert system via Slack for negative feedback spikes.

**Impact:**  
- Shortened complaint handling time by **40 %**; improved packaging satisfaction scores.

**Tech:** Python, HuggingFace Transformers, FastAPI, Tableau

---

### 3. Computer Vision for Product Consistency ->> A/B testing and Geo Spatial
**Objective:** Identify non‑uniform meat cuts from production line cameras.  
**Solution:**
- Trained lightweight **ViT + ResNet** model on labeled image dataset.
- Deployed inference API on on‑prem GPU node (Proxmox, RTX 3080).
- Telegram bot alerts for detected anomalies.

**Impact:**  
- Achieved **95 % F1‑score**; enabled real‑time quality assurance feedback loop.

**Tech:** PyTorch, OpenCV, ONNX Runtime, Flask

---

### 4. Marketing Analytics & Attribution
**Goal:** Quantify ROI of multi‑channel campaigns (Instagram, Email, Referral).  
**Approach:**
- Built **multi‑touch attribution model** using logistic regression + Shapley simulation.  
- Developed **Tableau dashboards** for ROI, CAC, LTV segments, conversion funnels.  
- Designed budget optimization model forecasting conversion efficiency.

**Impact:**  
- ROI ↑ 23 %, CAC ↓ 17 %, improved forecast accuracy for campaigns.

**Tech:** SQL (BigQuery), Python, Tableau, Airbyte

---

### 5. Content Automation with Generative AI
**Challenge:** Manual creation of product descriptions/captions slowed catalog updates.  
**Approach:**
- Used GPT‑based generation pipeline (Indonesian fine‑tune).  
- Integrated moderation filters (CLIP‑score + regex) before CMS publish.  

**Impact:**  
- Content creation time ↓ 80 %, SEO CTR ↑ 18 %.

**Tech:** Python, LangChain, OpenAI API, FastAPI, 
