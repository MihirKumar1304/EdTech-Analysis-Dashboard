# EdTech-Analysis-Dashboard
## Project Objective
The objective of this project is to analyze and optimize the recorded lecture offerings of an EdTech startup by leveraging data from various online education platforms. The focus is on understanding category-wise trends, identifying high-demand course types, and examining viewer engagement patterns based on factors such as language preferences, subtitle availability, instructor quality, course duration, and skill variety. By uncovering key insights, the project aims to help the startup strategically expand its content library, improve learner engagement, and collaborate with top-rated instructors to enhance course effectiveness and market competitiveness.

## Dataset Used
- <a href="https://github.com/MihirKumar1304/EdTech-Analysis-Dashboard/blob/main/Online_Courses.csv">Dataset</a>

## Problem Statements
1. Examine the distribution of course types across categories to uncover trends and insights, enabling the client to strategically determine which course types to launch in specific categories for maximum impact and alignment with learner demand, also count the number of courses by category and sub-category.
2. Calculate the average number of views for each category, sub-category, and language to provide insights into viewer engagement patterns and inform strategic content development.
3. Identify the most commonly taught skills in today's educational landscape based on the data given based on category to ensure course offerings remain relevant and aligned with current job market demands.
4. What is the distribution of various Languages  in which a particular course is  created?
5. Determine the language preferences for each category based on viewer preferences, so that clients can optimise course accessibility and better align content with audience demand. Clients only want to analyse this data for the top 5 categories based on user preferences.
6. Investigate the relationship between the availability of subtitles and the number of views for courses to determine how subtitle options may impact viewer engagement and accessibility.
7. Who are the top three instructors in each category and subcategory based on ratings, consistently delivering high-quality content and effectively engaging learners, and how can they be approached for future course collaborations?
8. What is the impact of course duration on the number of views across different categories and subcategories, and do shorter courses (60 hours per month) or longer flexible courses (200 hours) perform better in terms of engagement, helping to optimize course length based on learner preferences and viewing habits?
9. How does the variety of skills offered within each category and subcategory influence viewer engagement, and what is the impact of breadth vs. depth of skills on the popularity of recorded lectures, identifying the key skill clusters that attract the most learners in each category?

- Dashboard Interaction <a href="https://github.com/MihirKumar1304/EdTech-Analysis-Dashboard/blob/main/EdTec%20Analysis.pbix">View Dashboard</a>

## Process
- Imported, reviewed, and cleaned the dataset in Power BI by handling missing values, removing duplicates, standardizing formats, and categorizing data based on key attributes like category, subcategory, instructor, views, duration, subtitles, and language.
- Created a bar chart to visualize the number of courses by category and subcategory, incorporated filters and slicers for dynamic exploration, and identified the most popular and underrepresented categories to guide strategic course launches.
- Aggregated total views, calculated the average views per course for each category, subcategory, and language, and built a heatmap to highlight engagement trends and provide insights into viewer behavior and content preferences.
- Extracted skills data from courses using text analysis, created a word cloud to highlight in-demand skills across categories, and provided insights into emerging trends to help the client align course offerings with market demand.
- Grouped courses by language, created a stacked bar chart to visualize language distribution across categories, and identified dominant languages to guide content development for localized learning experiences.
- Focused on the top 5 categories based on viewer preferences, compared viewership data across languages to determine language preferences, and optimized language offerings to align with audience demand and enhance accessibility.
- Analyzed the relationship between subtitle availability and total views using a scatter plot, identified whether courses with more subtitles had higher engagement rates, and provided insights on optimizing subtitles to enhance course reach and accessibility.
- Ranked instructors based on ratings and engagement metrics, created a static visual to highlight top-performing instructors in each category and subcategory, and identified key educators for potential collaborations and content creation.

## Dashboard
![Dashboard_Image](https://github.com/user-attachments/assets/47ef1cf9-e9fd-44ee-8a5e-98635dab7c7c)
