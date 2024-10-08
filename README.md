# 🌍 World Happiness Report Analysis 😊

## 📝 Project Overview
This project analyzes the **World Happiness Report** data to understand the factors influencing happiness across different countries and regions over time. The analysis focuses on the relationship between happiness (Life Ladder score) and key factors like **GDP**, **social support**, **freedom**, and **healthy life expectancy**. 

The project explores global trends, country comparisons (e.g., Portugal vs. Germany), and regional differences to provide a comprehensive view of the determinants of happiness.

## 📊 Dataset
- **World Happiness Report**: This dataset contains happiness scores (Life Ladder) for various countries from 2005 to 2022, along with factors such as:
  - 🌍 **GDP per capita (log)**: A measure of economic prosperity.
  - 🤝 **Social Support**: The availability of social support networks.
  - 🏥 **Healthy Life Expectancy**: Average life expectancy at birth.
  - 🗽 **Freedom to Make Life Choices**: Perception of freedom in making life decisions.
  - 💌 **Generosity**: Contributions to charity and generosity.
  - 🏛️ **Perceptions of Corruption**: Public perceptions of corruption in government.

## 🔑 Key Analyses and Insights

### 1. **Top 15 Happiest Countries in 2022** 🏆
- **Analysis**: A barplot of the top 15 happiest countries in 2022 based on their Life Ladder scores.
- **Insight**: Countries like **Finland**, **Denmark**, and **Switzerland** rank consistently high in happiness, likely due to their strong social support systems, high GDP per capita, and good governance.

### 2. **🇵🇹 Portugal vs. 🇩🇪 Germany**
- **Analysis**: Comparative analysis of happiness (Life Ladder), GDP per capita, and healthy life expectancy for Portugal and Germany over time.
- **Insight**: Germany has consistently higher happiness scores and GDP per capita compared to Portugal. However, Portugal maintains moderate happiness levels, suggesting that factors beyond GDP, such as lifestyle and social cohesion, contribute to well-being.

### 3. **Happiness vs. Freedom to Make Life Choices** 🗽😊
- **Analysis**: A scatter plot with a regression line showing the relationship between **happiness** and **freedom to make life choices** for the year 2022. Pearson correlation coefficient was calculated to quantify the relationship.
- **Insight**: A positive correlation (\( r = 0.64 \)) was found between happiness and freedom, suggesting that countries where individuals feel they have greater personal freedom tend to be happier.

### 4. **Regional Happiness Trends Over Time** 🌍📈
- **Analysis**: A line plot comparing happiness trends across different regions (e.g., Western Europe, Sub-Saharan Africa, South Asia) from 2005 to 2022.
- **Insight**: **Western Europe** and **North America** consistently rank high in happiness, while regions like **Sub-Saharan Africa** and **South Asia** lag behind. These differences can be attributed to economic disparities, governance, health, and social support.

### 5. **Correlation Between Key Factors** 📊
- **Analysis**: Correlation analysis between happiness (Life Ladder) and key factors such as **GDP**, **social support**, **freedom**, and **healthy life expectancy**.
- **Insight**: Strong correlations were found between happiness and factors like **social support** and **freedom**. This highlights the importance of not only economic prosperity but also social and personal well-being factors in determining happiness.

## 🛠️ Technologies and Tools Used
- **Python** 🐍: For data analysis and visualization.
- **Libraries**: 
  - 📊 **Pandas**: For data manipulation.
  - 🎨 **Seaborn** and **Matplotlib**: For data visualization.
  - 🤖 **Scikit-learn**: For clustering and modeling (if further analysis is added).

  ## 💡 Key Insights Summary
- **🗽 Freedom and Happiness**: Countries with greater freedom in life choices tend to be happier, demonstrating the importance of autonomy for well-being.
- **💰 GDP is Important, But Not Everything**: While GDP per capita is correlated with happiness, other factors like social support and health also play significant roles.
- **🌍 Regional Disparities**: Western Europe leads in happiness, while Sub-Saharan Africa and South Asia face challenges due to lower economic development, governance, and health-related issues.
- **🇵🇹 Portugal vs. 🇩🇪 Germany**: Germany's higher GDP and happiness scores contrast with Portugal's more moderate levels, but Portugal still maintains stable happiness, likely due to non-economic factors.
- **🤝 Social Support**: Countries with stronger social support systems exhibit higher happiness levels, emphasizing the role of relationships and community in well-being.

## 🔮 Future Work
- **Predictive Modeling**: Develop a model to predict happiness scores based on key factors like GDP, freedom, and social support.
- **Clustering Analysis**: Use clustering techniques to group countries with similar happiness profiles and explore patterns among these groups.
- **Generosity and Corruption**: Further explore the impact of generosity and perceptions of corruption on happiness across countries.

## 🎯 Conclusion
This project demonstrates the multi-faceted nature of happiness, where economic factors like GDP are important, but social support, personal freedom, and health are equally, if not more, critical in determining well-being. By comparing countries and regions, this analysis provides valuable insights into the global state of happiness and the factors that drive it.

## 📂 Dataset Source
The **World Happiness Report** dataset used in this project is sourced from **Kaggle**. You can find the dataset [here](https://www.kaggle.com/unsdsn/world-happiness).
