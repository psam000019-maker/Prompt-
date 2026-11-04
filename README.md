# PROMPT MASTER - Premium AI Prompt Library & Engineering Suite

**PROMPT MASTER** is a modern, high-performance AI Prompt Library and Engineering platform supporting 13+ major AI tools (ChatGPT, Claude, Gemini, DeepSeek, Grok, Perplexity, Copilot, Midjourney, DALL-E, Stable Diffusion, Runway, Kling, Sora).

Built with **React 19**, **TypeScript**, **Tailwind CSS v4**, and **Node.js Express** with full bilingual support (**Arabic RTL by default** and **English LTR**).

---

## 🌟 Key Features

1. **Massive Bilingual Prompt Library (109+ Engineered Prompts)**
   - 19 professional categories and subcategories.
   - Comprehensive prompts with roles, objectives, context, constraints, difficulty levels, quality scores (/100), and sample outputs.
   - One-click copy with persistent counter.

2. **AI Prompt Optimizer**
   - Transforms basic prompts into 5 versions: *Professional Enhanced, Deep Detailed, Strategic Master, Structured Steps, and Model-Tuned*.
   - Powered by Gemini 2.5 Flash with deterministic engineering fallbacks.

3. **Smart Visual Prompt Builder**
   - Modular builder for AI Role, Objective, Context, Target Audience, Instructions, Negative Constraints, Output Format, and Tone.

4. **Prompt Quality Scorer & Evaluator**
   - Evaluates clarity, specificity, context, instructions, constraints, and output format.
   - Computes score out of 100 with actionable optimization advice.

5. **Prompt Comparison Suite**
   - Side-by-side prompt diffing with strength analysis and recommendations.

6. **AI Models Intelligence Directory**
   - Architecture dossiers for 13 AI engines with engineering tips and prompt structure guidance.

7. **Variable Templates & Specialized Studios**
   - Dynamic prompt templates with placeholder replacement (`{{variable}}`).
   - Midjourney / Flux Studio and Runway / Sora / Kling Video Director Studio.

8. **Profile Dashboard & Global Backup**
   - Manage saved prompts, favorites, and collections.
   - **Global Export (JSON & CSV)**: Export all saved prompts, collections, and metadata in unified backup files for external storage.
   - **Full Project ZIP Download**: Download the entire source code repository in one click to push directly to GitHub.

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ or 20+
- npm or yarn

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/prompt-master.git
cd prompt-master

# 2. Install dependencies
npm install

# 3. Create .env file (optional: add Gemini API key)
cp .env.example .env
# Edit .env and set GEMINI_API_KEY="your-gemini-api-key"

# 4. Start the development server
npm run dev
```

Visit `http://localhost:3000` in your browser.

---

## 📂 Project Structure

```text
├── data/                    # JSON database storage
├── src/
│   ├── components/          # React components (Header, Cards, Optimizer, Builder, Profile, etc.)
│   ├── data/                # Seed data & 109 engineered prompts
│   ├── locales/             # Translations (Arabic & English)
│   ├── utils/               # Scorer, Comparator, Exporter (JSON, CSV, ZIP)
│   ├── types/               # TypeScript interfaces
│   ├── App.tsx              # Main application shell
│   └── main.tsx             # React DOM entry point
├── server.ts                # Express backend & API proxy
├── vite.config.ts           # Vite build configuration
└── package.json             # NPM dependencies & scripts
```

---

## 📄 License
Apache-2.0
