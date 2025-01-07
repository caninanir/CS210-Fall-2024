# CS 210 - Fall 2024 - Term Project
# Study Habits Analysis

## Description

This project analyzes my personal study habits by tracking the time I spend studying and sleeping each day. The aim is to gain insights into how I allocate my time through the day, identify patterns, and find areas for improvement.

---

## Table of Contents

- [Motivation](#motivation)
- [Tools](#tools)
- [Data Collection](#data-collection)
- [Data Processing](#data-processing)
- [Data Visualizations](#data-visualizations)
- [Data Analysis](#data-analysis)
  - [Total Study Time per Subject](#total-study-time-per-subject)
  - [Daily Study Patterns](#daily-study-patterns)
  - [Peak Study Hours](#peak-study-hours)
  - [Predictive Analysis](#predictive-analysis)
- [Findings](#findings)
- [Limitations and Future Work](#limitations-and-future-work)
  - [Limitations](#limitations)
  - [Future Work](#future-work)
- [Participation in Peer-Evaluation](#participation-in-peer-evaluation)
- [Repository Structure](#repository-structure)
- [Contact](#contact)

---

## Motivation

While striving for being able to graduate, I wanted to understand how effectively I use my time. By analyzing my study habits, I aim to optimize my schedule, focus on problems that need more attention, and enhance my overall academic performance. As I suffer from ADHD, I have very sporadic study and sleep schedules. Most of my days I do not even study at all outside going to classes, but when deadlines come around, I cram a good 10-12 hours and pull an all-nighter just to make it through. This is especially true for exams as I cannot recall a single time I had a good night's sleep before an exam. I am hoping to change this.

---

## Tools

I utilized the following tools:
- **Python 3.8**
- **Jupyter Notebook**: For coding and documentation.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Data visualization.
- **Seaborn**: Statistical data visualization.
- **NumPy**: Numerical operations.
- **Scikit-learn**: Machine learning models.

---

## Data Collection

- **Duration**: Around 30 days.
- **Method**: Manually recorded the time spent sleeping and studying each day.
- **Data Fields**:
  - `Date`: The date of that day.
  - `Wake up time`: What time I woke up that day.
  - `Study_time`: Duration of study in hours.
  - `Sleep_time`: Duration of sleep in hours.
  - `Other_time`: The remaining hours of the day where I did not study nor sleep.
  - `Midterm`: Marks days where I had exams.

---

## Data Processing

- No need as I manually logged the data. Some days with missing entries were removed.

---

## Data Visualizations

- **Bar Charts**: Total study time, sleep time, and other time visualized.
- **Line Plots**: Daily total study time over the month, tracking spikes during exam periods.
- **Heatmaps**: Study time distribution by day of the week or deadline.
- **Scatter Plots**: Relationship between day number and time spent. Also, study time vs. sleep time.
- **Regression Lines**: Predictive analysis for future study times (though limited by sporadic data).

Visualizations will be available in the `figures` folder. (TO BE ADDED)

---

## Data Analysis

### Total Study Time

Calculated total hours spent on study and sleep over the month to identify areas needing improvement.

### Daily Study Patterns

Analyzed daily variations in study time, observing trends and fluctuations in habits. Noted that days leading up to deadlines had high study times, while other days were relatively unproductive.

### Peak Study Hours

Identified peak study times, with most sessions occurring in the late afternoon or evening. The erratic schedule is consistent with ADHD tendencies, as hyperfocus often drives bursts of productivity.

### Predictive Analysis

Attempted to use linear regression for predicting study hours based on deadlines. Results were inconclusive due to the sporadic nature of the data, a hallmark of ADHD-related time management challenges.

---

## Findings

- **Study vs. Sleep Trade-Off**: High study hours during deadlines were achieved at the cost of significantly reduced sleep (average 3.83 hours on deadline days).
- **Inconsistent Productivity**: Average study time on non-deadline days was only 1.30 hours, highlighting a lack of consistent effort.
- **Deadlines as Motivation**: Deadlines were the primary driver of productivity, often leading to unhealthy cramming sessions.
- **ADHD Impact**: The findings align with ADHD patterns of procrastination followed by intense hyperfocus under pressure.

---

## Limitations and Future Work

### Limitations

1. **Small Sample Size**: Data collected over only 30 days limits generalizability.
2. **Self-Reported Data**: Manual logging may introduce errors or biases.
3. **Limited Context**: External factors (e.g., mental health, academic workload) were not accounted for.

### Future Work

1. **Longer Data Collection**: Extend the tracking period to an entire semester for more robust insights.
2. **Automated Data Logging**: Use tracking apps or wearables for objective data collection.
3. **Additional Metrics**: Include data on physical activity, mental health, and academic performance.
4. **Intervention Testing**: Experiment with structured schedules and measure improvements.

---

## Participation in Peer-Evaluation

I participated in the peer-evaluation process by reviewing fellow students' projects and providing constructive feedback. This allowed me to learn from their approaches to similar challenges.

---

## Repository Structure

- `data/`: Contains data files.
- `scripts/`: Python scripts used for analysis.
- `figures/`: Visualizations generated from the analysis.
- `README.md`: Project description and plan.

---

## Contact

For inquiries, contact me at **can.inanir@sabanciuniv.edu**.

---
