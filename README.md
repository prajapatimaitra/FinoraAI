# FinoraAI 🚀
> **AI-Native Business Financial Intelligence Platform & Financial Copilot for SMBs**

FinoraAI transforms raw, cryptic bank transactions into deep business understanding and actionable financial intelligence tailored specifically to small and medium-sized businesses (SMBs).

---

## 📌 1. The Problem We Are Solving

Small and medium-sized businesses generate dozens of transactions daily via UPI, NEFT, IMPS, or cards. However, standard bank statements and traditional accounting tools present transactions with vague, abbreviated descriptions:

```text
UPI-RAJESH           ₹18,500
NEFT-ABC TRADERS     ₹50,000
IMPS-AMZN            ₹2,400
```

### The Limitations of Existing Accounting Tools:
- **No Context Awareness**: Traditional systems record *that* money moved, but cannot determine *why* it moved. A payment like `₹18,500 to Rajesh` could represent raw material purchase, employee salary, transport fees, equipment repair, or a personal drawing.
- **Generic Rules Fail**: Universal rules fail because the same vendor name represents completely different expense types for different industries (e.g., a paper supplier is a raw material expense for a packaging manufacturer, but an office supply expense for a software agency).
- **Time-Consuming Manual Entry**: Business owners spend hours every week manually classifying expenses, reconciling ledgers, and trying to decipher financial reports.

---

## 💡 2. The Solution: FinoraAI

**FinoraAI** is an AI financial copilot that understands your specific business model, learns from your historical transactions, interprets ambiguous line items in context, and provides proactive business insights.

```
Transaction Data + Business Profile + Vendor History + Context 
                               ⬇️
               Intelligent Business Action & Insights
```

### Core Solution Capabilities:
1. **Business Profile Engine**: Adapts transaction evaluation rules based on business type, main suppliers, typical expense profiles, and industry domain.
2. **Context-Aware Categorization**: Automatically infers expense intent, itemization, tax impact, and cost-of-goods-sold (COGS) allocation.
3. **Digital Khata & Ledger**: Streamlined customer and vendor ledger management with real-time balance tracking and transaction detail modals.
4. **Ask AI (Voice & Text Assistant)**: Multi-modal financial copilot with real-time voice recording capabilities to answer financial queries on demand.
5. **Proactive Financial Intelligence**: Automatically suggests cash flow optimizations, working capital improvements, and cost reduction opportunities.

---

## ✨ 3. Key Features

- 📊 **Financial Dashboard (`HomeTab`)**: High-level metrics, cash flow charts, recent transaction feeds, and business health indicators.
- 📖 **Khata Ledger (`KhataTab`)**: Manage customer & supplier credit/debit balances, filter entries, and log new transactions with `AddEntryModal`.
- 💬 **Ask AI Copilot (`AskAITab`)**: Ask complex financial questions using text or voice recording via an integrated microphone interface.
- 💡 **AI Business Insights (`IdeasTab`)**: Proactive financial strategies for working capital optimization, tax efficiency, and cost management.
- 🔍 **Detailed Entry View (`EntryDetailModal`)**: Deep dive into individual transactions to view metadata, receipt proofs, and AI-inferred category breakdowns.

---

## 🛠️ 4. Tech Stack

- **Frontend Framework**: React 18 + Vite
- **Language**: TypeScript & JavaScript (ESNext)
- **Styling**: Tailwind CSS + Radix UI Primitives + Framer Motion
- **Icons & Visuals**: Lucide React + React Icons
- **Charts & Analytics**: Recharts
- **Form & Validation**: React Hook Form + Zod
- **Routing & Navigation**: Wouter

---

## 🚀 5. How to Run the Project (Step-by-Step)

Follow these instructions to set up and run FinoraAI locally on your machine.

### Prerequisites
Make sure you have the following installed on your system:
- **Node.js**: `v18.0.0` or higher ([Download Node.js](https://nodejs.org/))
- **npm** (comes with Node.js) or **yarn** / **pnpm**
- **Git**: ([Download Git](https://git-scm.com/))

---

### Step 1: Clone the Repository
Open your terminal and clone the repository:

```bash
git clone https://github.com/prajapatimaitra/FinoraAI.git
```

---

### Step 2: Navigate to Project Directory

```bash
cd FinoraAI
```

---

### Step 3: Install Dependencies
Install all required project dependencies:

```bash
npm install
```

---

### Step 4: Start the Development Server
Run the local Vite development server:

```bash
npm run dev
```

Once started, open your browser and navigate to:
```text
http://localhost:3000
```
*(or `http://localhost:5173` depending on port availability)*

---

### Step 5: Build for Production (Optional)
To verify TypeScript compilation and create an optimized production build:

```bash
npm run build
```

---

### Step 6: Preview Production Build (Optional)
To test the built output locally:

```bash
npm run serve
```

---

## 📁 Project Structure Overview

```text
FinoraAI/
├── public/                 # Static public assets
├── src/
│   ├── assets/             # Images and design assets
│   ├── components/         # UI components & tab views
│   │   ├── AddEntryModal.jsx
│   │   ├── AskAITab.jsx
│   │   ├── EntryDetailModal.jsx
│   │   ├── HomeTab.jsx
│   │   ├── IdeasTab.jsx
│   │   ├── KhataTab.jsx
│   │   ├── Sidebar.jsx
│   │   └── ui/             # Reusable Radix UI components
│   ├── App.tsx             # Root Application component & routing layout
│   ├── index.css           # Global Tailwind CSS styles
│   └── main.tsx            # Application entry point
├── 01_AI_Business_Financial_Intelligence_Platform.md # Architecture specification
├── COLOR_THEME.md          # Color palette & design tokens guide
├── package.json            # Scripts & project dependencies
├── tsconfig.json           # TypeScript configuration
└── vite.config.ts          # Vite build configuration
```

---

## 📝 License

This project is licensed under the MIT License.
