# Employee-Performance-Dashboard
Tableau Public Link: https://public.tableau.com/app/profile/rohini.tembhurnikar/viz/HRDashboard_17043083751860/MetrixOverview

## Objective:
This dashboard aims to analyze the performance of employees across various departments by evaluating key metrics such as salary, employee score, and demographics. The objective is to provide a comprehensive employee performance report card highlighting their rank within the department and job profile. This dynamic, multipage dashboard offers an in-depth evaluation of employee performance based on an Employee Score weighted by Productivity, Satisfaction, and Feedback Scores.
The Employee Score helps identify top performers and those in need of improvement, allowing for data-driven decision-making regarding promotions, training, and other employee development strategies. This dashboard can be used by HR teams and department heads to measure and track the overall performance of employees, uncover trends in satisfaction and feedback, and determine how well employees are meeting productivity expectations. The dashboard can also be leveraged for employee appraisals, performance reviews, and strategic workforce planning.

## Methodology:
Employee Score Calculation:
The Employee Score is calculated by combining three key performance metrics—Productivity, Satisfaction Rate, and Feedback Received. These metrics are weighted using the following formula:

### Employee Score
=
(
Weightage of Productivity
×
Productivity
)
+
(
Weightage of Satisfaction Rate
×
Satisfaction Rate
)
+
(
Weightage of Feedback
×
Feedback
)
Employee Score=(Weightage of Productivity×Productivity)+(Weightage of Satisfaction Rate×Satisfaction Rate)+(Weightage of Feedback×Feedback)
Weightages are assigned as follows: 40% to Productivity, 40% to Satisfaction Rate, and 20% to Feedback Received.

### Rank Display:
The Index() Function was used to calculate and display the rank of each employee based on their score within their department and job profile. This helps users understand how each employee compares to their peers.

### Dynamic Filtering:
The dashboard is interactive, allowing users to filter by various parameters such as department and job profile. This flexibility allows users to see detailed performance metrics specific to different sections of the organization.

# Learnings:
Creating Parameters for Sorting: I developed parameters to sort the data based on various metrics such as productivity, satisfaction, and feedback, both in ascending and descending order.

Advanced Table Creation: I used advanced techniques to create tables that provide detailed insights into individual employee performance, including departmental comparisons and overall ranks.

Dashboard Design & Interactivity: Focused on creating a user-friendly experience with dynamic elements to help users explore performance data interactively.
