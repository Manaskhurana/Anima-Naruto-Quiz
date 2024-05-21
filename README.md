it a simple naruto Quiz app made with ejs, javascript, css

important things to know for an anima lover
- answer the full name of the character so the game dont end
- if the answer is correct you will get 1+ point
- you can change the background by any img you like i have given some background of naruto from google so you can costomise it



brfore run the website
- install postgresql
- make password of the server
- creat a new database name what you like in my case i have given anima
- and create new table like

- 
- CREATE TABLE naruto(
- id Serial PRIMARY KEY,
- name varchar(30),
- quots varchar(200)
- );


- the table should match with csv file
- in table import the csv file
- if their is no erros  you completed the database

- in index.js in top their is a password string fill the password of postgresql and enjoy the Naruto Quiz website



how to run the code
- downlode the files
- in cmd type npm i
- after the install
- in cmd type nodemon index.js to run the websit in local host 3000


 
