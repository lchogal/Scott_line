# Scott Family Tree

Interactive family tree visualization for the Scott lineage and related branches.

## View

https://lchogal.github.io/Scott_line/

## About

Created by [Leslie Hodges Gallagher](https://lchogal.github.io/cv/).

Research compiled from Geni.com, FamilySearch.org, and FindAGrave.com. This is a working draft - primary sources are still being verified.

## Branches

This repository includes visualizations for multiple Scott family branches:

- Main Scott Line
- Powell Branch
- Satterwhite Branch
- Duke Branch
- McCracken Branch
- Woody Branch

## Requirements

To regenerate the family tree visualizations:

- Python 3.11.5+
- pandas
- Graphviz 14.0.4+
- Quarto 1.3+ (for webpage rendering)

Install dependencies:
```bash
pip install pandas
brew install graphviz quarto
```

## Files

- `index.html` - Interactive family tree webpage (generated from Scott_tree.qmd)
- `Scott_tree.qmd` - Quarto source file for the webpage
- `data/` - CSV files containing genealogy data for each branch
- `convert_family.py` - Python script to generate tree visualizations
- `output/` - Generated tree files (PNG, SVG, HTML)

## Contact

Questions or corrections: [hodges.gallagher@gmail.com](mailto:hodges.gallagher@gmail.com)
