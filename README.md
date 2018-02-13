# CS490
CS490-NJIT-AJAX


Naming Conventions for Functions
===============================
Login Function
--------------
{
header => login
username
password
}
[backend returns]
{
 (fail, student, or teacher)
}

===============================
Question Bank Add
-----------------
{
  header(addQuestion)
  name (operate)
  question (create a program named operate that takes three parameters: op, a, b. The program will multiply, add, subtract, or divide the parameters a and b, and return the output)
  topic (if statements)
  difficulty (easy)
  cases op,a,b
  input (+:1:2,-:3:2,* :4:6, /:4:2) (all a single string)
  output (3,1,24,2)
 }
 [backend returns]
 {
  (success or fail)
 }
 ==============================
 Question Bank Request (returns list of questions)
 {
  header(bankRequest)
 }
 [backend returns]
 array{
  [0]{
    name
    question
    topic
    difficulty
    cases
    input
    output
  
  }
  [1]{..}
  [2]{..}
  .
  .
  . 
 }
 
 
 
 
 
 
 
 
 
 
 
 
 
 
