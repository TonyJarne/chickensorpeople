# Chickens vs People in Europe 🐔

## Overview

This project analyzes and visualizes the number of chicken and poultry populations across European countries compared to their human populations. The analysis reveals that **39 European countries have more chickens than people**.

## Key Findings

| Metric | Value |
|--------|-------|
| **Total European Countries** | 39 countries |
| **Total Chickens** | 1.4+ billion |
| **Country with Highest Ratio** | Moldova (13.65 chickens per person) |
| **Second Highest** | Belarus (12.71 chickens per person) |
| **Data Year** | 2024 |

## Top 10 Countries by Chickens-to-People Ratio

| Rank | Country | Chickens | Population | Ratio |
|------|---------|----------|-----------|-------|
| 1 | Moldova | 48,451,000 | 3,550,000 | 13.65:1 |
| 2 | Belarus | 120,516,000 | 9,480,000 | 12.71:1 |
| 3 | Poland | 244,680,000 | 36,800,000 | 6.65:1 |
| 4 | Cyprus | 4,655,000 | 858,000 | 5.43:1 |
| 5 | Netherlands | 89,231,000 | 17,700,000 | 5.04:1 |
| 6 | Ukraine | 173,725,000 | 36,500,000 | 4.76:1 |
| 7 | Russia (European part) | 507,994,000 | 110,000,000 | 4.62:1 |
| 8 | Portugal | 44,098,000 | 10,400,000 | 4.24:1 |
| 9 | Belgium | 48,754,000 | 11,690,000 | 4.17:1 |
| 10 | Spain | 193,476,000 | 48,100,000 | 4.02:1 |

## Data Sources

### Chicken/Poultry Population
- **Source**: FAOSTAT (Food and Agriculture Organization of the United Nations)
- **Database**: Live Animal Stocks
- **Year**: 2024
- **Coverage**: 190 countries and territories
- **Official Link**: https://www.fao.org/faostat/en/

### European Population (EU & EEA Countries)
- **Source**: Eurostat (Statistical Office of the European Commission)
- **Database**: Demographic Statistics
- **Year**: 2024
- **Official Link**: https://ec.europa.eu/eurostat/

### United Kingdom Population
- **Source**: ONS (Office for National Statistics)
- **Report**: Population estimates for the UK, England, Wales, Scotland and Northern Ireland
- **Year**: Mid-2024 Estimates
- **Value**: 69,300,000 inhabitants
- **Official Link**: https://ons.gov.uk/

## Project Structure

```
chickens-vs-people/
├── README.md                 # This file
├── DATA_SOURCES.md          # Detailed information about data sources
├── ANALYSIS.md              # Detailed analysis and insights
├── index.html               # Interactive visualization (web)
├── data/
│   ├── chickens_data.json   # Raw chicken population data
│   └── population_data.json # Raw population data
├── docs/
│   ├── METHODOLOGY.md       # Methodology for data collection and analysis
│   └── LIMITATIONS.md       # Data limitations and considerations
└── images/
    └── comparison_chart.png  # Static visualization

```

## Interactive Visualization

Open `index.html` in your web browser to view the interactive visualization with:
- Searchable table of all 39 countries
- Real-time filtering
- Sortable columns
- Responsive design for mobile devices

## Running Locally

1. Clone the repository:
```bash
git clone https://github.com/yourusername/chickens-vs-people.git
cd chickens-vs-people
```

2. Open the visualization:
```bash
# Simply open the HTML file in your browser
open index.html
# or
start index.html
```

No dependencies or installation required!

## Key Insights

### Why so many chickens?

1. **Agricultural Production**: European countries have significant poultry industries for meat and egg production
2. **Large-scale Farming**: Industrial chicken farms contain millions of birds
3. **Food Security**: Chicken is a primary protein source in European diets
4. **Economic Importance**: Poultry production is a substantial agricultural sector

### Regional Patterns

- **Eastern Europe**: Higher ratios (Moldova, Belarus, Ukraine, Poland)
- **Western Europe**: Lower but still above 1:1 (France, Germany, Spain, Italy)
- **Nordic Countries**: Moderate ratios (Sweden, Denmark, Finland, Norway)
- **Southern Europe**: Varied ratios (Spain high, Greece, Cyprus, Portugal moderate)

## Methodology

For detailed information about how the data was collected, processed, and analyzed, please see [METHODOLOGY.md](docs/METHODOLOGY.md).

## Data Limitations

Important considerations and limitations are documented in [LIMITATIONS.md](docs/LIMITATIONS.md).

## Contributing

Contributions are welcome! Please feel free to:
- Report issues or suggest improvements
- Add additional analysis or visualizations
- Update data for newer years
- Improve documentation

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Citation

If you use this data or analysis in your work, please cite:

```
Chickens vs People in Europe (2024)
Data sources: FAOSTAT (FAO), Eurostat (European Commission), ONS (UK)
Retrieved from: https://github.com/yourusername/chickens-vs-people
```

## Related Projects

- [FAOSTAT - Food and Agriculture Organization Statistics](https://www.fao.org/faostat/)
- [Eurostat - Statistical Office of the European Commission](https://ec.europa.eu/eurostat/)
- [World Animal Foundation - Global Chicken Distribution](https://worldanimalfoundation.org/)

## Questions & Contact

For questions or more information, please open an issue on GitHub or contact the project maintainer.

---

**Last Updated**: November 2024
**Data Year**: 2024
**Total Countries Analyzed**: 39 European countries
