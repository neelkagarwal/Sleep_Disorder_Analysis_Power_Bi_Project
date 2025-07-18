# 💤 Sleep Disorder Analysis Power BI Dashboard

## 1. Headline  
A visually engaging dashboard designed to analyze patterns of sleep disorders like insomnia and sleep apnea, breaking down health, lifestyle, and demographic factors across age, BMI, gender, and occupation.

---

## 2. Purpose  
This dashboard explores the prevalence and characteristics of sleep disorders, helping users understand how factors like stress, sleep quality, BMI, and physical activity relate to conditions like insomnia and sleep apnea. Built for health analysts, researchers, and public health advocates.

---

## 3. Tech Stack  
The dashboard was built using the following tools and technologies:  
• 📊 **Power BI Desktop** – Main visualization and reporting platform  
• 🔄 **Power Query** – Data transformation layer for cleaning and reshaping raw data  
• 🧠 **DAX** – For calculated metrics, conditional visuals, and filters  
• 🗂️ **Data Modeling** – Relationships between tables (disorders, demographics, lifestyle) to support drill-downs and filters  
• 📁 **File Format** – `.pbix` for the dashboard, `.png` for screenshots

---

## 4. Data Source  
The dataset is a structured CSV file consisting of personal, lifestyle, and medical information of individuals, including:  
- Sleep disorder diagnosis (insomnia, sleep apnea, or none)  
- Sleep duration, sleep score, and stress level  
- Age, gender, BMI category, and occupation  
- Step count per day
  
This data was modeled to enable filtering and comparative analysis across multiple dimensions.

---

## 5. Features

### • Business Problem  
Sleep disorders impact mental and physical health significantly, but patterns across population segments are hard to track without structured analysis.  
Questions like:  
- Are males or females more affected by insomnia?  
- How do stress and sleep quality vary with age?  
- What’s the correlation between occupation and physical activity or sleep disorders?

These are some of the questions that are difficult to answer without interactive insights!

---

### • Goal of the Dashboard  
To build an interactive, user-friendly Power BI report that:  
- Compares insomnia vs. sleep apnea prevalence and characteristics  
- Provides demographic and lifestyle breakdowns by gender  
- Helps identify patterns in stress, steps, and BMI linked to sleep disorders  
- Offers an intuitive way to explore sleep health across age groups

---

### • Walkthrough of Key Visuals  

- 🛏️ **Sleep Disorder Cards (Top Section)**  
  - **Insomnia & Sleep Apnea** side-by-side  
  - Gauge for average sleep score  
  - Pie chart for case count (%)  
  - Average sleep duration (numeric)

- 📈 **Sleep Quality vs. Stress Level by Age (Line Charts)**  
  Shows trends across age groups—visually comparing how sleep quality and stress evolve with age for each disorder

- 📊 **BMI Category Distribution (Stacked Bar Chart)**  
  Number of individuals segmented by BMI (Normal, Underweight, Overweight, Obese)

- 👣 **Average Steps by Occupation (Column Charts)**  
  Steps taken by individuals in roles like Manual Labor, Office Worker, Student, and Retired shows how physical activity varies with profession

- 🎯 **Sleep Disorder Tracker (Center Panel)**  
  Pie chart of total sleep disorder vs. non-disorder cases  
  Displays overall **percentage** of population affected  
  Gender-based filter buttons below (👩 Female, 👨 Male) to toggle all visuals by gender

---

### • Business Impact & Insights  
- **Public Health Awareness**: Shows patterns that could guide healthcare campaigns  
- **Demographic Targeting**: Helps identify age/gender groups most at risk  
- **Lifestyle Intervention**: Reveals correlation between daily activity and sleep health  
- **Policy & Strategy**: Useful for researchers, hospitals, and HR wellness programs

---

## 6. Screenshot / Demo  
![Dashboard Preview](Sleep_Analysis_Project_Screenshot.png)  
> Dashboard showing side-by-side analysis of insomnia and sleep apnea across demographics and lifestyle factors.

> [▶️ Watch Demo Video]()


