# 📊 Biostatistics Skill (`SKILL.md`)

Skill specialized in **Biostatistics and Statistics Applied to Health Sciences** for Artificial Intelligence assistants (compatible with platforms supporting agent and skill specifications via `SKILL.md`).

Designed to solve problems, test hypotheses, and interpret clinical results following **university academic rigor**, avoiding shortcuts or superficial solutions.

---

## 📌 Origin and Methodology (Transparency Notice)

> **Development Note:**  
> This project has been drafted and structured with **heavy Artificial Intelligence assistance**, but **its logic, methodology, and criteria are entirely grounded in official lecture notes and syllabi from 2nd-year university Biostatistics** (Health Sciences Degrees: Medicine, Biology, Pharmacy, Nursing, Biotechnology).

The main goal was to transform the rigor of traditional lecture notes (notations, mandatory exam steps, hypothesis justification, and clinical criteria) into a set of strict system instructions so that the AI does not invent procedures or provide simplistic answers.

---

## What Does This Skill Do?

When activated, the AI assumes the role of a teacher/specialist and applies a strict resolution protocol:

1. **Absolute priority to student notes:** If material or class notes are attached, it prioritizes the professor's nomenclature and formulas.
2. **7-step academic structure:**
   - Data and objective
   - Method selection and justification
   - Analytical formula
   - Substitution and detailed calculation (no sudden leaps)
   - Result with units and proper rounding
   - Contextualized interpretation in health
   - Verification of assumptions and limitations
3. **Biomedical focus:**
   - Clearly distinguishes between statistical significance ($p < \alpha$) and clinical importance.
   - Rigorous handling of diagnostic tests (Sensitivity, Specificity, Prevalence, PPV, and NPV via Bayes' Theorem).
   - Proper handling of parametric vs. non-parametric tests and verification of normality/homoscedasticity.

---

## 🌐 Language and Multilingual Support

- **Default language:** Spanish (with terminology adapted to the Spanish-speaking university environment).
- **Adaptation to other languages:** Although its base configuration responds in Spanish, the skill explicitly includes in its instructions (*Section 3: "Respond in Spanish, unless the user requests another language"*) the capability to operate in **any other language** (English, French, etc.). Simply asking for it in the prompt or submitting the query in that language is enough for it to adapt both the reasoning and the corresponding statistical notation.

---

## Triggers

The skill is automatically activated when key terms are detected in the conversation or prompt, such as:

- `bioestad`
- `bioestadistica`
- `bioestadística`
- Or explicit requests to solve or perform hypothesis tests on medical statistics exercises, analytical epidemiology, or inference.

---

## 📂 Repository Contents

```text
├── assets/
│   └── bibliograf.tex  # Biostatistics notes and reference sources (LaTeX)
├── SKILL.md            # Skill definition (instructions + YAML frontmatter)
├── LICENSE             # Terms of the license of use
└── README.md           # Project documentation
```

---

## ⚙️ Installation / Usage

### Option 1: On platforms compatible with Agent Skills / `.skill`
1. Download the `SKILL.md` file (or compress it into a `.zip` archive if required by your platform).
2. Upload it to your agent's skills/tools configuration panel.

### Option 2: As Custom Instructions / System Prompt
If you use ChatGPT, Claude, or another web interface without native support for `.skill` files:
1. Open `SKILL.md`.
2. Skip the initial YAML block (`--- ... ---`).
3. Copy the rest of the text and paste it into the **Custom Instructions (System Prompt)** section of your assistant or project.

---

## 📖 Topics Covered

- **Descriptive statistics:** Measures of central tendency, dispersion, skewness, and robustness against *outliers*.
- **Probability and diagnosis:** Bayes' Theorem, false positive/negative rates, conditional probabilities.
- **Theoretical distributions:** Binomial, Poisson, Normal, Student's $t$, Chi-square, etc.
- **Sampling and estimation:** Point estimation, standard errors, and sample size calculation.
- **Confidence intervals and hypothesis testing:** Two-tailed/one-tailed formulations, test statistics, critical region, and $p$-values.
- **Association and models:** Contingency tables, correlation (Pearson/Spearman), and linear regression.

---

## ⚠️ Disclaimer

This skill is intended as a **support tool for university studies**. Although it has been designed to minimize hallucinations and enforce mathematical verification:
- It must always be checked against the specific criteria of each faculty or department's teaching staff.
- **It must not be used as a tool for clinical diagnosis or real-world medical decision-making.**

---

## Contributions

If you are taking Biostatistics and feel that any convention, common statistical test, or edge case is missing, pull requests and issues are welcome!
