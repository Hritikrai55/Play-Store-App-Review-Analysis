# Play Store App Review Analysis

An in-depth **Exploratory Data Analysis (EDA)** project analyzing Google Play Store apps data to uncover insights about app features, market trends, and factors influencing app success.

## 📊 Project Overview

This project analyzes Google Play Store applications data to provide actionable insights for app developers and businesses. With Android holding approximately 85% of the mobile device market, understanding the Play Store ecosystem is crucial for app success.

The analysis explores key factors responsible for app engagement and success, helping developers make data-driven decisions to capture the Android market effectively.

## 🎯 Objectives

- Analyze app distribution across different categories
- Understand user preferences and installation patterns  
- Identify factors that influence app ratings and success
- Provide insights for app developers and stakeholders
- Explore relationships between app features (size, price, category) and user engagement

## 📁 Project Structure

```
Play-Store-App-Review-Analysis/
├── Play_Store_App_Review_Analysis.ipynb    # Main analysis notebook
├── Play Store Data.csv                     # Primary dataset with app details
├── User Reviews.csv                        # User reviews dataset  
└── README.md                              # Project documentation
```

## 📋 Dataset Description

### Primary Dataset: Play Store Data.csv
- **Size**: ~1.36 MB with 10,841+ records
- **Features**: 13 columns including:
  - `App`: Application name
  - `Category`: App category (Family, Game, Tools, etc.)
  - `Rating`: User rating (1-5 scale)
  - `Reviews`: Number of user reviews
  - `Size`: App size (MB/KB)
  - `Installs`: Number of installations
  - `Type`: Free or Paid
  - `Price`: App price ($ for paid apps)
  - `Content Rating`: Target audience
  - `Genres`: App genre classification
  - `Last Updated`: Last update date
  - `Current Ver`: Current app version
  - `Android Ver`: Minimum Android version requirement

### Secondary Dataset: User Reviews.csv
- **Size**: ~7.67 MB
- Contains detailed user reviews and sentiment data

## 🔧 Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Play-Store-App-Review-Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Play-Store-App-Review-Analysis
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Play_Store_App_Review_Analysis.ipynb
   ```

## 📈 Key Analysis & Insights

### 1. **Category Distribution**
- **Family** category has the highest number of apps
- **Game** category follows as the second most popular

### 2. **User Engagement Patterns**
- **Game** apps have the highest installation rates
- **Communication** apps rank second in user installations
- Users show strong preference for gaming and communication applications

### 3. **Rating Analysis**
- Most apps maintain ratings between **4.0 - 4.7**
- **Health & Fitness** and **Books & Reference** categories show highest quality with 50%+ apps rated above 4.5
- **Dating** category shows lower ratings compared to average

### 4. **Data Quality Insights**
- Identified and handled 1,474 missing rating values
- Removed apps with invalid ratings (>5.0)
- Standardized data formats for size, price, and installation counts

## 🔍 Analysis Workflow

1. **Data Import & Exploration**
   - Loading datasets and initial inspection
   - Understanding data structure and types

2. **Data Cleaning & Preprocessing**
   - Handling missing values using median imputation
   - Converting string formats to numerical values
   - Removing duplicates and invalid entries
   - Standardizing size units (MB/KB conversion)

3. **Exploratory Data Analysis**
   - Category-wise app distribution analysis
   - Installation patterns and user preferences
   - Rating distribution and quality assessment
   - Correlation analysis between features

4. **Data Visualization**
   - Count plots for categorical distributions
   - Bar plots for comparative analysis
   - Box plots for rating distributions
   - Trend analysis charts

## 💡 Business Impact

### Positive Insights:
- **Game and Communication apps** show highest user engagement
- **Health & Fitness** category demonstrates excellent user satisfaction
- Most apps maintain good quality standards (4+ ratings)

### Recommendations:
- Focus on **Game** and **Family** categories for maximum reach
- Prioritize **Health & Fitness** for quality-focused development
- Consider **Communication** tools for high user engagement

## 👨‍💻 Author

**Hritik Rai**
- Individual Contribution Project
- Data Analysis & Visualization Specialist

## 📝 Certification

- 🎓 [View Certification](https://verified.sertifier.com/en/verify/48599463874874/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📞 Contact

For any questions or suggestions, please feel free to reach out!
- 🌐 [LinkedIn Profile](https://www.linkedin.com/in/hritik-rai-/)

---

*This project demonstrates comprehensive EDA techniques and provides valuable insights for the mobile app development industry.*
