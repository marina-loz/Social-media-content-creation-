# 📊 Social Buzz: Content Analysis Project

## 📝 Objective
Analyze user interactions on the Social Buzz platform to identify the top-performing content categories. This analysis will help inform content strategy and optimize engagement.

## ❓ Key Questions
- What are the top 5 most popular content categories?
- How do reactions vary across these categories?
- Which month had the most user activity?

## 📊 Data
- **Content Table**: Details of posts, including content type and category.
- **Reactions Table**: User reactions to content.
- **Reaction Types Table**: Sentiment and score for each reaction type.

## 🧠 Approach
1. **Data Cleaning**: Removed missing data, renamed columns, and formatted datasets.
2. **Merging Tables**: Combined data from the content, reactions, and reaction types tables.
3. **Top Categories**: Grouped and sorted by reaction scores to identify the top 5 categories.
4. **Visualizations**: Created pie charts and bar plots to visualize category distribution and trends.

## 📈 Results
- **Top 5 Content Categories**: Travel (53,935), Science (53,657), Healthy Eating (52,745), Animals (52,443), Cooking (49,681).
- **Month with Most Posts**: January.

## 🚀 Conclusion
Social Buzz should focus on top-performing categories like Travel, Science, and Healthy Eating. These insights will help tailor content strategies and improve user engagement.

## 🛠️ Tools & Libraries
- **pandas**: Data analysis
- **seaborn**, **matplotlib**: Data visualization
- **openpyxl**: Exporting results to Excel
