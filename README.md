# **Exam Performance Dataset Project**

### **Contributors**

<a href="https://github.com/wue1atwit/ExamDatatset/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=wue1atwit/ExamDatatset" />
</a>

### **Tabel of Content**

- **[Abstract](#abstract)**<br>
- **[Selection of Data](#selection-of-data)**<br>
- **[Methods](#methods)**<br>
- **[Results](#results)**<br>
- **[Discussion/Summary](#discussionsummary)**<br>

## **Abstract**

**Purpose:**
We all have taken exams throughout our academic careers. Whether they are standardized tests or exams for a specific subject in school, some people struggle through specific portions of those exams, and with this dataset, we may be able to see the correlation between different factors and attributes of a student. We would like to see the connections between students’ grades and other parameters including but not limited to test preparation, parental level of education, etc.

**Core Questions:**

<ul>
    <li>What is the distribution between all scores?</li>
    <li>What is the correlation between grades and test preparation?</li>
    <li>What is the correlation between grades and groups?</li>
    <li>What is the correlation between grades and lunch?</li>
    <li>What is the correlation between grades and gender?</li>
    <li>What is the correlation between grades and parents' level of education?</li>
</ul>

**Hypothesis:**
We believe students that prepare for the test should score higher overall than students who do not prepare.

## **Selection of Data**

**Source:**
<a href="https://www.kaggle.com/datasets/whenamancodes/students-performance-in-exams">https://www.kaggle.com/datasets/whenamancodes/students-performance-in-exams</a>

Our dataset came from Kaggle and is called Students Performance in Exams by Aman Chauhan. The dataset has eight columns or in this case eight different attributes. There are three attributes with numerical values while the other five attributes are string values. These attributes include the student’s gender, race/ethnicity, parental level of education, lunch type, test preparation course, math score, reading score, and writing score. The sample size of the dataset is 1000, which means we have 1000 different students with varying attributes. Furthermore, we wanted to see the average score of the three scores for each student. To perform this we took, we appended a new column to the original dataset and named it “avgScore.” This column would add all three of the students’ scores up and divide by three to find the average of those scores (See Figure 1).

## **Methods**

In later parts of the report, we will show the division of work on who answered which of our core questions. In this project, we used the material we learned in class from the lecture Jupyter Notebooks. These tools and APIs include using Seaborn and Matplotlib main for visualization. Next, we used NumPy and Pandas to manipulate our data. We also used NumPy to check and clean our data. For example, to check the cleanliness of our dataset we used the methods `isnull()` and `isna()` and sum up all the null and na values on each column to see if there were any of these values (See Figure 2).

## **Results**

For the results, we will be discussing our findings in our personal section because it will show the division of work, which visuals each of us formulated, and which questions we answered with those visualizations. Additionally, our hypothesis was that students that went through a test preparation course or prepared for the exam in any way would perform better, and we were able to show proof and visuals on why that hypothesis was true.

## **Discussion/Summary**

In conclusion, with our analysis of the data and visualization, we can conclude a variety of different factors and attributes that may affect a student’s exam score. We found out those students with parents that had higher levels of education usually scored higher on their exams than those with parents of lower education. Next, we found that students who had a standard lunch, essentially paid more to get lunch, would usually score higher than those who had free or reduced lunch. Relating back to our hypothesis, we can also conclude that students who prepared for the exam performed better than those who did not prepare. Finally, from our visualization, mainly the pair plots, we can see that all the test scores – math, reading, and writing – are proportional to each other. For example, we can see that as students’ math scores increased so did their reading scores.

There may be some points of view that may oppose some of our findings for this dataset. Some people may have the mindset that students with parents who went to higher education usually would perform worse in school because they do not have similar aspirations to getting into higher education to students whose parents did not go to college. On the other hand, students whose parents went to higher education may be more capable of “lending a helping hand” to their students to help them study for the exam. For instance, the parent may have a strong grasp on certain subjects like math where they are able to explain and lead their children to success. Overall, there may be other factors that play a role in determining students’ performance on these exams.

# **Division of Work (Review):**

### **Payton's Contribution**

### Diversity in Data (Gender):

![Gender Diversity Graph](https://github.com/wue1atwit/ExamDatatset/blob/main/Images/genderDataNew.png)

**Observation**:
These graphs show the distribution of students in the data organized by gender. It is evident that there is slightly more male than female students.

### Diversity in Data (Race/Ethnicity):

![Group Diversity Graph](https://github.com/wue1atwit/ExamDatatset/blob/main/Images/groupDataNew.png)

**Observation**:
These graphs demonstrate the diversity in the data, and the division of each separate race/ethnicity taking the tests. There is a slight inequality in the total number of students in each group, which is to be expected considering each student was randomly selected.

**Distribution Between Scores**:

![Score Distribution Graph](https://github.com/wue1atwit/ExamDatatset/blob/6498b9a57064f4c778032d42e193679c1add2ad3/Images/scoreDistribution.png?raw=true)

**Observation**:
These bar graphs demonstrate the distribution between the 3 different types of tests, and then the average score of all tests combined. The shape of these graphs follows a normal distribution, with slight variation. Another observation is that there were more students scoring perfect / very high on the tests than those who scored extremely poorly.

**Distribution Between Genders**:

![Gender Distribution Graph](https://github.com/wue1atwit/ExamDatatset/blob/main/Images/genderDistribution.png)

**Observation**:
This graph shows the distribution of average scores compared between male and female students. Purple, which is the most common color in the visualization shows the overlap of male and female scores. Also, the graph followed a normal distribution with slight variation, namely more students scored extremely high than those who scored extremely low.

### **Individual Portion Submission**

### Distribution Between Parent Level of Education:

![Parent Level of Education Distribution Graph](https://github.com/wue1atwit/ExamDatatset/blob/main/Images/individualPaytonParentEducationDist.png)

**Observation**:
This section involved creating a histogram with the average test score on the x-axis, and the count on the y-axis. It displays hows the distribution of average test scores depending on the education of the student’s parents.

### Linear Regression Model- Math vs Reading Scores: Male & Females

![Linear Regression Graph](https://github.com/wue1atwit/ExamDatatset/blob/main/Images/individualPaytonRegression.png)

**Observation**:
The first step was to create a scatter plot of the math scores of both males and females on the x-axis, in order to then align it with the reading scores on the y-axis. The next step was to create a line of best fit (regression line) using the slope of the data, with red to represent the female scores and dark blue for male scores.
