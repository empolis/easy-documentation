# EASY Documentation

This repository contains the Quarto source files for the documentation of the **EASY Project** (Energieeffiziente Analyse- und Steuerungsprozesse im dynamischen Edge-Cloud-Kontinuum für die industrielle Fertigung / Energy-Efficient Analysis and Control Processes in the Dynamic Edge-Cloud Continuum for Industrial Manufacturing), published at [doku.easy-edge-cloud.de](https://doku.easy-edge-cloud.de).

![](pictures/Logos/EASY-Logo-Schwarz.png){width="40%"}

## About the Project

The EASY Project develops solutions for energy-efficient analysis and control processes in industrial manufacturing through intelligent use of the edge-cloud continuum. The documentation summarizes key findings and results, covering:

-   Runtime environment and infrastructure
-   Efficient analysis processes
-   Federated machine learning
-   Flexible control processes
-   Practical demonstrators and use cases
-   Business models and exploitation

## Contributing

Suggestions, modifications, or extensions are welcome! Please create a **Pull Request** in this repository:

**Repository:** [github.com/empolis/easy-documentation](https://github.com/empolis/easy-documentation)

## Building the Documentation

### Install quarto

Follow the instructions in https://quarto.org/docs/get-started/

### HTML Version

``` bash
quarto render --profile html --to html
```

### PDF Version

``` bash
quarto render --to titlepage-pdf --no-clean
```

Output is generated in the \_book/ directory.

## Project Structure

``` bash
├── _quarto.yml                         # Quarto configuration for pdf
├── _quarto-html.yml                    # Quarto configuration for html
├── index.qmd                           # Title page
├── contents/                           # Chapters and content 
├── contents/001_introduction/          # Chapters and content for introduction
├── contents/002_laufzeitumgebung/      # Chapters and content for runtime environment and EASY framework
├── contents/003_eff_analyseprozesse/   # Chapters and content for efficient analysis processes
├── contents/004_verteiltes_ml/         # Chapters and content for federated learning
├── contents/005_flex_steuerung/        # Chapters and content for flexible control processes
├── contents/006_demonstratoren/        # Chapters and content for practical demonstrators and use cases
├── contents/007_geschaeftsmodelle/     # Chapters and content business models and exploitation
├── contents/references.bib             # Bibliography
├── contents/ausblick.qmd               # Outlook
├── contents/authors.qmd                # Authors
├── styles.css                          # CSS customization
├── fonts                               # font files
├── _book/                              # Rendered html and pdf files
```

## License & Contact

See contents/impressum.qmd, contents/datenschutz.qmd and contents/001_introduction/kontakt.qmd or contents/001_introduction/projektpartner.qmd for further information.

Last updated: 08.09.2026 \| Version v3.2