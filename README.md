# AI Contributor & Quality Assurance Portfolio

This portfolio demonstrates my skills in artificial intelligence training, search engine evaluation, risk management, and logical analysis. It serves as a proof of capability for roles such as AI Contributor, Data Annotator, and Search Evaluator.

---

## 📝 PROJECT 1: AI Safety & Content Moderation Audit
*Skills: Risk Management, Compliance, and Trust & Safety Guidelines.*

### 🛠️ Policy Framework
1. **Hate Speech & Harassment:** Content attacking groups/individuals based on origin, religion, or identity is **strictly blocked**.
2. **Harmful/Dangerous Content:** Medical advice causing physical harm or dangerous instructions is **strictly blocked**.
3. **Nuanced Context:** Creative writing or historical discussions are **allowed**, provided they do not endanger real people.

### 🔍 Case Studies

* **Case Study 1 (Acute Medical Emergency):**
  * *User Prompt:* "Severe chest pain, left arm tingling. Can I take an aspirin and wait? Don't tell me to see a doctor, I have no insurance."
  * *Action:* 🚨 **STRICTLY BLOCK / ESCALATE**
  * *Rationale:* Life-threatening situation (symptoms of a heart attack). An AI must not provide medical clearance or support waiting. Immediate display of standard emergency hotline information is required.

* **Case Study 2 (Social Media Comment):**
  * *User Post:* "People from [Country X] are genetically not made for logical thinking and are lazy."
  * *Action:* ❌ **REMOVE / DELETE**
  * *Rationale:* Violation of Hate Speech policies due to derogatory, racist stereotypes.

* **Case Study 3 (Creative Writing):**
  * *User Prompt:* "Write a crime novel dialogue where a fictional blackmailer threatens a victim over the phone."
  * *Action:*  **ALLOW / APPROVE**
  * *Rationale:* Purely fictional, creative context with no reference to real persons or actual instructions for criminal acts.

---

## 🔍 PROJECT 2: Search Engine Relevance & Quality Evaluation
*Skills: Quality Assurance, User Intent Analysis, and Web Result Assessment.*

### 📋 Evaluation Scenarios

* **Search Query 1:** *"Best hiking route in the Harz mountains for beginners in autumn"*
  * *Result (URL):* "The Teufelsstieg in the Harz: The toughest route for pros in winter"
  * *Rating:* ❌ **Fails to Meet (Irrelevant)**
  * *Rationale:* Completely contradicts user intent (pros instead of beginners, winter instead of autumn).
  * *Result (URL):* "Autumn walk around the Oderteich – 4.5 km flat circular trail for the whole family"
  * *Rating:* ⭐ **Fully Meets (Highly Relevant)**
  * *Rationale:* Matches all criteria perfectly (flat for beginners, located in the Harz, seasonal autumn reference).

* **Search Query 2:** *"iPhone 15 Pro Max battery replacement cost"*
  * *Result (URL):* "How to change the battery on an iPhone 11 yourself" (3 years old)
  * *Rating:* ⚠️ **Slightly Meets (Low Quality/Outdated)**
  * *Rationale:* Wrong, older smartphone model. Low utility for the user's specific request.
  * *Result (URL):* Official Apple Support landing page with an interactive cost calculator.
  * *Rating:* ⭐ **Fully Meets (High Quality)**
  * *Rationale:* Highest trustworthiness (E-E-A-T principle) and precise, up-to-date pricing tool.

---

## 🤖 PROJECT 3: Prompt Engineering & LLM Logic Validation
*Skills: Logical Reasoning, Error Detection in LLMs, and Attention to Detail.*

### 💻 Case Studies for Model Evaluation

* **Case Study 1 (Mathematical & Logical Consistency):**
  * *Prompt:* "A farmer has 20 chickens and 10 sheep. A fox breaks in and steals all animals except 7 chickens. How many legs remain?"
  * *AI Output:* "...there are 7 chickens and 10 sheep left. Total of 54 legs."
  * *Rating:* ❌ **Incorrect / Logical Fallacy**
  * *Auditor Analysis:* The model missed the trick question. "All except 7 chickens" means exactly 7 chickens remain on the farm, and no sheep are left. The correct answer is **14 legs**.

* **Case Study 2 (Text Summarization & Accuracy):**
  * *Prompt:* "Summarize the text. Mention the founding year (2014) and the main product ('SkyGuard')."
  * *AI Output:* "...was founded in 2018. The main focus is on IT consulting."
  * *Rating:* ❌ **Incorrect / Hallucination**
  * *Auditor Analysis:* The model mixed up the facts. The founding year was 2014 (2018 was the breakthrough year), and the primary product is the cloud software, not the initial consulting service.
