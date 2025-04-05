# Pandas-Challenge 

# PyCity Schools Analysis

## Overview
This analysis provides insights into school district performance metrics, leveraging Python and Pandas for data manipulation and analysis. By analyzing various factors such as school type, size, and spending, the project draws conclusions about student performance across different categories.

---

## Key Findings
1. **Charter vs. District Schools**:
   - Charter schools consistently outperform District schools in all categories. For example:
     - **Cabrera High School** (Charter) has a **91.33% Overall Passing Rate**, compared to **Bailey High School** (District) with only **54.64%**.
   - The smaller class sizes and alternative teaching methodologies in Charter schools may drive their success.

2. **Spending Efficiency**:
   - Lower per-student spending often correlates with higher performance:
     - **Wilson High School** ($578 per student) achieves a **90.58% Overall Passing Rate**.
     - Schools spending more, such as **Huang High School** ($655 per student), see diminishing returns with an **Overall Passing Rate** of just **53.51%**.

3. **School Size**:
   - Smaller schools (<1000 students) outperform larger ones:
     - **Holden High School** (427 students) boasts an **89.23% Overall Passing Rate**, compared to **Hernandez High School** (4635 students) with only **53.53%**.

4. **Subject Trends**:
   - Reading scores consistently exceed math scores across schools, suggesting a need for targeted math interventions.

---

## Data Summary

### **District Summary**
- **Total Unique Schools**: 15
- **Total Students**: 39,170
- **Total Budget**: $24,649,428
- **Average Math Score**: 78.99
- **Average Reading Score**: 81.88
- **% Passing Math**: 74.98%
- **% Passing Reading**: 85.81%
- **% Overall Passing**: 65.17%

### **School Summary**
The report includes school-level performance metrics such as:
- School type (Charter or District)
- Total budget (with  ranges per student spending)
- School size
- Average math and reading scores
- Percentage of students passing math, reading, and overall.

### **Other Findings**
- **Top-performing schools**: Cabrera High School, Griffin High School.
- **Bottom-performing schools**: Rodriguez High School, Huang High School.
- **Scores by Grade**: Math and reading scores are calculated for each grade (9th to 12th).
- **Scores by Spending and Size**: School performance is evaluated across spending ranges and size categories to identify key trends.

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/pycity-schools-analysis.git

2. Install required dependencies:
   ```bash
   pip install pandas

3. Run the analysis in Jupyter Notebook:
   ```bash
   jupyter notebook PyCitySchools.ipynb

----

## Resources adn References
1. [Python Official Documentation](https://docs.python.org/)
2. [Pandas Documentation](https://pandas.pydata.org/docs/)
3. [Jupyter Notebook Guide](https://jupyter.org/)
4. [W3Schools](https://www.w3schools.com/)
5. [Microsoft Copilot](https://copilot.microsoft.com/)  
6. **Data Source** : PyCitySchools\Resources (**`schools_complete.csv`** and **`students_complete`**)

----

## Conclusion
This analysis identifies significant trends in school district performance, emphasizing the benefits of efficient spending, smaller schools, and the success of Charter school models. Future strategies could prioritize math-focused programs and resource allocation to improve outcomes further. 
