# 📞 **3CX Call Log Analyzer**

A premium, high-performance static web application built to instantly parse multi-line **3CX call logs** and extract critical metrics. Designed with a stunning **glassmorphism dark UI** and fluid micro-animations for an exceptional user experience.

---

## 🚀 **Key Features**

*   📊 **Total Dials** — Displays the absolute count of all outgoing call attempts.
*   👥 **Unique Dials** *(New)* — Filters out duplicate numbers to track actual unique contacts reached.
*   🔥 **Peak Answered Calls Time** *(New)* — Automatically calculates the hour window with the highest volume of successfully answered calls.
*   ⏱️ **Total Talk Time** — Sums up duration from all answered calls formatted in `HH:MM:SS`.
*   ✅ **Answered Calls** — Counts calls with valid talk duration records.
*   ❌ **Unanswered Calls** — Tracks missed calls and attempts without duration.
*   📝 **Result Summary Dashboard** — An expandable/dynamic monospace summary block for quick audits.
*   ✨ **Smooth Animations** — Easing numerical counters and pulse-glow highlights upon processing new data logs.

---

## 🎨 **Design & Tech Stack**

*   **HTML5** & **Vanilla Javascript** (ES6+ Engine)
*   **Tailwind CSS** (Configured with custom dark mode & layout specs)
*   **Glassmorphic Design** (Translucent backgrounds, subtle backdrops, and borders)
*   **Performance First** (Zero framework bloat, instant processing done entirely client-side)

---

## 📋 **Supported Log Format Example**

Simply paste raw multi-line logs formatted as follows into the input text area:

```text
07415527980
04/14/2026 7:35 PM, 00:12:43

08926040811
04/14/2026 7:34 PM, 00:00:20

09123456789
04/14/2026 7:45 PM
```

---

## 🛠️ **Installation & Local Development**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/USERNAME/REPO-NAME.git
   cd REPO-NAME
   ```

2. **Open index.html:**
   Simply open the `index.html` file in any modern web browser, or serve it locally:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server -p 8000
   ```

---

## 📤 **Deploying to Vercel**

This project is fully ready for deployment as a static app on **Vercel**:

1. Install the Vercel CLI:
   ```bash
   npm install -g vercel
   ```
2. Run the deployment command:
   ```bash
   vercel
   ```
3. Follow the CLI prompts to deploy your live project link.
