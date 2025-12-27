# Google-Apps-Insights-Analytics-PowerBI

<div align="center">

<img src="https://static0.anpoimages.com/wordpress/wp-content/uploads/2022/06/what-is-google-play-hero.jpg" alt="drawing" width="500"/>

</div>


## Overview
Interactive Power BI dashboard analyzing 10.35K Google Play Store apps with 147 billion total installs. Visualizes market share, app success journey, category performance, and content ratings to drive strategic app development and marketing decisions.

## Dataset Overview
- **Size**: 10,350 apps after comprehensive data cleaning from the original Google Play Store dataset through Python preprocessing.
- **Source**: Cleaned dataset (`cleaned_googleplaystore.csv`) generated from `google-play-store-analytics.ipynb` with standardized formats and handled missing values.
- **Key Metrics**: Average rating of 4.19 across all apps, 147 billion total installs, 84% apps with positive rating trend, comprehensive review performance scoring.
- **Categories**: Multi-category analysis featuring GAME, COMMUNICATION, SOCIAL, PRODUCTIVITY, TOOLS, FAMILY, and other segments with detailed install breakdowns.
- **Success Segmentation**: Apps categorized into journey stages - All Apps (10K), With Reviews (94.29%), Popular 1K+ installs (74.13%), Successful 100K+ (44.16%), Top Tier 10M+ (7.26%), and Elite 100M+ (1.06%).
- **Content Ratings**: Distribution across Everyone (50.68%), Teen (20.83%), Mature 17+ (14.98%), Everyone 10+ (12.51%), Adults only 18+, and Unrated categories.
- **Install Scale**: Massive 147 billion total installs tracked across all categories providing comprehensive market coverage and performance benchmarking.

## Analysis & Dashboard
- **Data Preparation**:  
  - Processed raw Google Play Store data using Python in `google-play-store-analytics.ipynb`, cleaning duplicates, standardizing install ranges, converting sizes to MB.
  - Exported cleaned dataset to `cleaned_googleplaystore.csv` ensuring Power BI compatibility with proper data types and validated fields.
  - Created calculated columns and measures in Power BI for metrics like Review Performance Score, success tiers, and market share percentages.

- **Dashboard Design**:  
  - Built KPI cards displaying Total Apps (10.35K), Avg Rating (4.19), Total Installs (147bn), and Apps Rating percentage (84%) for executive summary.
  - Designed Market Share horizontal bar chart ranking categories by app count, with GAME, COMMUNICATION, and SOCIAL dominating the landscape.
  - Created innovative "App Success Journey" funnel visualization showing conversion rates from All Apps to Elite status, revealing only 1.06% reach 100M+ installs.
  - Developed Category Install Breakdown bar chart with variance indicators (Increase/Decrease arrows) showing total installs per category for performance tracking.

- **Advanced Visualizations**:  
  - Implemented scatter plot analyzing Reviews vs Rating correlation, identifying high-engagement apps with strong user satisfaction scores.
  - Built Size-Content Distribution stacked bar chart showing app size distribution across content ratings, with "Everyone" category leading at 450 apps.
  - Added interactive slicers for Content Rating filtering (Everyone, Teen, Mature 17+, Everyone 10+) enabling demographic-focused analysis.
  - Applied color-coded formatting with green/red indicators for performance trends and professional Power BI theme for dashboard consistency.

- **Key Insights**:  
  - Success funnel reveals significant drop-offs: 94% apps have reviews, but only 1% achieve Elite status, highlighting competitive market dynamics.
  - GAME category dominates both market share and total installs, validating gaming as primary growth opportunity in app ecosystem.
  - "Everyone" content rating represents 50.68% of apps, confirming family-friendly content as market standard and safest demographic target.
  - Review Performance Score enables quick identification of high-performing apps with strong user engagement and satisfaction metrics.

## How to Use
- Open the dashboard file:  
  - Download `Google Play Store Dashboard.pbix` from the repository
  - Open with Power BI Desktop (free version available from Microsoft)
  - Ensure `cleaned_googleplaystore.csv` is in the same directory or update data source path
- Navigate the dashboard:  
  - View top KPI cards for immediate market overview and key performance indicators
  - Analyze Market Share chart to understand category distribution and competitive landscape
  - Explore App Success Journey funnel to see conversion rates across different success milestones
  - Review Category Install Breakdown for detailed performance comparison with trend indicators
- Use interactive features:  
  - Click on any category in Market Share chart to filter entire dashboard for category-specific insights
  - Select Content Rating slicers (Everyone, Teen, Mature 17+) to analyze demographic segments
  - Hover over data points in scatter plot to see detailed app information including reviews and ratings
  - Use drill-through features to navigate from summary to detailed app-level analysis
- Refresh data:  
  - Run updated analysis in `google-play-store-analytics.ipynb` with new data
  - Generate fresh `cleaned_googleplaystore.csv` file
  - In Power BI, click "Refresh" in Home tab to update all visualizations automatically
  - Validate data refresh by checking Total Apps count and date stamp
- Export and share:  
  - Export visuals as images (right-click on any chart > Export data)
  - Publish to Power BI Service for web-based sharing with stakeholders
  - Schedule automatic data refreshes in Power BI Service for continuous monitoring
  - Create custom alerts for key metrics like rating changes or install milestones
- Best practices:  
  - Start with Success Journey funnel to understand overall market competitiveness
  - Compare your app category performance against market benchmarks in Category Install Breakdown
  - Use Content Rating filters to analyze target demographic performance
  - Monitor Review Performance Score to identify engagement opportunities and improvement areas

## Author & Contact
- Name: `Pratyush Puri`  
- Contact: `pratyushpuri17@gmail.com`  
- LinkedIn: [https://www.linkedin.com/in/pratyushpuri](https://www.linkedin.com/in/pratyushpuri)
