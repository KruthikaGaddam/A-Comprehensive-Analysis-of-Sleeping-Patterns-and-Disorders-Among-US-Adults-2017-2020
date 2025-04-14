# 🛌 A Comprehensive Analysis of Sleeping Patterns and Disorders Among U.S. Adults (2017–2020)

This project explores sleep patterns and common sleep disorders among U.S. adults using nationally representative data from NHANES (2017–2020). We investigated social jetlag, sleep debt, and their associations with snoring, sleepiness, and other disturbances, drawing attention to lifestyle-driven discrepancies in weekday vs. weekend sleep behavior.

## 📌 Project Goals

- Analyze differences in sleep duration and timing between weekdays and weekends
- Estimate average sleep debt and social jetlag in the population
- Investigate relationships between sleep regularity and indicators like daytime sleepiness, snoring, and trouble sleeping

## 📊 Key Findings

1. 📈 **Identified average sleep debt of 0.5 hours**, with most individuals sleeping **~7.6 hrs on weekdays vs. ~8.3 hrs on weekends**, revealing clear behavioral compensation patterns.

2. 🕒 **Detected over 1 hour of social jetlag** (difference in average wake time), supporting previous research linking inconsistent sleep cycles to health risks.

3. 📉 **Multiple logistic regression showed significant association** between trouble sleeping and factors like **snoring, snorting**, and **excessive daytime sleepiness** — pointing to critical symptoms healthcare providers can monitor.

## 🧰 Tools & Methods

- **Language**: R (RStudio)
- **Statistical Techniques**: Time-series analysis, Kruskal-Wallis test, Multiple Linear & Logistic Regression, Data Visualization
- **Data Source**: NHANES Sleep Disorders Dataset (10,000+ respondents)
- **Feature Engineering**: Calculated sleep debt, social jetlag, sleep regularity

## 🔍 Limitations & Considerations

- Data was **self-reported**, which introduces memory bias and limits generalizability.
- Outliers were retained due to the subjective nature of sleep data (e.g., 3–14 hour sleep ranges).
- Non-normal distributions required non-parametric testing (Kruskal-Wallis) over traditional ANOVA.
- Sleep duration recorded as time strings (hh:mm) introduced complexity in analysis.

## 📈 Impact

While the findings should be interpreted with caution, they **provide insight into population-level sleep behaviors**. This can help inform:
- Public health recommendations for consistent sleep schedules
- Screening protocols for identifying sleep-related disorders
- Future studies leveraging passive tracking or clinical-grade sleep data

## 👩‍💻 Authors

- Kruthika Gaddam  
- Likith Sai Gowni  
- Kavya Gustala  
- Mounisha Madala  
- Sowmya Papagari
