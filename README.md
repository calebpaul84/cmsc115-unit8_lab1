# Lab Reflection: Unit 8 Lab 1 - Git Version Control + Debugging (BuggyProgram)

## Student Name
Caleb Paul

## GitHub Repository URL
https://github.com/calebpaul84/cmsc115-unit8_lab1

---

# Commit 1: Initial Commit

## What did you include in this commit?
- To show the initial start of the project.

## What was the purpose of this commit?
- To create a start point of the project and to show what the
- program looked like before any changes.

---

# Commit 2: Task 1 (getGrade)

## Which tests in Task1Test were failing before your fix?
- Both tests, testGrades and testEdges failed. 

## What was the issue in the code?
- The formating was bad. The returns for "Meets" and "Exceeds"
- were flipped and outputting for the wrong scores. Also had >
- rather than >= for the score ranges.

## What change did you make to fix it?
- Put "Meets" and "Exceeds" in the correct locations and 
- added >= to the score ranges.

## How did the tests help guide your fix?
- It told me what the score ranges are supposed to be for 
- the "Meets" and "Exceeds" categories.

---

# Commit 3: Task 2 (sumEvenNumbers)

## Which tests in Task2Test were failing before your fix?
- All tests failed.

## What was the issue in the code?
- The for statement had an error. It was (i = 0; i <= values.length; i++)
- The correct statement is (i = 0; i < values.length; i++)
- It also had sum = 1, and it should be sum = 0

## What change did you make to fix it?
- I changed the for statement to (i = 0; i < values.length; i++)
- I also set sum to sum = 0
## How did the tests help guide your fix?
- The index error it had told me something was wrong with how
- it was iterating over the array.

---

# Commit 4: Task 3 (sumRange)

## Which tests in Task3Test were failing before your fix?
-

## What was the issue in the code?
-

## What change did you make to fix it?
-

## How did the tests help guide your fix?
-

---

# Overall Reflection

## Which task was the easiest to fix? Why?
-

## Which task was the most difficult? Why?
-

## How did Git help you track your progress through the debugging process?
-

## Why is it important to make small, frequent commits when debugging code?
-

## What did you learn about using JUnit tests to guide debugging?
-

---

# Commit 5: Final Reflection

## What did you complete or update before making this final commit?
-

## Why is it useful to document your work after completing a programming task?
-