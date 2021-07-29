# Pewlett-Hackard-Analysis

## Overview

At the forefront of senior management's mind is managing rates of attrition. In order make informed hiring decisions and combat the "silver tsunami", our team has compiled and provided to Bobby's manager the number of retiring employees by title and identified employees who are eligible to participate in a mentorship program.

## Results

### Deliverable 1
* Employees that have multiple promotions (multiple titles in the system) caused retirment titles to yield duplicate values. Therefore, we leveraged the DISTINCT ON syntax to remove duplicate rows.

### Deliverable 2
* The results yielded a large population of employees retiring within the same timeline which could have seismic impact on company operations

* The MAX and MIN population of employees nearing retirement are Senior Engineers and Managers, respectively.
  
  ![image](https://user-images.githubusercontent.com/85204128/127542453-52160fb9-5adb-4f91-85a4-545082dfef10.png)

* Of that population of employees reaching retirement, those eligible for mentorship programs is insignificant. For Senior Engineers eligible to mentor vs total population of soon to be retirees, only 1.4% are eligible to participate in the program.

  ![image](https://user-images.githubusercontent.com/85204128/127543189-5b158a06-8b0f-4ff3-a4c1-9cc2d935dad8.png)


## Summary
The results clearly show a large population of employees retiring around the same time frame. This will have a material impact on companies continued success.

### Responses to upcoming "silver tsunami"
* How many roles will need to be filled as the "silver tsunami" begins to make an impact?
  
   When the retirment age is reached, 90,398 employees with different titles will be eligible for retirement.
  
  ![Total Count of Retiring Employees](https://user-images.githubusercontent.com/85204128/127522206-7638e393-8289-4b10-a909-adf94287c885.PNG)

* Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
  
  No, there are not enough qualified retirment-ready employees in the respective departments to mentor the next generation of Pewlett Hackard employees. The mentor elibigility group pales in comparison to the total population of retirement eligible employees.
  
  ![image](https://user-images.githubusercontent.com/85204128/127522989-5affc92e-fcbf-4c44-a3cf-b12f03f75f6e.png)
