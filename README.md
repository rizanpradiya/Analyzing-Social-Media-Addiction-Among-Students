# Analyzing Social Media Addiction Among Students

## Summary
This project analyzes survey data on students’ social media usage to understand how **social media addiction** relates to key aspects of student life:
- **Academic performance**
- **Mental health**
- **Sleep Quality**
- **Interpersonal relationships & conflcts over social media**

## Objective
Provide data-driven insights on the impact of social media addiction on students' academic performance, mental health, and relationships across demographic groups.

## Problem Statement
The true impact of social media addiction on students’ academic performance, mental health, sleep, and relationships is still unclear.

As a data analyst, this project aims to answer questions such as:
- How does the level of addiction vary across demographic groups?
- How is addiction related to **mental health**, **sleep quality**, and **conflicts over social media**?
- How addiction influences interpersonal relationships?

## Dataset
- `Students Social Media Addiction.csv`  
**Source:** Adil Shamim - *Students' Social Media Addiction vs Relationships* dataset on Kaggle ([link](https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships)). 
 
### Key Features

| Column                        | Description                                     |
|-------------------------------|-------------------------------------------------|
| Student_ID                    | Unique identifier for each student              |
| Age                           | Student age (integer)                           |
| Gender                        | Student gender (categorical)                    |
| Academic_Level                | Level of education (categorical)                |
| Country                       | Country of residence                            |
| Avg_Daily_Usage_Hours         | Average daily social media hours (float)        |
| Most_Used_Platform            | Primary social media (categorical)              |
| Affects_Academic_Performance  | Perceived academic impact (categorical)         |
| Sleep_Hours_Per_Night         | Average nightly sleep (float)                   |
| Mental_Health_Score           | Mental health metric (integer)                  |
| Relationship_Status           | Relationship status (categorical)               |
| Conflicts_Over_Social_Media   | Occurrence of conflicts (integer)               |
| Addicted_Score                | Composite addiction score (integer)             |

## Project Structure

```text
Analyzing Social Media Addiction Among Students/
│
├── README.md                                   
├── Portfolio_2_Social_Media.ipynb              # Main analysis 
├── Students Social Media Addiction.csv         # Dataset
├── Analyzing_Social_Media_Addiction.pdf        # Slides
└── Social_Media_Impact_Dashboard.pdf           # Dashboard

```

## Conlusion
1. **Mental Health Impact:**
There is an indicated negative relationship between Addicted Score and Mental Health Score. As the addiction level goes up, mental health tends to go down. Students with higher addiction scores are more likely to report worse mental health, while students with lower addiction scores tend to report better mental well being.

2. **Sleeping Quality Impact:**
Students with higher addiction levels usually sleep fewer hours per night, while those with lower addiction levels sleep longer. This suggests that higher social media addiction is linked to shorter and poorer sleep.

3. **Conflict over Social Media Impact:**
Students with higher addiction levels tend to experience more conflicts with others online, while students with lower addiction levels report fewer or almost no conflicts. This shows that higher addiction is associated with more social media drama.

## Suggestion

1. **Promote Awareness of Social Media Impact:**
Students are encouraged to reflect on their own social media use and recognize early signs of addiction, such as feeling more tired, stressed, or seeing a drop in academic performance.

2. **Set the Limits:**
Set a few simple rules can also enhance students to get better sleep and manage their emotion, such as no phone during homework/study, turn off all non-essential notifications, and avoid excessive late night scrolling.

3. **Provide Student Support:**
Schools/Colleges can provide counseling support for managing stress, establishing healthy sleep patterns and resolving online conflicts in a calm manner.