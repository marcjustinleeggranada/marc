# [Your Project Name Here]

Keep the law understandable, from anywhere. Amazon Comprehend · LLM · Vite · React · [Your Wallet/Auth Stack]

Our tool is a steady, AI-powered way to protect the people who matter — workers, borrowers, and ordinary citizens who face complex legal agreements. Upload it once. You're taken care of. Our app is a circle of trust. Users drop their confusing documents, and clarity flows instantly so that safety lives in comprehension, not in dense legal jargon. The AI parsing pipeline holds the context, runs the clause analysis, and breaks down the risk — so trust lives in clarity, not in dense legalese.

## Demo & submission

Quick links for reviewers — everything the submission rubric asks for, in one place.

### Live demo

- **Deployed app:** `(input this here)` — connect `(input this here)` and try a document upload.
- **Walkthrough video:** `(input this here)` — full feature tour.

### Mobile responsive

Captured on Android Chrome at 1080×2400 — hero, typography, and interactive risk highlights all reflow cleanly without horizontal scroll.

### CI/CD

Runs on every push to main and on every PR: `npm ci` → `npm run build` against the frontend. Workflow lives at `(input this here)`.

## Contract addresses & transactions / Core Backend Services

- **Main LLM/Comprehend Router Service:** `(input this here)`
- **Database / Storage address:** `(input this here)`
- **Sample Document Analysis Transaction/Log ID:** `(input this here)`

## Token / Pricing Integration (If applicable)

- **Asset used by the demo:** `(input this here)`
- **No custom token deployed.** If you later switch settlements to a payment portal, set `(input this here)` in the frontend `.env` and list the gateway address here.

## Deployed Infrastructure

The legal routing and parsing service is live.

- **Service/Model ID:** `(input this here)`
- **Type:** LLM Pipeline / Custom NLP Classifier
- **Network/Host:** `(input this here)`
- **Explorer/Logs:** `(input this here)`

---

## Why [Your Project Name Here]

The law protects Filipinos on paper. Labor laws, lending regulations, and consumer rights all exist—but the system is structurally inaccessible. Legally navigating daily life in the Philippines is broken, confusing, and stressful.

Our tool removes the stress. You upload any document, and the AI handles the rest, breaking down liabilities on low-cost, fast rails. Anyone can verify what they are signing before it is too late.

### What you get

- **Quiet predictability** — once a document is scanned, the fine print is instantly demystified.
- **Privacy-native** — private documents are parsed securely; raw personal details never leak.
- **Verifiable** — every clause interpretation and risk rating is mapped to actual Philippine law references.

---

## Concept vocabulary

| Brand Word             | Means                                                                      |
| :--------------------- | :------------------------------------------------------------------------- |
| **Scan/Upload**        | Submitting a document to be broken down into plain language.               |
| **Red Flag**           | A clause that is heavily skewed against the user or potentially illegal.   |
| **Plain Language**     | The translated overview ("Ano ang ibig sabihin nito sa madaling salita?"). |
| **Obligation Balance** | Visual metrics showing who bears the burden in the contract.               |

---

## How it works

1. **Upload a Document** — Drop an Employment Contract, Loan Agreement, Barangay Summons, or Terms & Conditions.
2. **Auto-Classification & Language Routing** — The system detects the language (English/Filipino/Taglish) and document type to pull up specific legal compliance checklists.
3. **Entity & Risk Extraction** — AI highlights deadlines, monetary amounts, and flags dangerous clauses (e.g., "automatic renewal", "waiver of rights").
4. **Clarity Flows** — The user reads an interactive, side-by-side translation and runs clause-by-clause Q&A to safely understand their rights.

---

## Project structure

The processing repository is organized into a modular pipeline; its core public parameters match standard text interpretation rules for seamless compatibility.

## Architecture

| Layer         | Stack                                                           |
| :------------ | :-------------------------------------------------------------- |
| **Frontend**  | React, Vite, Tailwind, Zustand, `(input wallet/auth tool here)` |
| **AI Engine** | Custom Amazon Comprehend-mapped NLP Pipeline & LLM Wrapper      |
| **Database**  | `(input this here)`                                             |

---

## Environment variables (frontend)

Copy `frontend/.env.example` to `frontend/.env` and set:

- `VITE_COMPREHEND_API_URL` — Backend processing pipeline URL.
- `VITE_LLM_GATEWAY_URL` — LLM interface for real-time contract Q&A.
- `VITE_APP_ENV` — Development or production indicator.
- `(input any extra environment variables here)`

The example variables in `.env.example` are for development purposes only.

## Local development

1. **Shared Documents API (Optional but recommended):** `(input this here)`
2. **Frontend Setup:** `(input commands like npm run dev here)`
3. **Contract/Service Setup:** `(input setup instructions here)`

## Deploying on Vercel

The Vite app lives at `frontend`, not the repository root.

1. Project → Settings → General → Root Directory → `frontend`.
2. Framework Preset: Vite. Build Command: `npm run build`. Output Directory: `dist`.
3. Add the `VITE_*` variables from `frontend/.env.example`.
4. The included `vercel.json` adds a SPA rewrite so client routes load `index.html`.

---

## Privacy & custody

- **Non-custodial Data** — Sensitive Personal Identifiable Information (PII) like TIN, SSS, and bank accounts are flagged locally to warn you before data transmission occurs.
- **Secure Infrastructure** — The backend only caches parsed clause frameworks anonymously to compile generalized risk trends without exposing personal contracts.

---

## The Problem Is Real — And the Numbers Prove It

Our tool directly targets the systemic legal comprehension crisis in the Philippines:

### 🔓 Legal Access Gap

- **80% of Filipinos have no access to legal help** (World Justice Project Survey).
- Of the 20% who do, 72% rely entirely on friends/family—**only 15% manage to consult an actual lawyer**.

### 📖 Comprehension Crisis

- **Only 70.8% of Filipinos aged 10–64 are functionally literate** under the modern comprehension standard (PSA FLEMMS).
- **24.8 million Filipinos struggle to understand what they read**, and 21% of senior high school graduates fail functional literacy expectations.

### 🌐 Language Barrier

- For close to a century, nearly **all law teaching and legal drafting in the Philippines has been done in English**.
- With 8 major languages and over 85 dialects, documents are fundamentally structured for lawyers, not ordinary citizens.

### 👷 Labor & Workplace Abuse

- DOLE inspected 30,000 establishments and found violations so rampant that **3.28 million workers had to recover lost wages**.
- Common systemic issues include unpaid overtime, illegal deductions, and unremitted SSS/PhilHealth/Pag-IBIG logs. DOLE explicitly notes that **lack of awareness among workers is the primary reason abuses persist**.

### 💸 Predatory Lending & Loan App Abuse

- **47.5 million Filipinos used online loan apps**, fueled by an unbanked population of roughly 37 million adults.
- Lenders deliberately deploy confusing language so borrowers sign without understanding actual penalty risks. Victims drop complaints because the legal process is too tedious—**they just want the harassment to stop**.

---

### 💡 The Connecting Thread

> Filipinos are signing documents and entering agreements they do not fully understand. By the time they realize what happened, it is already too late. The law exists. The rights exist. The gap is in comprehension.
>
> **A right you cannot read, in a language you weren't taught, explained by a lawyer you can't afford—is not really a right at all.**

---

Built for the Hackathon. Powered by Advanced NLP. Made with care.
