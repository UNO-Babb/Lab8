# Lab8 - CIST 1600

## File Input/Output and Manipulation

A common problem in working on computers is that you have data in one format but want it to be in another format for your specific purposes.

### Input File

I have a datafile **"names.dat"** that contains text in the following format.

| First name | Last Name | E-Mail | Student ID | Date of Birth | Year | Major |
|---|---|---|---|---|---|---|
| Abby | Apples | abby@email.com | 123-45-6780 | 02/07/1982 | Junior | Music |
| Bob | Brown | bob@email.com | 123-45-6780 | 09/25/1981 | Freshman | Civil Engineering |
| Carl | Crowe | carl@email.com | 123-45-6780 | 05/26/1985 | Senior | Cyber Security |

### Desired Format
We want to take this information and re-work it for the database that we use on campus. For this database, we need to create a CSV(comma separated values) file so that we can upload the names directly. The CSV needs to contain the following information for each student:
- Last Name
- First Name
- UserID
  - User ID is first initial, last name, last 3 digits of their student ID
  - If their last name is shorter than 5 characters, an X is added
- Major-Year
  - The major is the first 3 letters of their major
  - The year is their year in school, abbreviated
    - FR
    - SO
    - JR
    - SR
  - These are joined with a hyphen (-) between the major and year

### Output File
Your code should process each line of the input file and write it to an output file. This file should be called **StudentList.csv** and contain all of the relevant information from the input file. Each element of the CSV is separated with a comma except for the end of the line. We will use the "\n" to show end of line.

---
## Testing your code
You may not actually know that your code works until you fully test what you have written. It is often a good idea to get someone else to run your program, they may do something you had not anticipated which could show you a possible flaw or at least a design issue.

## End of class
In Repl.it, you will find the share link to your code. That is what gets submitted to Canvas.
