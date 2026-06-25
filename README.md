# SULO

An AI that brings ordinary Filipinos out of the dark on the documents that decide their rights — without ever pretending to be a lawyer. Amazon Comprehend · Quantized LLM · OCR · ASR/TTS · Vite · React.

SULO is an AI-powered legal-literacy and document-understanding platform. A Filipino points their phone at a contract, a notice, or a loan agreement — by upload, photo, or voice — and SULO explains, in plain language and in their own tongue, what the document is, what it obligates them to do, what deadlines it carries, and which clauses deserve a second look. It does not give legal advice. It gives legal understanding, and it routes people to real help when they need it so that safety lives in comprehension, not in dense legal jargon.

## Demo & submission

Quick links for reviewers — everything the submission rubric asks for, in one place.

### Live demo

* **Deployed app:** `(input this here)` — try an image upload or a voice interaction.
* **Walkthrough video:** `(input this here)` — full feature tour showing legal text-to-speech routing.

### Mobile responsive

Captured on Android Chrome at 1080×2400 — hero layout, camera-capture flow, typography, and interactive risk highlights all reflow cleanly as a Progressive Web App (PWA) layout without horizontal scroll.

### CI/CD

Runs on every push to main and on every PR: `npm ci` → `npm run build` against the frontend. Workflow lives at `(input this here)`.

## Core Backend & Model Pipelines

* **Amazon Comprehend NLP Routing Service:** `(input this here)`
* **Quantized LLM Inference Host Location:** `(input this here)`
* **Vector Store Semantic Search Endpoint:** `(input this here)`
* **Sample Document Analysis / Processing Log ID:** `(input this here)`

## Deployed Infrastructure

The legal routing, text extraction, and parsing service is live.

* **Service/Model ID:** `(input this here)`
* **Type:** Quantized LLM Pipeline / Custom NLP Classifier / RAG Engine
* **Network/Host:** `(input this here)`
* **Explorer/Logs:** `(input this here)`

---

## Why SULO

The law protects Filipinos on paper. Labor laws, lending regulations, and consumer rights all exist—but the system is structurally inaccessible. Legally navigating daily life in the Philippines is broken, confusing, and stressful. 

SULO removes the stress. You upload any document or record an audio clip, and the AI handles the rest, breaking down liabilities on low-cost, fast rails. Anyone can verify what they are signing before it is too late.

### What you get

* **Quiet predictability** — once a document is scanned or voiced, the fine print is instantly demystified.
* **Privacy-native** — private documents are parsed securely; raw personal details never leak.
* **Verifiable** — every clause interpretation and risk rating is strictly mapped to actual Philippine law references (Labor Code, RA 11106, etc.) using a curated knowledge base as a single source of truth.

---

## Concept vocabulary

| Brand Word | Means |
| :--- | :--- |
| **SULO** | Filipino for *torch*—bringing clarity to hidden, dark legal clauses. |
| **Scan/Upload (OCR)** | Submitting an image of a document to be transformed into machine-readable text. |
| **Voice Query (ASR)** | Submitting audio or spoken code-switching language to ask questions about obligations. |
| **Plain Language (TTS)** | The spoken and written overview ("Ano ang ibig sabihin nito sa madaling salita?"). |
| **Red Flag** | A clause that is heavily skewed against the user or potentially illegal under current DOLE/Philippine regulations. |

---

## How it works

1. **Capture & Extract (OCR / ASR)** — Point a phone at a contract or speak directly into the app. SULO reads images or transcribes spoken Filipino/Taglish.
2. **Auto-Classification & Language Routing** — The system integrates Amazon Comprehend to detect the language profile and document type to pull up specific legal compliance frameworks.
3. **Semantic Grounding (RAG & Vector Store)** — The system queries a curated knowledge base of true legal provisions (Labor Code, current amendments) to prevent AI hallucinations.
4. **Local Comprehension Execution** — A compressed, Quantized LLM reads the context to highlight deadlines, monetary balances, and suspicious clauses.
5. **Clarity Flows (TTS)** — The user reads or listens to an interactive, side-by-side translation to safely understand their rights without entering legal advice boundaries.

---

## Project structure

The processing repository is organized into a modular pipeline; its core public parameters match standard text interpretation rules for seamless compatibility.

## Architecture

| Layer | Stack |
| :--- | :--- |
| **Frontend** | React, Vite, Tailwind, Progressive Web App (PWA) |
| **AI Engine** | Custom Amazon Comprehend NLP Pipeline, Quantized Mobile-Optimized LLM, RAG |
| **Data Engine** | Vector Store (Semantic Embeddings Retrieval Index) |
| **Perception** | OCR (Text Extraction) & ASR / TTS (Speech Components) |

---

## Environment variables (frontend)

Copy `frontend/.env.example` to `frontend/.env` and set:

* `VITE_COMPREHEND_API_URL` — Backend processing pipeline URL.
* `VITE_LOCAL_LLM_GATEWAY_URL` — Quantized LLM endpoint interface for real-time contract Q&A.
* `VITE_VECTOR_STORE_URL` — RAG knowledge base search interface.
* `VITE_APP_ENV` — Development or production indicator.
* `(input any extra environment variables here)`

The example variables in `.env.example` are for development purposes only.

## Local development

1. **Shared Knowledge Base API:** `(input this here)`
2. **Frontend Setup:** `(input commands like npm run dev here)`
3. **Model Weights Deployment:** `(input instructions for loading quantized LLM here)`

## Deploying on Vercel

The Vite app lives at `frontend`, not the repository root.

1. Project → Settings → General → Root Directory → `frontend`.
2. Framework Preset: Vite. Build Command: `npm run build`. Output Directory: `dist`.
3. Add the `VITE_*` variables from `frontend/.env.example`.
4. The included `vercel.json` adds a SPA rewrite so client routes load `index.html`.

---

## Privacy & custody

* **Non-custodial Data** — Sensitive Personal Identifiable Information (PII) like TIN, SSS, and bank accounts are flagged locally to warn you before data transmission occurs.
* **On-Device Optimization** — Our core quantized models aim to transition workflows into local execution blocks to minimize remote exposures of sensitive documents.

---

## The Problem Is Real — And the Numbers Prove It

SULO directly targets the systemic legal comprehension crisis in the Philippines:

### 🔓 Legal Access Gap
* **80% of Filipinos have no access to legal help** (World Justice Project Survey).
* Of the 20% who do, 72% rely entirely on friends/family—**only 15% manage to consult an actual lawyer**.
* *Visual Suggestion:* A photo of a Filipino family sitting around a kitchen table looking stressed over a legal notice instead of sitting with an attorney.

### 📖 Comprehension Crisis
* **Only 70.8% of Filipinos aged 10–64 are functionally literate** under the modern comprehension standard (PSA FLEMMS). 
* **24.8 million Filipinos struggle to understand what they read**, and 21% of senior high school graduates fail functional literacy expectations.
* *Visual Suggestion:* An infographic split-panel showing two people looking at the exact same contract—one completely lost, one with a clear path forward.

### 🌐 Language Barrier
* For close to a century, nearly **all law teaching and legal drafting in the Philippines has been done in English**.
* With 8 major languages and over 85 dialects, documents are fundamentally structured for lawyers, not ordinary citizens.
* *Visual Suggestion:* Close-up photo of dense English legalese text right beside a confused worker.

### 👷 Labor & Workplace Abuse
* DOLE inspected 30,000 establishments and found violations so rampant that **3.28 million workers had to recover lost wages**.
* Common systemic issues include unpaid overtime, illegal deductions, and unremitted SSS/PhilHealth/Pag-IBIG logs. DOLE explicitly notes that **lack of awareness among workers is the primary reason abuses persist**.
* *Visual Suggestion:* A photo of a worker staring anxiously at a payslip with unknown deduction values highlighted in red ink.

### 💸 Predatory Lending & Loan App Abuse
* **47.5 million Filipinos used online loan apps**, fueled by an unbanked population of roughly 37 million adults.
* Lenders deliberately deploy confusing language so borrowers sign without understanding actual penalty risks. Victims drop complaints because the legal process is too tedious—**they just want the harassment to stop**.
* *Visual Suggestion:* A smartphone screen displaying an ominous collection message with hidden fee fine print in the background.

---

### 💡 The Connecting Thread
> Filipinos are signing documents and entering agreements they do not fully understand. By the time they realize what happened, it is already too late. The law exists. The rights exist. The gap is in comprehension. 
> 
> **A right you cannot read, in a language you weren't taught, explained by a lawyer you can't afford—is not really a right at all.**

---

Built for the Hackathon. Powered by SULO Core Engineering. Made with care.
