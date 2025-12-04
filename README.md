# MANIT Presentation Template

A comprehensive Quarto presentation template for **Maulana Azad National Institute of Technology (MANIT), Bhopal** featuring the Metropolis theme design for both Beamer (PDF) and RevealJS (HTML) formats.

## ✨ Features

- **Dual Output Formats**
  - 📄 **Beamer PDF** - Professional LaTeX-based presentations for printing and formal submissions
  - 🌐 **RevealJS HTML** - Interactive web presentations with animations and multimedia support

- **Metropolis Theme Design**
  - Clean, modern typography with Fira Sans and Source Code Pro
  - MANIT brand colors (Blue #1969AA, Orange #CC5900)
  - Metropolis-inspired dark teal (#23373b) accents
  - Consistent styling across both formats

- **Comprehensive Feature Set**
  - ✅ Code syntax highlighting with 20+ themes
  - ✅ Auto-animate code transitions
  - ✅ Line-by-line code highlighting
  - ✅ LaTeX equations with MathJax/KaTeX
  - ✅ Mermaid diagrams (flowcharts, sequences, etc.)
  - ✅ Multi-column layouts
  - ✅ Incremental lists and fragments
  - ✅ Tabsets for multi-language code examples
  - ✅ Custom backgrounds and transitions
  - ✅ Speaker notes and presenter view
  - ✅ MANIT logo and branding

## 🚀 Quick Start

### Prerequisites

- [Quarto](https://quarto.org/docs/get-started/) 1.4.0 or higher
- For PDF output: XeLaTeX (included in [TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/))
- Modern web browser for HTML output

### Installation

1. **Clone or download this template:**
   ```bash
   git clone https://github.com/ResearchInfuser/manit-presentation.git
   cd manit-presentation
   ```

2. **Start editing `presentation.qmd`** with your content

3. **Render your presentation:**
   ```bash
   # RevealJS HTML (interactive web presentation)
   quarto render presentation.qmd --to presentation-revealjs
   
   # Beamer PDF (for printing/formal submission)
   quarto render presentation.qmd --to presentation-beamer
   
   # All formats
   quarto render presentation.qmd
   ```

### Basic Document Structure

```yaml
---
format:
  presentation-beamer: default
  presentation-revealjs: default
---

# MANIT Quarto Presentations

## Hello, There

This presentation demonstrates:

- Code highlighting and animations
- LaTeX equations
- Diagrams and visualizations
- And much more!

# Section Title

## Slide Content

Your content here...
```

## 📚 What's Included

The template includes extensive examples of:

1. **Code Presentation**
   - Syntax highlighting with multiple themes
   - Auto-animate transitions between code states
   - Line-by-line highlighting for walkthroughs

2. **Mathematics**
   - Inline and display equations
   - Multi-line derivations
   - Complex mathematical notation

3. **Layout Features**
   - Column layouts for side-by-side content
   - Incremental lists and fragments
   - Tabsets for organizing related content

4. **Visualizations**
   - Mermaid flowcharts and diagrams
   - Process flows and sequence diagrams
   - Tables and data presentation

5. **Advanced Features**
   - Custom backgrounds and gradients
   - Slide transitions
   - Speaker notes and presenter view
   - Navigation shortcuts

## 🎨 Customization

### Colors

Edit `_extensions/presentation/revealjs/manit.scss` to customize colors:

```scss
// MANIT Official Colors
$manit-blue: #1969AA;
$manit-orange: #CC5900;

// Metropolis Theme Colors
$metropolis-dark-teal: #23373b;
$metro-dark: rgba($metropolis-dark-teal, 0.9);
$metro-medium: rgba($metropolis-dark-teal, 0.7);
$metro-light: rgba($metropolis-dark-teal, 0.1);
```

### Logo

Replace `_extensions/presentation/_images/logo/manit_logo.png` with your department or project logo.

### Fonts

The template uses:
- **Presentation text**: Fira Sans
- **Code blocks**: Source Code Pro

To change fonts, edit the SCSS files in `_extensions/presentation/`.

## 🏗️ Project Structure

```
manit-presentation/
├── presentation.qmd          # Main presentation file
├── README.md                 # This file
├── LICENSE                   # MIT License
├── references.bib            # Bibliography file
├── _quarto.yml              # Quarto project configuration
└── _extensions/
    └── presentation/
        ├── _extension.yml    # Extension configuration
        ├── _images/          # Logos and background images
        ├── beamer/           # Beamer theme files
        └── revealjs/         # RevealJS theme files
            └── manit.scss    # Main stylesheet
```

## 💡 Usage Tips

### For Research Presentations

- Use speaker notes (press `S` in RevealJS) for detailed explanations
- Include references in `references.bib` and cite with `@citationkey`
- Use incremental lists to control information flow
- Add diagrams to illustrate complex processes

### For Course Lectures

- Use tabsets to show code in multiple languages
- Use line highlighting to walk through code step-by-step
- Include executable code examples (configure Python/R environment)
- Use fragments for step-by-step reveals

### For Conference Talks

- Keep slides focused (one main idea per slide)
- Use auto-animate for smooth transitions
- Include MANIT branding consistently
- Test presentation beforehand in target environment

## 📖 Documentation

- [Quarto Presentations](https://quarto.org/docs/presentations/)
- [RevealJS Features](https://quarto.org/docs/presentations/revealjs/)
- [Beamer Output](https://quarto.org/docs/presentations/beamer.html)

## 🙏 Credits

- **Metropolis Theme**: Based on [Metropolis Beamer Theme](https://github.com/matze/mtheme) by Matthias Vogelgesang
- **MANIT Branding**: Official colors and logo from MANIT Bhopal
- **Quarto**: Built with [Quarto](https://quarto.org) publishing system

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs or issues
- Suggest new features
- Submit pull requests
- Share your presentations made with this template

## 👤 Author

**Prashant Kumar Nag**
- Email: prashantnag.workmail@gmail.com
- Department of Mathematics, Bioinformatics and Computer Applications
- Maulana Azad National Institute of Technology, Bhopal

---

**Made with ❤️ for the MANIT community**

