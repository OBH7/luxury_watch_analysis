# Luxury Watch Dataset Analysis

## Introduction
This project aims to explore the differences and similarities between luxury, mid-range, and non-luxury watches. The analysis focuses on the materials used in key components (lunette, case, bracelet) and the types of complications present in these categories. The dataset covers the 20 most popular watch brands, segmented into luxury, mid-range, and non-luxury based on a consensus of their brand status.

We performed statistical tests to understand patterns in materials and complications across these three categories, helping to highlight key trends in the watch industry.

## Dataset
The dataset used for this analysis can be found on Kaggle: Luxury Watch Listings Dataset:(https://www.kaggle.com/datasets/philmorekoung11/luxury-watch-listings). It contains detailed records of luxury, mid-range, and non-luxury watches, including attributes such as lunette material, case material, bracelet material, complications, and price.

## Methodology
The dataset was segmented into three categories: Luxury, Mid-Range, and Non-Luxury. Brands such as **Rolex**, **Patek Philippe**, and **Audemars Piguet** were classified as luxury. Brands like **Omega** and **TAG Heuer** were considered mid-range, while lesser-known or lower-priced brands were classified as non-luxury.

Four main attributes were analyzed:
- **Lunette Material** (e.g., Steel, Gold, Ceramic)
- **Case Material** (e.g., Steel, Platinum, Rose Gold)
- **Bracelet Material** (e.g., Steel, Crocodile-Leather, Platinum)
- **Complication** (e.g., Automatic, Quartz, Hand-Wound)

### Statistical Analysis
Chi-square tests were conducted to determine if there were statistically significant differences between the watch categories for each of the four attributes. Visualizations were created to illustrate these patterns.

## Key Findings

1. **Lunette Material**: 
   - Luxury watches favored high-end materials like White Gold (13.5%) and Yellow Gold (18.6%).
   - Steel was the most common material across all categories, particularly in non-luxury watches (70.4%).
   - Ceramic was found in all categories but most prominently in mid-range watches (17.8%).

2. **Case Material**:
   - Steel was dominant across all categories, though luxury watches exhibited more variety with Gold/Steel and Platinum.
   - Both mid-range and luxury watches used Titanium and Rose Gold, indicating some overlap in material choices.

3. **Bracelet Material**:
   - Steel was the most common bracelet material across all categories.
   - Luxury watches, however, featured more premium materials like Platinum and Rose Gold.
   - Crocodile-Leather, typically associated with luxury, was also found in mid-range watches.

4. **Complications**:
   - Automatic movements were the most common in both luxury (95.9%) and mid-range (78.9%) categories.
   - Quartz movements were more common in non-luxury watches (17.3%) but also appeared in mid-range watches (10.2%).

### Statistical Insights
Chi-square tests revealed significant differences between the three categories for each attribute:
- **Lunette Material**: Chi-square value = 19,765, p-value = 0.0
- **Case Material**: Chi-square value = 13,547, p-value = 0.0
- **Bracelet Material**: Chi-square value = 30,150, p-value = 0.0
- **Complications**: Chi-square value = 11,735, p-value = 0.0

These results indicate significant differences in material and complication choices between luxury, mid-range, and non-luxury watches. Notably, the use of materials like **Ceramic** and **Titanium** in both mid-range and luxury watches suggests a blurring of the line between these segments.

## Visualizations
To explore the visual findings in detail, please visit the interactive Tableau dashboard:

[Watch Sales Visualizations on Tableau](https://public.tableau.com/views/WatchSalesvisuals2/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Conclusion
This analysis revealed clear material preferences across different watch categories. Luxury watches unsurprisingly favor precious materials like Gold and Platinum, while mid-range watches show significant overlap with luxury, particularly in materials like Ceramic, Titanium, and Crocodile-Leather. Despite this overlap, Quartz movements remain a key differentiator for non-luxury watches, while automatic movements dominate the higher-end categories.

The findings suggest that mid-range brands are adopting elements traditionally associated with luxury, potentially blurring the lines between the two segments. The continued reliance on Quartz in non-luxury watches reinforces their distinction from the higher-end models.

## How to Use This Repo
1. **Data**: The cleaned dataset is provided in the repository for your reference.
2. **Visualizations**: Access the Tableau link above to interact with the visuals.
3. **Analysis**: Use the provided methodology and statistical insights for further investigation into watch material and complication trends.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
