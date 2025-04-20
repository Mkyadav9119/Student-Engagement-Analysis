# Student-Engagement-Analysis

## Overview
This repository contains an analysis of student engagement and course performance based on randomly generated datasets. The datasets simulate student demographics, course activity, and feedback ratings. The goal of this analysis is to provide insights and actionable recommendations that can help enhance student engagement and improve course performance.

## Datasets
The following randomly generated datasets were used in the analysis:

1. **students.csv** - Contains simulated student demographic information (e.g., ID, Name, Age, Gender, Location, Enrolment Date).
2. **course_activity.csv** - Tracks simulated student course activity (e.g., Student ID, Course ID, Date, Time Spent, Completion Percentage).
3. **feedback.csv** - Contains simulated feedback data (e.g., Student ID, Course ID, Rating, Feedback Text).

## Analysis and Insights
The following key insights were derived from the data:

### 1. Engagement Varies by Course
- **Highest Engagement**: DM101 with an average of 102.43 minutes.
- **Lowest Engagement**: PY202 with an average of 93.90 minutes.
- **Business Implication**: The platform should analyze successful courses like DM101 to replicate their high engagement elements in other courses.

### 2. Age Group Impact on Engagement
- **Age Group 18-25**: Average engagement time of 100.76 minutes.
- **Age Group 26-35**: Average engagement time of 95.36 minutes.
- **Business Implication**: Content customization based on age group could boost engagement. For younger learners, more interactive and gamified content could be offered, while older learners might prefer structured and professional formats.

### 3. Location-Based Engagement Insights
- **Highest Engagement**: Kolkata (104.38 minutes), followed by Delhi (103.30 minutes).
- **Business Implication**: There are regional preferences that can be leveraged to improve engagement in cities like Chennai and Mumbai, where engagement is comparatively lower.

### 4. Correlation Between Completion Rate and Feedback Rating
- **Correlation**: -0.052, indicating a weak negative relationship between completion percentage and feedback ratings.
- **Business Implication**: Students completing courses may still provide poor feedback. Investigating areas of dissatisfaction despite course completion could improve overall satisfaction.

### 5. Top Student Segments Based on Engagement and Satisfaction
- **Top Students**:
  - Student_36: Time spent = 175 mins, Rating = 5, Age = 25, Location = Chennai.
  - Student_81: Time spent = 174 mins, Rating = 4, Age = 24, Location = Bangalore.
  - Student_64: Time spent = 173 mins, Rating = 4, Age = 30, Location = Bangalore.
- **Business Implication**: These students represent the ideal profile of highly engaged and satisfied learners. Personalizing learning paths for others based on their behavior could help replicate their success.

## Recommendations
Based on the analysis, the following data-driven recommendations are made:

### 1. Implement Personalization and Adaptive Learning Paths
- **Objective**: Customize learning experiences based on student demographics and engagement data.
- **Key Actions**:
  - Use student age, location, and past performance to recommend courses or adjust content delivery.
  - Provide dynamic difficulty adjustments based on student progress.
- **Expected Impact**: Increases engagement by offering tailored content that suits each student's learning style.

### 2. Gamify the Learning Experience with Rewards for Engagement
- **Objective**: Increase student motivation and interaction with courses through gamification.
- **Key Actions**:
  - Reward students with badges, leaderboards, and interactive challenges.
  - Offer real-world rewards (e.g., certificates, discounts) for achieving engagement milestones.
- **Expected Impact**: Higher engagement and consistent course completion. Gamification will keep students motivated throughout their learning journey.

### 3. Optimize Course Content Based on Feedback and Completion Data
- **Objective**: Continuously improve course content by leveraging feedback and engagement metrics.
- **Key Actions**:
  - Regularly assess feedback and completion rates to identify areas for improvement.
  - Conduct A/B testing to find the most engaging content formats (videos, quizzes, etc.).
  - Implement real-time content adjustments based on student data.
- **Expected Impact**: Improves course quality, leads to higher satisfaction, and reduces dropout rates.

## Visualizations
The following visualizations were created to support the analysis:

1. **Bar Chart**: Average Time Spent by Course.
2. **Box Plot**: Time Spent by Age Group.
3. **Bar Chart**: Average Feedback Rating by Course.
4. **Scatter Plot**: Completion Percentage vs. Feedback Rating.
5. **Line Plot**: Average Engagement Over Time.
6. **Heatmap**: Correlation Between Engagement Metrics.
7. **Heatmap**: Engagement Patterns by Course and Location (Demographic).

