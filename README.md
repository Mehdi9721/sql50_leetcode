# date 24/09/24
left day 156. <br>
sql50.<br>
/////////////////////<br>

question 1= 1978. Employees Whose Manager Left the Company.

solution= select employee_id from employees where salary<30000 and manager_id not in (select employee_id from employees) order by employee_id;
approach=> subquerry written in 'where not in' will return whole row column for checking. <br>
/////////////////////////<br>
q 2 => 1667. Fix Names in a Table <br> 
ans => select user_id,concat(upper(substr(name,1,1)),lower(substr(name,2,length(name) ) )) name from users order by user_id;<br>
//////////////////////////////<br>
q 3=>



