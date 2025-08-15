# scheduling
This group project focuses on applying scheduling and optimization for airplane scheduling problem.

Abstract
This report addresses the complex challenges associated with flight and crew scheduling (CS) problems,
focusing on Virgin Australia, which can also be described as a machine-job scheduling problem. The
Bender decomposition approach is employed, dividing the problem into three stages: fleet assignment
and routing (MILP), flight scheduling (E/T), and CS (PT). We proposed two MILP models; one is
proven to improve the objective value by 17%, suggesting that the sixth and latest flight must go to
the origin city. Additionally, the Earliness-Tardiness approach is used to create flight schedules, with
due dates set at 13:00, aiming to align with passenger preferences. This approach results in a promising
flight timetable: the majority of the flight is scheduled at midday. Moreover, a modified list scheduling
(LS) is used to solve the CS problem, ensuring even distribution of the working hours across the team
in each home base, with due dates set to 36, that is, the maximum working hours per week. In solving
CS, some cases were observed by changing the maximum number of shifts, which can be analysed to
determine which is more profitable between hiring additional crew or paying overtime. However, despite
these findings, the model proposed in this report still used several assumptions and simplifications, which
still need to be adjusted for practical implementation.
