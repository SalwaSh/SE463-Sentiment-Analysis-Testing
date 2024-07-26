# Sentiment Analysis 😄📊

Our sentiment analysis software is a simple simulation for natural language processing 
technique that uses several if condition statements to automatically classify the 
sentiment of a given text into positive, negative, or neutral categories

### Project Objective 🎯
The purpose of this project is to demonstrate our knowledge of Software Testing and 
Quality Assurance. To accomplish this, we will be utilizing dynamic testing as one of 
our testing techniques to measure code coverage. We will design our test plans, create 
test suites, and perform test coverage both manually and automatically. To compare the 
results, we will evaluate test suite coverage using the well-known "Coverage.py" library 
in Python. 

### Testing Plan 📑
<table>
  <thead>
    <tr>
      <th>Testing Strategy</th>
      <th>Testing Level</th>
      <th>Testing Technique</th>
      <th>Category of Testing Technique</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Top-Down Approach</td>
      <td>System Testing</td>
      <td>Dynamic Testing</td>
      <td>White-Box Testing (Structure-Based)</td>
    </tr>
  </tbody>
</table>

## Example: Coverage Criteria (Statement, Branch, Condition) 🏆

**Test Case 01:**
- I absolutely love this new car! Driving it brings me so much joy and I am so excited to take it on a road trip this weekend.

**Output:** 
- Positive
- The percentage of positive words in the text is: 11.11%
- The percentage of negative words in the text is: 0.0 %
- The percentage of neutral words in the text is: 0.0 % 

### A. Manual Testing 🔍

1. Statement Coverage = Number of Executed Statements / Total Number of Statement *100 
  ```
 = (27 / 37) ∗ 100 = 72.9%
  ```
2. Branch Coverage = Number of Executed Branches / Total Number of Branches *100 
 ```
 = (7 / 14) ∗ 100 = 50%
 ```
3. Condition Coverage = Number of Executed Operands / Total Number of Operands *100 
 ```
  = ( 8 / 20 ) ∗ 100 = 40%
 ```
**Note: For more details on how they were calculated, refer to the report**

### B. Automatic Testing (Coverage.py) 💻

1. Statement Coverage
![image](https://github.com/user-attachments/assets/805fa31d-9d46-45ab-9234-0e3d7d3fd767)

2. Branch Coverage
![image](https://github.com/user-attachments/assets/037d5e0d-1a55-4915-85b4-182803b1a2ea)

**Note: Only statement and branch coverage were provided, as the tool does not support condition coverage**

## How to Run ⚙️
1. Download the SentimentAnalysis.py file.
```
 git clone https://github.com/SalwaSh/SE463-Sentiment-Analysis-Testing.git
```
2. Install the coverage package:
```
pip install coverage
```
3. Run the code using the following command:
```
converage run SentimentAnlysis.py 
```
4. To see a short coverage report, use the following command:
```
converage report -m
```
5. To see a nicer presentation of the coverage report, use the following command:
```
coverage html
```

## Contributors ✍️

- Jana Aldubai
- Salwa Shamma
- Samah Shamma
- Sana Shmama
