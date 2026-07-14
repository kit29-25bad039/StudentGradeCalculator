# StudentGradeCalculator
The Student Grade Calculator is a Java console application that calculates a student's total marks, average percentage, and grade based on marks entered for multiple subjects. It validates input, assigns grades using conditional statements, and displays the final academic result accurately.
Student Grade Calculator – Explanation (Point-wise)
1. Import Scanner
Imports the Scanner class from java.util.
Used to take input from the user.
2. Create Scanner Object
Creates a Scanner object named sc.
Reads the user's input from the keyboard.
3. Input Number of Subjects
Asks the user to enter the total number of subjects.
Stores the value in the variable subjects.
4. Initialize Total Marks
Declares totalMarks and initializes it to 0.
Used to store the sum of all subject marks.
5. Input Marks Using Loop
Uses a for loop to enter marks for each subject.
Repeats until all subjects' marks are entered.
6. Validate Marks
Uses a while loop to ensure marks are between 0 and 100.
If invalid marks are entered, the program asks the user to re-enter them.
7. Calculate Total Marks
Adds each valid subject mark to totalMarks.
Calculates the overall marks obtained.
8. Calculate Average Percentage

Computes the average using:

averagePercentage = (double) totalMarks / subjects;
Uses (double) to get a decimal value.
9. Determine Grade
Uses if-else statements to assign grades:
A : 90–100%
B : 80–89%
C : 70–79%
D : 60–69%
F : Below 60%
10. Display Results
Displays:
Total Marks
Average Percentage
Final Grade
11. Close Scanner

Closes the Scanner object using:

sc.close();
Prevents resource leaks.
Features
Accepts marks for multiple subjects.
Validates user input.
Calculates total marks and average percentage.
Assigns grades automatically.
Displays results in a clear format.
Easy-to-use console-based application.
Time Complexity
Time Complexity: O(n) (where n is the number of subjects)
Space Complexity: O(1)
