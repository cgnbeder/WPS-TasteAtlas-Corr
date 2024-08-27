# Correlation Between Women's Rights Indexes and Countries' Cuisine Rankings

## Project Overview
This project explores the relationship between a country's Women's Peace and Security (WPS) index and its ranking in global cuisine. The analysis uses data from the Georgetown Institute for Women, Peace and Security (GIWPS) and TasteAtlas. The aim is to determine whether there is a significant correlation between a country's women's rights situation and the quality of its cuisine.

## Data Sources
- **WPS Index Data:** This dataset measures women's well-being across various dimensions such as inclusion, justice, and security.
- **TasteAtlas Rankings:** This dataset ranks countries based on the quality of their traditional dishes, ingredients, and culinary heritage.

## Methodology
The analysis involved categorizing countries based on their WPS Index scores and performing statistical tests (like the chi-square test) to determine if there is a significant relationship between these categories and the culinary rankings.

### Steps:
1. **Data Collection:** Gathered data from GIWPS and TasteAtlas for 95 countries.
2. **Data Categorization:** Grouped countries into different categories based on their WPS Index scores.
3. **Statistical Testing:** Applied chi-square tests to check for any significant correlation between WPS categories and culinary rankings.
4. **Visualization:** Created plots to visually explore the data and support the statistical findings.

## Key Findings
- The analysis did not reveal a strong statistical correlation between the WPS Index and culinary quality rankings.
- However, there was a weak, suggestive relationship that became more apparent when countries were grouped into fewer categories.
- The p-value approached statistical significance in the 3-category grouping, indicating a potential but not conclusive relationship.

## Visualizations
The following visualizations were used in the analysis:
- **WPS Index vs. Culinary Ranking:** Initial scatter plot to explore the potential correlation.
- **WPS by Regions:** Visual representation of how countries were categorized.
- **Minimum and Maximum WPS Index by Region:** Insights into the regional distribution of WPS scores.

## Conclusion
While the evidence does not strongly support a robust correlation between women's rights and culinary quality, the findings suggest that there might be a weak relationship worth further exploration. Simplifying the categorization of countries highlighted this subtle relationship, indicating that factors such as women's rights could influence the culinary landscape of a country.

## Future Work
Further research with more comprehensive data or additional variables may provide deeper insights into the connection between women's rights and culinary excellence. This project lays the groundwork for such studies, emphasizing the importance of considering social factors in culinary research.

## How to Use
To explore the data and analysis further, clone this repository and review the included Jupyter notebooks and visualizations. The full storytelling, along with the code used for analysis, can be found in the `WPS-TasteAtlas Corr` folder.
