# Pandas Master Practice Questions


## A. Exploration

1. Load the CSV.
2. Display first 10 rows.
3. Display last 7 rows.
4. Find shape.
5. List columns.
6. Check dtypes.
7. Use info().
8. Use describe().
9. Count missing values per column.
10. Find duplicate rows.

## B. Selection & Filtering

11. Select only name, cgpa, city.
12. Students with CGPA > 8.5.
13. Attendance < 75.
14. Placed students from Chennai.
15. CSE students with CGPA > 8 and attendance > 85.
16. Students not from Bangalore.
17. Students with internship salary >= 25000.
18. Female students with no backlogs.
19. Students having exactly 0 projects.
20. Students whose city is null.

## C. Cleaning

21. Remove duplicates.
22. Fill missing CGPA with mean.
23. Fill missing attendance with median.
24. Fill missing city with 'Unknown'.
25. Replace missing internship salary with 0.
26. Drop rows where department is missing.
27. Find percentage of missing values.
28. Convert placement_status to category.
29. Rename internship_salary to stipend.
30. Reorder columns.

## D. Sorting & Unique

31. Sort by CGPA descending.
32. Sort by city then attendance.
33. Unique departments.
34. Unique cities.
35. Students per city using value_counts().
36. Students per department.

## E. GroupBy

37. Average CGPA by city.
38. Average CGPA by department.
39. Maximum attendance by department.
40. Average study hours by placement status.
41. Count students by gender.
42. Total stipend by city.
43. Average projects by department.
44. Multiple agg: mean/max/min CGPA per city.
45. Average CGPA grouped by city and gender.
46. Department with highest average attendance.

## F. String

47. Uppercase names.
48. Lowercase names.
49. Names containing 'a'.
50. Names starting with 'A'.
51. Length of each name.
52. Replace '&' in department names if any.

## G. New Columns

53. Create cgpa_percentage=cgpa*10.
54. Create is_good_student (cgpa>=8).
55. Create total_score = cgpa*10 + attendance.
56. Create experience_level from projects (0-1 Beginner,2-3 Intermediate,4+ Advanced).
57. Create has_backlog boolean.

## H. apply()

58. Create performance labels using apply().
59. Map placement to Yes/No.
60. Append ' hrs' to study_hours.
61. Cap attendance at 100 using apply().
62. Convert stipend 0 to 'No Internship' in a new column.

## I. EDA

63. Highest average CGPA city.
64. Highest average department.
65. Top 10 students by CGPA.
66. Bottom 10 by attendance.
67. Relationship between projects and CGPA (summary).
68. Does higher study_hours generally mean higher CGPA? Use groupby.
69. Placement rate by department.
70. Average stipend of placed vs not placed.
71. Departments with most backlogs.
72. City with highest average stipend.
73. Average attendance by gender.
74. Distribution of CGPA using describe/value_counts bins if desired.
75. How many students have CGPA > department average?
76. Find outliers in attendance using IQR.
77. Rank students by CGPA.
78. Top city by placements.
79. Average projects by placement status.
80. Backlog count distribution.
81. Students above overall average CGPA.
82. Students below median attendance.

Total Questions: 82