# netflix-data-analysis-powerbi
Power BI dashboard analyzing 8,800+ Netflix titles with data cleaning, transformation, and interactive visualizations for content trends and insights

# Netflix Data Analysis Dashboard 🎬

Power BI dashboard analyzing 8,800+ Netflix movies and shows with comprehensive data cleaning and interactive visualizations.

## 🔗 View Dashboard
**Download Files:**
- 📊 [Power BI Dashboard (.pbix)]([netflix_dashboard.pbix](https://app.powerbi.com/groups/me/reports/5bbe67cf-012f-459b-a935-2052922515e1?ctid=6e5a6b5e-3c8f-4821-81c5-28885a52597c&pbi_source=linkShare))
- *Requires Power BI Desktop*
    
- 📄 [Dashboard PDF]
- [NETFLIX_DA_POWERBI.pdf](https://github.com/user-attachments/files/24136051/NETFLIX_DA_POWERBI.pdf)
-  - *View without Power BI*

## 📸 Dashboard Preview
![Dashboard Overview]
<img width="1291" height="725" alt="image" src="https://github.com/user-attachments/assets/02f5c7d2-1915-44f9-91bc-ecffa59ae561" />


## 🎯 Project Overview
Analyzed Netflix content catalog to uncover trends in:
- Content distribution by type (Movies vs TV Shows)
- Release trends over time
- Top genres and categories
- Country-wise content production
- Director and cast analysis
- Rating distributions

## 📁 Dataset
- **Source**: Netflix Titles Dataset
- **Size**: 8,800+ titles
- **Columns**: 12 attributes including title, director, cast, country, release year, rating, duration
- **Challenges**: Significant missing values in director, cast, and country columns

## 🧹 Data Cleaning & Transformation

### Power Query Transformations:
1. **Data Import**
   - Imported CSV data with proper text encoding
   - Set first row as headers
   - Profiled columns for data quality assessment

2. **Handling Missing Values**
   - **Director column**: Labeled missing values as "Director Missing"
   - Analyzed cast-director relationships to fill gaps where possible
   - Encoded nulls for better analysis

3. **Data Enrichment**
   - Split multi-value columns (genres, countries, cast)
   - Extracted year from date added
   - Created duration categories
   - Added calculated columns for analysis

4. **Data Quality**
   - Removed duplicates
   - Filtered unnecessary columns
   - Standardized text formats
   - Validated data types


## 📈 Key Insights
- 🎬 Movies make up ~70% of Netflix catalog
- 📅 Peak content addition: 2019-2020
- 🌎 USA, India, and UK are top content producers
- ⭐ TV-MA is the most common rating
- 📺 International Movies and Dramas dominate genres
- 📉 Significant missing director data (~30% of titles)

## 🛠️ Tools & Techniques
- **Power BI Desktop** - Dashboard creation and visualization
- **Power Query (M Language)** - Data cleaning and transformation
- **DAX** - Calculated columns and measures
- **Data Modeling** - Relationship management
- **Statistical Analysis** - Missing value handling strategies

## 💡 Technical Highlights

### Data Cleaning Strategy:
```
Missing Director Values:
1. Check if cast member is also director
2. Extract from title/description where possible  
3. Label remaining as "Director Missing" for transparency
```

### Power Query Steps:
- Column profiling with completeness bars
- Conditional column creation
- Text extraction and splitting
- Null encoding and imputation
- Date manipulation

## 💼 Business Applications
This dashboard helps:
- Content strategists identify trending genres
- Producers understand market gaps
- Marketing teams target specific demographics
- Analysts track content growth patterns

## 🎓 What I Learned
- Advanced Power Query data transformation techniques
- Handling missing data in real-world datasets
- Creating interactive and user-friendly dashboards
- Power BI best practices for performance
- Data storytelling through visualization

## 👤 Author
**Your Name**
- GitHub: [@4rthye](https://github.com/4rthye)
- LinkedIn: [arthyesridharan](https://linkedin.com/in/arthyesridharan)

## 📄 License
This project is open source and available under the MIT License.
```
dashboard
business-intelligence
data-transformation
