# Olympics-Data-Analysis-Project
Unified Mentor Internship 2025

🔍 Project Overview (TL;DR)
Goal: Analyze Olympics data (from 1896 to recent games) to uncover insights about countries, athletes, events, medals, etc., and build visualizations + maybe ML predictions (like which country might win most medals next time).

💼 Key Parts to Include

**1. Problem Statement**

The Olympic Games represent the pinnacle of global sporting events, uniting athletes from all nations and disciplines. With data spanning more than a century, this project aims to analyze trends and patterns in Olympic participation and performance using historical data.

The core objective is to uncover insights such as:

Which countries have historically dominated the Olympics?

What demographic patterns exist among medal-winning athletes?

Which sports bring in the most medals?

Is there a trend in participation by gender?

Can we predict medal outcomes based on athlete attributes?

**2. Dataset**
Use Kaggle Olympics Dataset.

Typically includes: Name, Sex, Age, Height, Weight, Team, NOC, Games, Year, Season, City, Sport, Event, Medal

**3. Data Cleaning & Preprocessing**
Handle missing values (Age, Height, Weight often have nulls).

Standardize country names if needed.

Remove duplicates if any.

Format Medal data (Gold, Silver, Bronze, None).

**4. Exploratory Data Analysis (EDA)**
Use Python with Pandas, Matplotlib, Seaborn, or Plotly.

Trend of total medals over the years

Top countries by medal count

Most successful athletes

Distribution of athletes by gender

Sports that are more gender balanced

Average age/height/weight of medalists per sport

**5. SQL Analysis**
Write queries for:

Total medals by country/year

Top athletes from a specific country

Count of athletes by sport/gender

**6. ML Model (Optional but🔥)**
Predict if an athlete will win a medal (classification)

Use Logistic Regression, Random Forest, etc.

Features: Age, Gender, Height, Weight, Country, Sport

Label: Medal (Yes/No)
