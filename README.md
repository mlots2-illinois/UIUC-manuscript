# 📝 LaTeX Manuscript Template for University of Illinois Researchers

This repository provides a comprehensive and highly configurable LaTeX template designed specifically for researchers at Illinois preparing journal draft submissions. It aims to streamline the manuscript preparation process, offering robust features for various academic publishing requirements.

Forget about juggling formatting guidelines from different journals – this template provides a solid, adaptable foundation so you can focus on your research.

## ✨ Features

This template is built with flexibility and robustness in mind, offering a rich set of features to meet diverse journal requirements:

*   **Dual Title Pages:** Includes both a full title page with author information and a blinded title page for anonymous peer review, easily switchable.
*   **ORCID Integration:** Seamlessly add ORCID IDs for all authors.
*   **Flexible Author & Affiliation Management:** Define authors and their affiliations clearly and manage multiple affiliations with ease.
*   **Standard Journal Sections:** Pre-configured sections for Abstract, Keywords, Introduction, Literature Review, Methodology, Results, Discussion, Conclusion, Acknowledgments, Author Contributions, Conflicts of Interest, Funding, Supplementary Material, Data Availability, Code Availability, Ethical Approval, and Appendices.
*   **Detailed Methodology & Results Sections:** Includes examples for:
    *   Subsections for different phases of methodology (Data Preprocessing, Feature Extraction, Model Architecture, Training Procedure).
    *   Examples for presenting results (Performance Comparison, Computational Efficiency, Scalability Analysis, Sensitivity Analysis) with accompanying tables and figures.
*   **Mathematical Environments:** Ready-to-use environments for equations, theorems, definitions, lemmas, propositions, corollaries, examples, remarks, and notes.
*   **Cross-Referencing:** Utilizes `cleveref` for intelligent cross-referencing of sections, figures, tables, equations, and theorem environments, automatically adding "Figure," "Table," etc.
*   **Citation Management:** Configured for `natbib` with `apalike` bibliography style (easily changeable to other styles like `unsrtnat`). Includes sample citations.
*   **Table & Figure Handling:** Examples for single and multi-column tables (`booktabs`, `tabularx`, `longtable`, `threeparttable`) and figures (`graphicx`, `subcaption`).
*   **Page Layout & Formatting:**
    *   `letterpaper` size with 1-inch margins.
    *   Adjustable line spacing (`doublespacing`, `onehalfspacing`, `singlespacing`).
    *   Optional line numbering (`lineno`) – often required for review.
    *   Customizable caption and section formatting.
    *   `microtype` for enhanced typography.
*   **Hyperlink Support:** Configured `hyperref` for clickable links within the PDF (citations, URLs, internal references).
*   **Common Abbreviations:** Pre-defined commands for `e.g.`, `i.e.`, `et al.`, `vs.`, `etc.`.
*   **Dummy Content:** Uses `lipsum` for placeholder text to quickly visualize the document structure.
*   **Error-Resistant Structure:** Designed to minimize common LaTeX errors and provide a stable base.
*   **Code & Data Availability Statements:** Dedicated sections to easily add links to your code and data repositories, crucial for open science practices.

## 🚀 Getting Started

1.  **Clone this repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```
2.  **Open with your LaTeX editor:**
    *   **Overleaf:** Upload the entire zipped repository, or create a new project and copy the files.
    *   **Local Installation (e.g., TeX Live, MiKTeX with VS Code + LaTeX Workshop):** Open the `manuscript.tex` file directly.
3.  **Customize `manuscript.tex`:**
    *   **Document Information:** Update `\manuscripttitle`, `\manuscriptsubtitle`, `\runninghead`, `\manuscriptkeywords`, and `\manuscriptabstract`.
    *   **Author Information:** Fill in `\authorone`, `\authortwo`, etc., including affiliations, emails, and ORCIDs.
    *   **Affiliations:** Define your full affiliation details in `\affilone`, `\affiltwo`, etc.
    *   **Corresponding Author:** Set `\correspondingauthor`, `\correspondingemail`, and `\correspondingaddress`.
    *   **Uncomment options as needed:** E.g., `\doublespacing` or `\linenumbers`.
    *   **Bibliography Style:** Change `\bibliographystyle{apalike}` to your desired style (e.g., `plain`, `abbrv`, `IEEEtran`).
    *   **Replace Filler Content:** Systematically replace `\lipsum` commands and example tables/figures with your actual content.
4.  **Update `cover_letter.tex`:** Modify the content to suit your submission needs.
5.  **Compile:** Use `pdflatex` (or your editor's "Build PDF" function) to compile the `.tex` files. You may need to run `pdflatex`, `bibtex` (if using a `.bib` file), and `pdflatex` again for cross-references and citations to resolve correctly.

## 📂 Project Structure
├── manuscript.tex # The main manuscript file
├── cover_letter.tex # A template for your cover letter
├── header.png # Example header image for cover letter
├── Cover_header.png # Example header image for manuscript title page
├── Cover_footer.png # Example footer image for manuscript title page
├── example-image-a.png # Placeholder image for Figure 1
├── example-image-b.png # Placeholder image for Figure 2
├── references.bib # Example BibTeX file (uncomment in manuscript.tex to use)
└── README.md # This file


## ⚠️ Important Notes

*   **Bibliography:** If you use a `references.bib` file, uncomment `\bibliography{references}` in `manuscript.tex` and ensure your LaTeX compiler runs BibTeX (or similar) after the initial `pdflatex` pass.
*   **Images:** Replace `example-image-a.png`, `example-image-b.png`, `header.png`, `Cover_header.png`, and `Cover_footer.png` with your actual figures and logos.
*   **Journal Specifics:** Always double-check and adapt this template to the specific requirements of your target journal (e.g., specific margins, font sizes, bibliography styles, or mandatory sections).

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements, new features, or find any bugs, please open an issue or submit a pull request.

## 📄 License

This template is released under the [MIT License](LICENSE). Feel free to adapt and use it for your academic work.
