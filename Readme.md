# From Script to Document: Reproducible Research with Quarto

**KKP & KKCS Spring Professional Meeting — Crop Production and Horticulture**

📅 April 29, 2026 (Wednesday) · 📍 Gödöllő, Hungary · ⏱️ ~1.5 hours

---

## About

Are you tired of copy-pasting tables and figures from R into Word?
In this workshop, you will learn how to use [Quarto](https://quarto.org/)
to create fully reproducible documents that integrate your analysis,
visualizations, and text — all in a single file.

**What we cover:**

- Why reproducibility matters (for any software, not just R)
- Anatomy of a `.qmd` file: YAML + Markdown + Code
- Tables, figures, cross-references, and inline code
- Practical tips: automatic model equations, publication-ready tables
- One file → many outputs: HTML, PDF, Word, slides
- Brief Python integration demo

**No prior experience** with Quarto or R Markdown is needed.

---

## Workshop Materials

| File | Description |
|------|-------------|
| [`01_slides.qmd`](01_slides_quarto_ws.qmd) | Presentation slides (revealjs) |
| [`02_my_first_quarto.qmd`](02_my_first_quarto.qmd) | Follow-along document for the hands-on session |
| [`custom.scss`](custom.scss) | Slide theme |
| 🌐 [**View slides online**](https://gelsleichter.github.io/quarto_ws/01_slides_quarto_ws.html) | Rendered HTML (after publishing) |
| 🌐 [**View exercise online**](https://gelsleichter.github.io/quarto_ws/02_my_first_quarto.html) | Rendered HTML (after publishing) |

---

## Pre-Workshop Setup

> **Please complete these steps BEFORE the workshop.**
> It takes about 15 minutes. If you run into issues, bring your laptop
> and we'll troubleshoot together.

### 1. Install R

Download from <https://cran.r-project.org/>

- Windows: "Download R for Windows" → "base" → download `.exe`
- macOS: "Download R for macOS" → choose your chip (Apple Silicon or Intel)

Version **4.3 or newer** recommended. Check yours: `R.version.string`

### 2. Install RStudio

Download from <https://posit.co/download/rstudio-desktop/> (free Desktop version)

### 3. Verify Quarto works

Quarto comes **bundled with RStudio** (2022.07+). Test it:

1. Open RStudio
2. **File → New File → Quarto Document**
3. Title: "Test", Author: your name, Format: HTML
4. Click **Render** (or `Ctrl + Shift + K`)

If a rendered HTML appears — **you're ready!** ✅

> If Render fails, try to install Quarto CLI separately from
> <https://quarto.org/docs/get-started/>

### 4. Install R packages

Open RStudio and run in the console:

```r
install.packages("ggplot2")
```

That's the only package needed for the hands-on session.
The slides use additional packages (`gt`, `equatiomatic`, `broom`, `report`)
but you don't need to install those — they're for demonstration only.

### What to bring

- Your laptop (with R + RStudio installed)
- A charger
- Curiosity 🔬

---

## Some resources

- [Quarto Documentation](https://quarto.org/)
- [Quarto Gallery](https://quarto.org/docs/gallery/)
- [R for Data Science (2e) — Quarto](https://r4ds.hadley.nz/quarto)
- [Awesome Quarto](https://github.com/mcanouil/awesome-quarto)

---

## Author

**Yuri Gelsleichter** · MATE, Gödöllő
· 📧 Gelsleichter.Yuri.Andrei@uni-mate.hu
· 🔗 [github.com/Gelsleichter](https://github.com/Gelsleichter)
