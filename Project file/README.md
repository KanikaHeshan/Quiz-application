# Introduction About Zimpliq Quiz

According to Zimpliq quiz website, it may consider a quiz website. It was built for admin users and students. Admin can upload quizzes and students could be answered the quizzes. There are login and sign-up functions for entering the website. The signup function is the same for the students and teachers. There are several details needed for signing up.

Login as Student 
Here students can see Navigation keys and after select zimpliq quiz logo, they can come back to the home page. After the student by into the home page. They can get various quizzes and he can answer them only within the given time period. After answering questions, students can see what the correct answers are.

Login as admin 
If the admin needs to get admin privileges they need to log in or signup. After login, the user gets student privileges so, we have to turn it into an admin account. So first we go to the database "db" and get the "auth_ user" table. Then select the person who wants to give admin privileges, and need to turn the value of that person's row of "is_superuser" column as "1" for becoming the relevant user as admin and admin needs to save it, then need to refresh the browser. After the refresh, that user turns as admin. These admins can add quizzes, questions and see students ' results.
