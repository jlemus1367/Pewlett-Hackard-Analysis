# Pewlett Hackard Analysis
## Project Overview
Pewlett Hackard is a leading information technology company that provides hardware and software solutions to many customers, ranging from casual consumers to worldwide enterprises. They have maintained a robust outlook in a continuously evolving industry where innovation and disruptive technology can make or break a company. Pewlett Hackard attributes its unwavering success to its diligent staff consisting of thousands of scientists, engineers, and business professionals. Unfortunately, their tenured staff cannot work forever, so PH must be mindful of the roles that will become vacant in the upcoming years. 
In this project, we will explore various CSV files containing employee information and link them together in a database management system to uncover the positions that will need to be filled, along with determining which employees are eligible for retirement packages. By taking a proactive approach to its staffing needs, PH can further bulletproof the company in an industry full of uncertainty. 
## Resources
- pgAdmin 4.30
- PostgreSQL 11.11
## Results
- 90,398 employees are expected to retire in the upcoming years based on the retiring titles table we created

    <img src = "Images/rt_sum.png" width=200> 
    
- At first glance, it appears the vast majority of retiring staff are either senior staff or senior engineers

    <img src = "Images/retiring_titles.png" width=200> 
    
  - 33% of retiring employees are senior engineers
  - 31% of retiring employees are senior staff
- If we consider senior engineers and engineers as an entire unit, then the amount of retiring engineers is closer to 50% 

    <img src = "Images/SE_E.png" width=300> 

- There are 1549 eligible employees for the mentorship-eligibility program based on the mentorship-eligible table we created

    <img src = "Images/eligible_amt.png" width=200> 

## Summary
