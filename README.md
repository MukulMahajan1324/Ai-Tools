# Cover Letter Studio

A sleek, production-ready web application for crafting publication-grade, tailored PDF cover letters for job applications.

## Quick Start

### 1. Run Locally
Open `index.html` directly in any modern browser (Google Chrome, Edge, Safari, Brave, Firefox):
```
file:///C:/Users/User/.gemini/antigravity/scratch/cover-letter-studio/index.html
```
No installation, build step, or terminal server required. It runs 100% locally and securely in your browser.

### 2. Live on GitHub Pages
When GitHub Pages is enabled on this repository (`Settings` > `Pages` > `Deploy from a branch` > `main` / `root`), the tool is accessible live at:
```
https://mukulmahajan1324.github.io/Ai-Tools/
```

---

## Key Features

1. **Candidate Profile Pre-Filled with Verified Resume Credentials:**
   - **Name:** Mukul Mahajan
   - **Role:** UX/UI Designer
   - **Email:** mukulmahajan1324@gmail.com
   - **Phone:** +91 93704 95393 • +91 94227 72385
   - **Portfolio:** Behance.net/MukulM
   - **LinkedIn:** linkedin.com/in/mukulm3110
   - **Education:** M.Des (2025-2026) & B.Des (2021-2025) in Design, Indian Institute of Technology (IIT) Bombay
   - **Proven Impact:** FollowG (B2B SaaS design system, +15% task success, -60% errors), TCS Innovation Labs (Service Design), and All India Top 10 in Suzuki Next Bharat design competition.

2. **Dual-Intelligence AI Engine:**
   - **Smart Built-in AI Synthesis Engine:** Instantly parses target company names, job titles, and job description texts. Extracts core competencies, frameworks (Figma, Framer, design systems), and company initiatives to formulate a personalized, 4-paragraph persuasive letter. Zero API key needed!
   - **Direct Google Gemini API Integration (Optional):** Input your Gemini API key in the settings modal for real-time generative streaming directly from Google's latest models. Your key is stored exclusively in your browser's `localStorage`.

3. **WYSIWYG Live A4 Canvas Preview:**
   - True A4 dimensions (`210mm x 297mm`) rendered on an authentic paper sheet with margin guidelines and page numbering.
   - **Active Clickable Hyperlinks:** Email (`mailto:`), Phone (`tel:`), LinkedIn (`https://`), and Portfolio / Behance (`https://`) are interactive, clickable hyperlinks in both the live preview and the exported PDF.
   - **Direct Click-to-Edit:** Click into any sentence in the preview to tweak wording, customize greetings, or highlight specific project metrics.
   - **Rich Text Toolbar:** Bold (`Ctrl+B`), Italic (`Ctrl+I`), Bullet lists, custom Link insertion, and clean typography.
   - **Template Switcher:**
     - *Resume Style (Royal Blue)* (Default: High-craft header with large bold name, royal blue role subtitle, stacked contact icons, Behance pill, and dark divider rule matching your resume)
     - *Design Studio Monogram* (Creative studio layout with your signature **$\mu$ / mu brand logo**)
     - *Modern Minimalist* (Clean horizontal divider and right-aligned contact stack)
     - *Executive Serif* (Centered, classic serif typography for formal leadership roles)
     - *Clean Tech* (Emerald accent bar, portfolio tag, and monospace tech links)

4. **Publication-Ready PDF Export:**
   - **100% Selectable & Copyable PDF Text:** Uses a calibrated PDF text layer mapped directly to the screen DOM geometry. In any PDF viewer (Adobe Acrobat, Chrome, Preview), recruiters can highlight, select, copy (`Ctrl + C`), and search (`Ctrl + F`) all text, and ATS can parse every line without OCR.
   - **Direct Live-Preview Capture:** Captures the live styled preview element directly, ensuring text, colors, fonts, and letterhead styles render with 100% fidelity (never blank).
   - **Interactive PDF Hyperlink Preservation:** Configured with `enableLinks: true` and normalized link coordinates so recruiters can click your email, portfolio, and LinkedIn directly from the downloaded PDF.
   - **Strictly 1 Page Guarantee:** Compiles directly into a single A4 page (`210mm x 297mm`) via `jsPDF`. No multi-page split errors or blank 2nd pages.
   - **Full-Width Unclipped Geometry:** Zero margin mapping ensures the 794px A4 sheet is never cut off on laptop screens.
   - **Vector Print Engine:** Browser print (`Ctrl + P`) also configured with `@page { size: A4 portrait; margin: 0; }` for crisp vector output.
   - **Copy to Clipboard:** Copy text in one click for pasting into application portals.
