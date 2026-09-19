# Looksmax Score Calculator & Evidence-Based Action Plan Engine

A calibrated, harm-reduction-first self-assessment tool engineered for [looksmaxxing.guide](https://looksmaxxing.guide).

🔗 **Live Tool:** [https://blxrryfxce17.github.io/looksmax-score-calculator/](https://blxrryfxce17.github.io/looksmax-score-calculator/)  
📂 **GitHub Repo:** [https://github.com/BlxrryFxce17/looksmax-score-calculator](https://github.com/BlxrryFxce17/looksmax-score-calculator)

---

## 🎯 Purpose & Why This Was Built

On `looksmaxxing.guide`, the primary call-to-action button in the site header is **"Looks Maxx Yourself"** pointing directly to `/en/looksmax-score/`. However, that page currently features only static editorial copy and a manual pen-and-paper formula in `<noscript>`. 

This project bridges that exact high-friction drop-off by delivering an **interactive, calibrated 0–100 self-assessment tool** that:
1. Matches the site's exact 6 weighted pillars (Facial Harmony 25%, Physique 20%, Skin 15%, Hair 15%, Grooming 15%, Jawline 10%).
2. Anchors subjective 1–10 ratings with concrete physiological descriptors to mitigate body dysmorphia and rating inflation.
3. Computes the user's weighted score with a dynamic radial SVG meter and real-time pillar breakdown.
4. Programmatically detects the user's **highest-ROI bottleneck** (e.g. Skin or Grooming vs. unchangeable bone structure).
5. Generates a tailored **90-Day Evidence-Based Action Plan** emphasizing high-ROI softmaxxing (SPF 50, tretinoin, posture, dental care, body recomp).
6. Embeds prominent **Harm-Reduction Alerts** explicitly debunking dangerous internet trends (e.g., hammer bonesmashing, unregulated lipolytic injections like Aqualyx).
7. Enables state sharing via URL search params and 1-click clipboard export for journaling.

---

## 🛠️ Architecture & Tech Stack

- **Pure HTML5 / Modern CSS3 (Vanilla)**: Zero external UI frameworks, customized CSS custom properties (`--bg-dark`, `--accent #D19C14`, `--accent-fitness #E5443B`, etc.), responsive layout, glassmorphic header.
- **Vanilla ES6+ JavaScript**: Reactive calculations on slider input, SVG circular progress offset math, dynamic DOM rendering of tailored protocols, and URL state persistence.
- **Ultra-Lightweight & Fast**: Zero npm dependencies, sub-50KB total footprint, instant first-contentful paint.
- **Accessibility & Harm Reduction**: Screen-reader friendly semantic structure, contrasting text, and medically grounded disclaimers.

---

## 🚀 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/BlxrryFxce17/looksmax-score-calculator.git

# Open index.html directly in any modern browser
# or serve with any static server:
npx serve .
```
