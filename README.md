# Sid Quarto Portfolio

A data science and analytics portfolio built with Quarto, showcasing projects, analyses, and visualizations.

## Overview

This repository contains a Quarto-based portfolio website that demonstrates data science skills, statistical analysis, and data visualization capabilities. The portfolio is designed to be both a learning resource and a professional showcase of analytical work.

## Features

- **Interactive Documentation**: Powered by Quarto for rich, interactive content
- **Data Analysis**: Python-based statistical analysis and modeling
- **Visualizations**: Comprehensive charts and graphs for data insights
- **Reproducible Research**: All code and data are version controlled and documented
- **Professional Presentation**: Clean, modern design suitable for professional portfolios

## Project Structure

```
sid-quarto-portfolio/
├── README.md                 # This file
├── .gitignore               # Git ignore rules for Python/Quarto projects
├── _quarto.yml             # Quarto configuration (to be added)
├── index.qmd               # Portfolio homepage (to be added)
├── projects/               # Individual project folders (to be added)
│   ├── project-1/
│   ├── project-2/
│   └── ...
├── data/                   # Data files (to be added)
├── scripts/                # Analysis scripts (to be added)
└── _site/                  # Generated site output (ignored by git)
```

## Getting Started

### Prerequisites

- [Python](https://www.python.org/downloads/) (3.8 or higher)
- [Quarto](https://quarto.org/docs/get-started/)
- [Git](https://git-scm.com/downloads)

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd sid-quarto-portfolio
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Building the Portfolio

1. Render the Quarto site:
   ```bash
   quarto render
   ```

2. Preview the site locally:
   ```bash
   quarto preview
   ```

3. The site will be available at `http://localhost:4200`

## Content Guidelines

### Adding New Projects

1. Create a new folder in `projects/` with a descriptive name
2. Add a Quarto document (`.qmd`) with your analysis
3. Include any necessary data files in the project folder
4. Update the main navigation in `_quarto.yml`

### Best Practices

- **Documentation**: Always include clear explanations of your methodology
- **Reproducibility**: Ensure all code runs from scratch
- **Data Privacy**: Never commit sensitive or personal data
- **Code Quality**: Follow Python PEP 8 style guidelines
- **Version Control**: Commit frequently with meaningful messages

## Technologies Used

- **Quarto**: Document publishing system
- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **Matplotlib/Seaborn**: Data visualization
- **Jupyter**: Interactive development environment
- **Git**: Version control

## Contributing

This is a personal portfolio project. If you have suggestions or want to collaborate, please feel free to reach out or submit issues.

## License

This project is for educational and portfolio purposes. Please respect any data usage rights and cite sources appropriately.

## Contact

For questions or collaboration opportunities, please reach out through the contact information provided in the portfolio.

---

*Last updated: October 2025*
