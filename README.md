# Bahria University Islamabad MS and PhD Thesis Template

This repository provides a **structured, easy-to-edit LaTeX thesis template** designed by **Dr. Hazoor Ahmad** for **MS and PhD students** at **Bahria University Islamabad Campus**. Tailored to meet the formatting guidelines of Bahria University, this template is ideal for theses and dissertations in fields like Electrical Engineering, Computer Science, Earth and Environmental Sciences, and others. It ensures compliance with university standards while being beginner-friendly and highly customizable. Optimized for **TeXstudio**, this template supports both MS and PhD candidates in producing professional academic documents.

## Features
- **Bahria University Compliance**: Configured for A4 paper, 12pt font, two-sided printing, with 1.5-inch left margin, 1-inch other margins, Times New Roman font, and 1.5 line spacing, as required for MS and PhD submissions.
- **Predefined Constants**: Uses `\newcommand` for consistent reuse of key details like author name (`Hamza Saleem`), thesis title (`THESIS TITLE IN CAPITAL LETTERS`), supervisor name (`Dr. Hazoor Ahmad, PhD`), and enrollment number (`01-249231-002`).
- **Modular Structure**: Organized with separate files for preamble, title pages, abstract, nomenclature, chapters, and references for easy maintenance.
- **Comprehensive Sections**: Includes title page, abstract, table of contents, list of tables, list of figures, nomenclature, chapters, references (using `elsarticle-num` BibTeX style), and appendices.
- **Version Control Ready**: Clear file structure supports Git for tracking changes and collaboration.
- **TeXstudio-Optimized**: Includes comments and a logical organization for seamless use in TeXstudio.

## Repository Structure
- **`main.tex`**: The main LaTeX file, defining the document class (`report`, A4, 12pt, two-sided) and including all sections.
- **`Extras/preamble.tex`**: Contains LaTeX packages (e.g., `geometry`, `times`, `setspace`) and formatting settings for MS and PhD theses.
- **`Extras/title_pages.tex`**: Defines the title page and related preliminary pages.
- **`abstract/abstract.tex`**: Contains the thesis abstract.
- **`Extras/nomenclature.tex`**: Lists symbols and abbreviations used in the thesis.
- **`Chapter1/Chapter1.tex` to `Chapter5/Chapter5.tex`**: Individual chapter files for modular content management.
- **`Extras/References.bib`**: BibTeX file for managing references in `elsarticle-num` style.
- **Appendix**: Includes an example appendix (Appendix A) for implementation details.

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/bahria-university-thesis-template.git
   ```
2. **Set Up LaTeX Environment**:
   - Install a LaTeX distribution (e.g., MiKTeX or TeX Live).
   - Use TeXstudio or another LaTeX editor.
3. **Customize Constants**:
   - Edit `\newcommand` definitions in `main.tex` to update:
     - `\AuthorName{Hamza Saleem}` to your name.
     - `\ThesisTitle{THESIS TITLE IN CAPITAL LETTERS}` to your MS or PhD thesis title.
     - `\SupervisorName{Dr. Hazoor Ahmad, PhD}` to your supervisor’s name.
     - `\EnrollmentNumber{01-249231-002}` to your enrollment number.
4. **Add Content**:
   - Modify chapter files (`Chapter1.tex` to `Chapter5.tex`) with your MS or PhD thesis content.
   - Update `References.bib` with your citations.
   - Add figures to a `figures/` folder (if applicable) and include them using `\includegraphics`.
   - Edit `abstract.tex`, `nomenclature.tex`, and appendices as needed.
5. **Compile the Document**:
   - Open `main.tex` in TeXstudio.
   - Compile using `F5` (Compile & View).
   - Run BibTeX (`F11`) for references, then compile again.
6. **Version Control**:
   - Use Git to track changes (`git add .`, `git commit -m "Update MS/PhD thesis"`, `git push`).

## Prerequisites
- LaTeX distribution (MiKTeX or TeX Live).
- LaTeX editor (TeXstudio recommended).
- Basic LaTeX knowledge for editing content and managing references.

## Customization Tips
- **Adjust Formatting**: Modify `preamble.tex` to change margins, font, or spacing (e.g., `\doublespacing` for specific MS/PhD requirements).
- **Add Chapters**: Create additional chapter files (e.g., `Chapter6.tex`) and include them with `\input`.
- **Update References**: Use `elsarticle-num` or another BibTeX style as required by your department for MS or PhD submissions.
- **Appendices**: Add more appendices by following the example in `main.tex` (`Appendix A`).
- **Figures/Tables**: Place images in a `figures/` folder and reference them in chapters.

## Why Use This Template?
- **University-Specific**: Aligned with Bahria University Islamabad’s MS and PhD thesis formatting guidelines, saving time on setup.
- **Designed by Dr. Hazoor Ahmad**: Crafted by an expert to ensure academic rigor and compliance with university standards.
- **Modular and Maintainable**: Separate files for chapters, preamble, and references simplify editing and collaboration.
- **SEO-Optimized**: Designed for discoverability with searches like "Bahria University MS thesis template," "Bahria University PhD dissertation template," or "LaTeX thesis format for Pakistani universities."
- **Beginner-Friendly**: Clear file organization and comments make it accessible for LaTeX newcomers.
- **Real-World Example**: Based on a thesis for "THESIS TITLE IN CAPITAL LETTERS," supervised by Dr. Hazoor Ahmad, PhD, ensuring relevance for technical MS and PhD programs.

## Contributing
Contributions are welcome! To improve the template for MS or PhD students:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-branch`).
3. Commit changes (`git commit -m "Add MS/PhD feature"`).
4. Submit a pull request.

## License
This template is licensed under the [MIT License](LICENSE), allowing free use, modification, and distribution.

## Contact
For questions or issues, open an issue on this repository or contact [hazoor786@gmail.com](mailto:hazoor786@gmail.com).

**Keywords**: Bahria University MS thesis template, Bahria University PhD dissertation template, LaTeX thesis format, Bahria University Islamabad thesis guidelines, TeXstudio thesis template, LaTeX template for Pakistani universities, MS thesis formatting, PhD dissertation formatting, Direction of Arrival Estimation thesis, Electrical Engineering thesis, Dr. Hazoor Ahmad PhD.
