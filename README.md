# The Effects of Anti-Anxiety Medicine on Memory Recall  

This project analyzes the effects of anti-anxiety medicine on memory recall when participants are primed with happy or sad memories. The analysis includes data preprocessing, exploratory data analysis (EDA), and statistical evaluations to uncover trends and insights.  

## Project Overview  
### Goals  
1. Assess the impact of different drugs and dosage levels on memory recall.  
2. Explore variations in responses between participants primed with happy or sad memories.  

### Drugs of Interest  
- **Alprazolam (Xanax, Long-term)**: Known as **Drug A**  
  - Dosages: [1 mg, 3 mg, 5 mg]  
- **Triazolam (Halcion, Short-term)**: Known as **Drug T**  
  - Dosages: [0.25 mg, 0.5 mg, 0.75 mg]  
- **Sugar Tablet (Placebo)**: Known as **Drug S**  
  - Dosages: [1 tab, 2 tabs, 3 tabs]  

## Experimental Setup  
- **Dosage Ratios**: 1:1 for consistency.  
- **Memory Priming**: Participants were primed with happy or sad memories 10 minutes prior to testing.  
- **Testing Duration**: Daily memory recall tested over one week to observe potential dependency effects.  

## Dataset  
The dataset contains:  
- **Demographics**: Age of participants.  
- **Groups**: Happy (H) or Sad (S).  
- **Drugs and Dosages**: Administered treatments.  
- **Memory Scores**: Measured before and after treatment.  
- **Memory Improvement**: Difference between post-treatment and pre-treatment scores.  

### Key Columns  
| Column Name          | Description                                           |  
|----------------------|-------------------------------------------------------|  
| `age`               | Participant's age                                     |  
| `Happy_Sad_group`   | Memory priming group (Happy - H, Sad - S)             |  
| `Drug`              | Administered drug (A, T, S)                           |  
| `Dosage`            | Dosage level administered                             |  
| `Mem_Score_Before`  | Memory recall score before treatment                  |  
| `Mem_Score_After`   | Memory recall score after treatment                   |  
| `Improvement`       | Improvement in memory recall (calculated)            |  

## Project Workflow  
### Data Preprocessing  
- Loaded and cleaned the data.  
- Handled missing values and anomalies.  
- Calculated memory improvement for each participant.  

### Exploratory Data Analysis (EDA)  
- Visualized distributions of key variables (`age`, scores, dosages).  
- Explored group-wise statistics for memory scores and improvements.  
- Identified trends in drug and dosage effects on memory improvement.  

### Statistical Analysis  
- Assessed the significance of memory improvement across drugs.  
- Analyzed the effects of dosage levels.  
- Compared results between Happy and Sad groups.  

### Visualizations  
- Histograms, scatter plots, and box plots for variable relationships.  
- Bar plots and line plots for trends in memory improvement.  
