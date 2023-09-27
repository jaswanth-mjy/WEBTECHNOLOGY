# WEBTECHNOLOGY
All my WEB TECH labs which i have done in VITAP is here 
# Lab 1 - Output Storage

This folder is for Lab 1 of the Web Technology course at VITAP. Follow the instructions below:

1. Create a folder named `RollNo_LAB1`, where "RollNo" should be replaced with your actual roll number.

2. Store all the output files in image format within the `RollNo_LAB1` folder.

3. Save the source code for Lab 1 in a text file using Notepad or any text editor of your choice.

Feel free to organize your Lab 1 materials according to these instructions within this repository.

---

**Note:** Replace "RollNo" with your actual roll number when creating the folder.

# Lab 2 - Webpage with Grid Layout and Form

This folder contains the materials for Lab 2 of the Web Technology course at VITAP.

## Instructions

1. Create a webpage using Grid Layout based on the provided Fig1 and Fig2.

   **Fig1: Grid Layout Example**
   ![Fig1](fig1_example.png)

   **Fig2: Grid Layout with Form**
   ![Fig2](fig2_form.png)

2. Create a form using HTML and CSS.

---

You can use the provided figures as a reference to design your Grid Layout and Form for this lab exercise. Feel free to customize the design and layout to meet your requirements.

**Note:** Make sure to include relevant HTML and CSS files in this folder to showcase your work for Lab 2.


# Lab 3 - HTML Page, JavaScript Validation, and More

This folder contains the materials for Lab 3 of the Web Technology course at VITAP.

## Lab 3 - Tasks and Instructions

### Task 1 - HTML Page and JavaScript Validation

1. Create an HTML page that includes the following elements:
   - Text field 1
   - Text field 2
   - Text field 3 (output field)
   - Three buttons: "First," "Second," and "Third"

2. Write JavaScript code to validate user input on clicking the buttons as follows:
   a. On clicking the "First" button, the text present in Text field 1 should change to red color with a pink background and be in uppercase.
   b. On clicking the "Second" button, Text field 2 should have a blue color dashed border and a red background.
   c. On clicking the "Third" button, concatenate the text in Text field 1 and Text field 2 and display it in Text field 3.

### Task 2 - Array Data Display

1. Read data from an array and display the data using an ordered list (OL) and unordered list (UL).

### Task 3 - HTML Registration Form with JavaScript Validation

1. Create an HTML registration form consisting of the following fields:
   a. Textbox with label "Username"
   b. Password box with a password label
   c. Password box with a confirm password label
   d. Textbox with label "Phone number"
   e. Textbox with label "E-mail"
   f. Submit and reset buttons.

2. When the form is submitted, perform the following validation using JavaScript:
   a. Validate the username (should not contain numbers and special symbols).
   b. Ensure the password and confirm password boxes contain the same characters, letters, and symbols; if the data in both boxes are different, display an error message.
   c. Check that the phone number field contains only ten digits.
   d. Verify that the email field is in the following format: "username@domain.com."

3. If any of the data is incorrect, the HTML page should display an alert message: "Not Completed." Upon successful validation, display the corresponding alert message: "Successfully Completed."

### Task 4 - Armstrong Number Check

1. Create two textboxes, T1 and T2.
2. Get a number from T1 and check whether the number is an Armstrong number or not.
3. Display the result in T2.

---

You can use this folder to organize and store the materials related to Lab 3. Feel free to customize the HTML, JavaScript, and CSS files as needed to complete the tasks outlined above.

# Lab 4 - PHP Webpage with Form and Data Processing

This folder contains the materials for Lab 4 of the Web Technology course at VITAP.

## Lab 4 - Tasks and Instructions

### Task 1 - PHP Webpage with Form Validation

1. Create a PHP webpage that consists of textboxes to read the following input fields:
   - "empid"
   - "salary"
   - "eName"
   - "address"

2. Include submit and reset buttons in the form.

3. Create a PHP file to process the form submission and perform the following checks:
   a. Check whether "empid" is proper or not (length of empid must be 8, the first four places of empid must be characters, and the remaining must be digits).
   b. Ensure "salary" contains only digits and is in the range of 4-6 digits.
   c. Validate "eName" to have characters only with the first character as a capital letter.
   d. Display the length of the "address" on the webpage.

### Task 2 - PHP File to Read Student Data and Display Results

1. Create a PHP file to read student data (RNo, Sname, 3 subject marks) from an HTML form. Use the POST method to submit the form data.

2. Display the result in a table as shown below:

   | RNo       | SName       | Total | Percentage | Result       |
   |-----------|-------------|-------|------------|--------------|
   | 19bci7034 | ffffffff    | 273   | 91         | First Class  |

---

You can use this folder to organize and store the materials related to Lab 4. Ensure that you have both the HTML form and the PHP files for processing the form and displaying the student data result as mentioned in the tasks.



# Lab 5 - PHP Webpage with Form and BMI Calculator

This folder contains the materials for Lab 5 of the Web Technology course at VITAP.

## Lab 5 - Tasks and Instructions

### Task 1 - PHP Webpage with Form and Data Processing

1. Create a PHP webpage that consists of four textboxes with the following labels:
   - "number1"
   - "number2"
   - "Name"
   - "address"

2. Include submit and reset buttons in the form.

3. Create a PHP file to process the form submission and perform the following actions:
   - Display the sum of digits of "number1."
   - Display "number2" in reverse order.
   - Convert the "Name" into uppercase and also display it as a heading of the page.
   - Display the length of the "address" on the webpage.

### Task 2 - PHP BMI Calculator

1. Create a PHP form that calculates the BMI (Body Mass Index) of a person by taking input through the form.

2. Upon submission of the form, calculate the BMI using the formula:
   - Metric Units: BMI = weight (kg) / [height (m)]^2
   - Imperial Units: BMI = weight (lb) / [height (in)]^2 * 703

3. Print the BMI category as a response in the next page based on the calculated BMI value:
   - Below 18.5: Underweight
   - 18.5–24.9: Healthy
   - 25–29.9: Overweight
   - 30 and above: Obese

---

You can use this folder to organize and store the materials related to Lab 5. Ensure that you have both the HTML form and the PHP files for processing the form data and performing BMI calculations as mentioned in the tasks.

# Lab 6 - PHP File Operations

This folder contains the materials for Lab 6 of the Web Technology course at VITAP.

## Task 1 - PHP Program for Number Occurrence

### Instructions

1. Write a PHP program to write 50 numbers into a file.

2. Read 20 numbers at a time from the file and find the numbers that occur an even number of times and those that occur an odd number of times.

#### Input
Example Input: `2 4 6 7 7 7 8 9 0 1 11`

#### Results
- Even Occurrence: `2 4 6 8 0`
- Odd Occurrence: `7 9 1 11`

## Task 2 - PHP Script to Read Company Names

### Instructions

1. Create a PHP script to read data from a text file named "company.txt," which consists of various company names.

2. Count the number of unique companies and display them as a list in the following way:

#### Example content of "company.txt"
-Apple YouTube Intel Microsoft CTS TCS Google GGG RRR
#### Output on the webpage
Count of companies: 9
Apple
YouTube
Intel
Microsoft
CTS
TCS
Google
GGG
RRR

You can use this folder to organize and store the materials related to Lab 6. Ensure that you have the PHP files for both tasks as outlined in the instructions.



# Lab 7 - PHP Form Handling and Database Operations

This folder contains the materials for Lab 7 of the Web Technology course at VITAP.

## Task 1 - PHP File to Read Form Data and Display Employee Table

### Instructions

1. Create a PHP file to read details from an HTML form.

2. Use the submitted data to create a table named "employee" and display the result in the table format as shown below.

   | EmpNum  | EmpName | Designation         | Age | Experience | Department | Salary  |
   | ------- | ------- | ------------------- | --- | ---------- | ---------- | ------- |
   | 700001  | AAAAA   | Assistant Professor | 36  | 5          | SCOPE      | 10000   |
   | 700001  | AAAAA   | Assistant Professor | 56  | 10         | SCOPE      | 100000  |

## Task 2 - PHP Script to Display Highest Salary Employees

### Instructions

1. Create a PHP file to read the table name from an HTML form.

2. Read employee details from the specified table and find employees with the highest salary in each department.

3. Display the results in a tabular format on the webpage.

## Task 3 - PHP Script to Update Designation and Salary

### Instructions

1. Create a PHP file to read the table name from an HTML form.

2. Update the designation and salary of employees whose experience is more than 5 years, following the norms shown in the table.

3. Display the updated results in a table as shown below.

   | EmpNum  | EmpName | Designation         | Age | Department | Salary  |
   | ------- | ------- | ------------------- | --- | ---------- | ------- |
   | 700001  | AAAAA   | Senior Professor    | 36  | SCOPE      | 12000   |
   | 700001  | AAAAA   | Senior Professor    | 56  | SCOPE      | 110000  |

## Task 4 - PHP Script to Delete Employees by Age

### Instructions

1. Create a PHP file to read the table name from an HTML form.

2. Delete the employee details whose age is greater than 65.

3. Display the remaining employees' details in a table as shown below.

   | EmpNum  | EmpName | Designation         | Age | Department | Salary  |
   | ------- | ------- | ------------------- | --- | ---------- | ------- |
   | 700001  | AAAAA   | Assistant Professor | 36  | SCOPE      | 10000   |

You can use this folder to organize and store the materials related to Lab 7. Ensure that you have the PHP files for all tasks as outlined in the instructions.


-LAB 8 QUESTION:
Create webpage using ng-app,ng-bind-ng-init directive in AngularJS
