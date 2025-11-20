<!-- marp: true -->
<!-- theme: custom -->
<!-- paginate: true -->
<!-- size: 16:9 -->
<!-- math: katex -->
<!-- footer: "© 2025 — Product Documentation | Contact: 21f2000646@ds.study.iitm.ac.in" -->

<style>
/* @theme custom */

section {
  font-family: 'Segoe UI', system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
}

h1, h2, h3 {
  color: #004aad;
}

.custom-box {
  border: 3px solid #004aad;
  padding: 12px;
  border-radius: 10px;
  background: #e8f1ff;
}

footer {
  font-size: 12px;
}
</style>

<!-- _class: lead -->
# Product Documentation Slides

Technical Writer: **21f2000646@ds.study.iitm.ac.in**

---

# Custom Theme Example

<div class="custom-box">
This slide demonstrates the **custom theme** using the `custom` theme name and CSS in this document.
</div>

- Custom theme: `custom` (defined with `/* @theme custom */`)
- Custom colors and fonts
- Page numbers enabled via `paginate: true`
- Suitable for version control and CI exports

---

<!-- Background Image Slide -->
![bg](https://images.unsplash.com/photo-1522071820081-009f0129c71c)

# Background Image Slide

This slide uses a **full background image**, ideal for feature highlights or product overviews.

---

# Mathematical Equations

Marp supports **KaTeX** for math rendering via the `math: katex` directive.

### Algorithmic Complexity Example

For a divide & conquer algorithm such as merge sort:

\[
T(n) = 2T(n/2) + O(n)
\]

Time complexity:

\[
T(n) = O(n \log n)
\]

Space complexity:

\[
S(n) = O(n)
\]

These formulas can be used to document performance characteristics of key product components.

---

# Architecture Overview

- Modular service-oriented architecture  
- API-first documentation  
- Markdown-based docs in Git version control  
- Exportable to **PDF**, **PPTX**, and **HTML** using Marp CLI  
- Easy to review via pull requests and code review workflows  

---

# Thank You!

For documentation requests or feedback, contact:  
📧 **21f2000646@ds.study.iitm.ac.in**
