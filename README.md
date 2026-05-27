# FinAssist-AI: Intelligent Loan Eligibility Assessment Assistant

**AI Loan Eligibility Assessment Assistant :-**
**Overview**

The AI Loan Eligibility Assessment Assistant is an enterprise-grade Generative AI application designed to automate and streamline the loan underwriting process for financial institutions.

The system combines:

Multi-Agent AI Architecture,
Retrieval Augmented Generation (RAG),
Human-in-the-Loop (HITL) Review,
Policy-Aware Decision Making,
Interactive Web-Based UI,

to simulate a real-world banking loan approval workflow.

**The project was developed as part of the UST Enterprise Capstone Program.**

----
**Problem Statement**

Traditional loan approval systems rely heavily on manual review processes which can lead to:

Slow loan approvals
Inconsistent decisions
Human bias
Difficulty in policy compliance tracking
Increased operational overhead

This project aims to solve these challenges using AI-driven automation while still maintaining human oversight for sensitive cases.

----

## 📁 Repository Structure

The repository is organized as follows:

* **`data/`**: Core assets used for evaluating the system.
    * `applicants.csv`: Mock applicant profiles containing financial metrics, credit scores, and requested loan details.
    * `policies/`: Institutional guidelines including `loan_policy.txt`, `risk_guidelines.txt`, and `manual_review_sop.txt`.
    * `sample_pdfs/`: Test document vectors representing `approved`, `rejected`, `invalid`, and `review-required` edge cases.
* **`notebooks/`**: Core development environments.
    * `loan_eligibility_assistant.ipynb`: Main production notebook featuring data chunking, prompt engineering, and LLM orchestration.
    * `FinAssist_AI_Capstone.ipynb`: Experimental and foundational workflow scaffolding.
* **`outputs/`**: PPT, along with the Verification documentation containing test cases and system performance evaluations.

---

## 🚀 Key Features

* **Policy-Driven RAG (Retrieval-Augmented Generation)**: Ingests unstructured policy documentation (SOPs, risk thresholds) and chunks the data using recursive text splitters to ground the LLM's decision-making process.
* **Automated Applicant Screening**: Reads structured data vectors (`.csv`) and matches applicant financial profiles against rigid institutional risk criteria.
* **Document Classification**: Evaluates multi-scenario applicant cases, mapping them cleanly to `Approved`, `Rejected`, or `Manual Review` states.
* **Secure Implementation Architecture**: Engineered using modern environment variables to separate API credentials (OpenRouter/LLM keys) from codebase commits.

---

## 🛠️ Tech Stack & Tools

* **Language:** Python 3.12+
* **Frameworks:** LangChain (LangChain Community Document Loaders,OpenAI / OpenRouter, Text Splitters), Chroma db.
* **Environment:** Google Colab / Jupyter Notebooks
* **Version Control:** Git & GitHub (Protected Security Implementations)

---

## ⚙️ Setup and Installation

To run the notebooks locally or within Google Colab:

1. Clone the repository:
   ```bash
   git clone [https://github.com/Mohsin-22/Capstone_Project_100_Gen-Ai_cohort.git](https://github.com/Mohsin-22/Capstone_Project_100_Gen-Ai_cohort.git)
