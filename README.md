# The instructions

Follow codding standarts (Attached)<br />
Every solution should have a description.<br />
Create a github private repository and provide the link.<br />

Deadline: 05.10.2021 23:59:59<br />

Tasks:<br />

1. Create a function that returns the number of Saturdays between the two inputted dates.<br />
 
2. Create a function that finds whether a given string is palindrome or not.<br />

3. Create a function that finds the sum of digits of the inputted number.<br />

4. Assume you have two identical tables which need to be syncs every time. <br />
Write a procedure that checks if they don't synch and synch them if required.<br />

5. Print(dbms_output) the multiplication table to 9.<br />
1x1=1<br />
1x2=2<br />
...<br />
1x9=9

6. You running the query:<br />
select count(*) from some_table;<br />
After 5 mins you are getting results: 0<br />
Why it took that long ?<br />

7. Need to find the count of "!":<br />
'Hello World! It is a good day!!!'<br />
Here its 4.<br />
Use only SQL<br />
Give more than one solution.      <br />

8. Create a package with procedures/functions to call Web Service from PLSQL. SOAP or REST<br />
Example: https://habr.com/ru/post/223405/ <br />
You might have your own structure. <br />
Mandatory: The solution must be configurable. It should be easy to add call to a new endpoint.<br />

9.* Print the days of the current month in Azeri language like<br />
01.10.2021	CÜMƏ<br />        
02.10.2021	ŞƏNBƏ<br />   
03.10.2021	BAZAR<br />
...<br />
30.10.2021	ŞƏNBƏ<br />
31.10.2021	BAZAR<br />

2 solutions: SQL only and with PL/SQL<br />

10.* Create a trigger that will log the compilation of every :<br />
•	View<br />
•	Function<br />
•	Procedure<br />
•	Package<br />
•	Type<br />
•	Record<br />
 to a table with these columns: <br />
•	compile_time<br />
•	username<br />
•	machine_name<br />
•	object_name<br />
•	object_type<br />
•	code_before<br />
•	code_after<br />
