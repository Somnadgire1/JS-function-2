# JS-function-2
Title
JavaScript Function Challenges

Level
Level 0

Time to solve the problem
30 min

Overview
In this assignment, you will tackle various JavaScript function challenges covering topics such as array manipulation, object manipulation, destructuring, and spread operators. These challenges are designed to test your understanding of JavaScript fundamentals and improve your problem-solving skills.

Detailed Explanation
Topics
Destructuring for object manipulation
Destructuring for finding the average salary
Destructuring for extracting specific employee information
Problem Statements
Employee Information: Define a function employeeInformation that takes an array of employee objects, 'employees', as a parameter. Extract the name and department of the second employee in the array and assign them to variables 'secondEmployeeName' and 'secondEmployeeDepartment'. Return an object with 'secondEmployeeName' and 'secondEmployeeDepartment'.
//Example Invocation:
const employees = [
  { name: "John Doe", age: 30, department: "HR", salary: 50000 },
  { name: "Jane Smith", age: 28, department: "Finance", salary: 60000 },
  { name: "Alex Johnson", age: 35, department: "IT", salary: 70000 },
];

console.log(employeeInformation(employees)); // Output: { secondEmployeeName: 'Jane Smith', secondEmployeeDepartment: 'Finance' }
Average Salary: Define a function averageSalary that takes an array of employee objects, 'employees', as a parameter. Calculate the average salary of all employees using destructuring and a for-of-loop. Return the average salary.
//Example Invocation:

const employees = [
  { name: "John Doe", age: 30, department: "HR", salary: 50000 },
  { name: "Jane Smith", age: 28, department: "Finance", salary: 60000 },
  { name: "Alex Johnson", age: 35, department: "IT", salary: 70000 },
];

console.log(averageSalary(employees)); // Output: 60000
Third Employee Info: Define a function thirdEmployeeInfo that takes an array of employee objects, 'employees', as a parameter. Extract the name, age, and salary of the third employee and assign them to variables 'thirdEmployeeName', 'thirdEmployeeAge', and 'thirdEmployeeSalary'. Calculate a bonus of 10% on the salary. Return a string in the format "Employee: , Age: , Salary: , Bonus: ".
//Example Invocation:

const employees = [
  { name: "John Doe", age: 30, department: "HR", salary: 50000 },
  { name: "Jane Smith", age: 28, department: "Finance", salary: 60000 },
  { name: "Alex Johnson", age: 35, department: "IT", salary: 70000 },
];

console.log(thirdEmployeeInfo(employees)); // Output: "Employee: Alex Johnson, Age: 35, Salary: 70000, Bonus: 7000"
