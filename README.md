# Data Science Homework 5 — Interactive Visualizations

Johns Hopkins University | Data Science for Biomedical Applications

## Live Site

**[View the visualizations here](https://jinsungsur.github.io/data_science/)**

## Contents

| File | Description |
|------|-------------|
| `index.html` | Landing page with links to both visualizations |
| `stacked_bar.html` | Part 1 — GDP stacked bar plot (IMF data, by UN region) |
| `sankey.html` | Part 2 — MRICloud brain volume Sankey diagram (Type 1, 6 levels) |
| `hw5_jin.ipynb` | Jupyter notebook with all source code for Parts 1 and 2 |

## Part 1 — GDP Stacked Bar Plot

- Web-scraped GDP data from [Wikipedia's List of countries by GDP (nominal)](https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal))
- Uses IMF forecast figures
- Countries grouped by UN region using `country_converter`
- Interactive stacked bar chart built with Plotly

## Part 2 — MRICloud Sankey Diagram

- Visualizes brain volume hierarchy for Subject 127 (Type 1, Level 5)
- 6-level Sankey flow: ICV → Level 1 → Level 2 → Level 3 → Level 4 → ROI
- Data sourced from the MRICloud T1 volumetrics dataset
- Interactive diagram built with Plotly

## Tools Used

- Python, Pandas, NumPy
- Plotly (interactive visualizations)
- country_converter (region mapping)
- GitHub Pages (hosting)
