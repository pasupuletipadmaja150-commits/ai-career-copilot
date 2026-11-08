# TalentLens AI — AI Career Copilot & Resume Analyzer 🚀

> An advanced AI product built with Google Gemini API, modern Prompt Engineering (ROLE + TASK + FORMAT + RULES), structured JSON outputs, client-side PDF parsing (`pdf.js`), multi-model selector, and analysis history.

---

## 🌟 Features (Advanced Tier +10 XP)

1. **Prompt Engineering Framework**:
   - Structured persona system: Tech Recruiter, General ATS Specialist, Fresh Graduate Advisor, and Career Transition Coach.
   - Enforced JSON response schema for deterministic, structured evaluations.
   - Grounded rule set preventing hallucinations.
2. **PDF & Document Parsing**:
   - Direct PDF upload & text extraction in-browser using `pdf.js`.
   - Support for `.txt` files and direct pasting.
3. **Dynamic ATS Score Gauge**:
   - Visual SVG circular score indicator (0–100) with color-coded grading and assessment summary.
4. **Actionable Insights Breakdown**:
   - Evidence-based strengths.
   - Missing job description keywords (tag cloud).
   - High-impact resume improvement suggestions (Google X-Y-Z formula).
   - Strategic interview preparation & next steps.
5. **Persistence & History**:
   - Past analysis sessions stored in browser `localStorage`.
   - Side drawer allowing quick recall of earlier results to track improvements.
6. **Multi-Model Selector**:
   - `gemini-2.5-flash` (fastest & high quality)
   - `gemini-2.0-flash`
   - `gemini-1.5-pro`
7. **Export Options**:
   - 📋 Copy full formatted report to clipboard
   - 💾 Download analysis as `.txt`
   - 🖨️ Print / Save as PDF view
8. **Dark Mode & Responsive UI**:
   - Full mobile and desktop responsiveness.

---

## 🔗 Direct Deployment Link

To deploy this project for free on Vercel without command-line deployment:

👉 **[Deploy to Vercel (https://vercel.com/new)](https://vercel.com/new)**

### 3-Step Manual Vercel Deployment:
1. Create a GitHub repository (e.g., `ai-career-copilot`).
2. Upload `index.html` to the repository.
3. Open [vercel.com/new](https://vercel.com/new), select your GitHub repository, choose **Other** as the Framework Preset, and click **Deploy**.
4. (Optional) In Vercel Project Settings > Environment Variables, add `GEMINI_API_KEY`.

---

## 🏃 Quick Start (Local Run)

1. Double-click [index.html](file:///C:/Users/dell/.gemini/antigravity/scratch/ai-career-copilot/index.html) to open in your browser (Chrome/Edge/Firefox).
2. Enter your free Gemini API key from [Google AI Studio](https://aistudio.google.com/).
3. Click **"Sample: Junior Dev"** and **"Load Target Job"** for instant 1-click testing.
4. Click **"Analyze Resume with Gemini"** and view your instant ATS report.
