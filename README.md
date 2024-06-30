# Election2024-DataAnalysis
This repository contains scripts and analysis for the 2024 election results obtained from the [Election Commission of India](https://results.eci.gov.in).

## Key Analysis Points
1. **Top 10 Candidate and Constituecy with Highest Postal Impact**
2. **State dominance by Party**
3. **Top Candidates by Vote Share**
4. **Top Parties by Vote Share**
5. **Top 15 States with no. of Votes**
6. **Top 10 constituencies with the smallest winning margins.**
7. **States with Highest Postal Votes**
8. **Top Parties with Highest Number of Wins**
9. **Top Constituencies with the Highest Voter Turnout**
10. **Top 10 Constituencies with the Most Number of Candidates**

11. ## How to Run

### Web Scraping

1. Ensure you have Python installed on your machine.
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Open the web scraping notebook:
    ```bash
    jupyter notebook notebooks/WebScrape.ipynb
    ```
4. Run the cells in the notebook to perform web scraping.

### Data Analysis

1. Open the analysis notebook:
    ```bash
    jupyter notebook notebooks/Election-Analysis.ipynb
    ```
2. Run the cells to perform the data analysis.

## Requirements

- pandas
- numpy
- requests
- beautifulsoup4
- jupyter

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
