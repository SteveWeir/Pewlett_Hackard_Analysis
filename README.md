# Pewlett_Hackard_Analysis

### Analysis Overview

 Pewlett-Hackard, a large corporation, is in the process of examining its current inventory of human capital. As the "Baby Boomer" generation approaches retirement age, the firm is attempting to determine its exposure to employees on the verge of leaving the workforce. Pewlett-Hackard's assignments were as follows: using employee data and SQL, determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. With this analysis, the firm hopes to ascertain whether or not it is prepared to adequately replace the workers deemed a part of the "Silver Tsunami".

### Results

1.) The majority of workers considered to be a part of the "Silver Tsunami" occupy Senior Engineer and Senior staff roles (29,414 and 28,254 employees, respectively).

2.) Though it is rather unexpected, management roles appear to be affected the least, with only 2 employees considered to be near-retirement.


<img width="250" alt="retiring_titles_screencap" src="https://user-images.githubusercontent.com/85244439/137661111-abb63eee-648d-474e-9b53-5af7d7f3b886.png">


3.) Based on the results of the query, there are a total of 1,549 employees eligible to mentor incoming employees either through promotion or external hire.

4.) Of those 1,549 eligible to mentor, the majority are either senior staff or engineers (569 and 501 employees, respectively). Senior engineers have a worringly low mentorship eligibility rate relative to their expected outflux, with only 169 employees eligible.

[mentorship_eligibility.csv](https://github.com/SteveWeir/Pewlett_Hackard_Analysis/files/7361511/mentorship_eligibility.csv)


### Summary

 Based on the results of this analysis, Pewlett-Hackard is not well-positioned to adequately replace its aging human capital. With an expected outflow of 90,398 employees and only 1,549 eligible to mentor, it appears that- unless action is taken to attract new talent- Pewlett-Hackard is ill-equipped to mentor the next generation of employees. To provide more clarity on this issue, additional data, queries or tables might prove useful. A query of a younger age group (ex: those born between 1966-1976), ordered by department, might give the firm a better idea of how many employees are available to fill vacancies internally via promotion. An additional query showing a COUNT of mentorship-eligible employees by deptartment might also be beneficial. The firm can determine its expected mentor-mentee ratio by department, and address any shortages on a more accurate level.
