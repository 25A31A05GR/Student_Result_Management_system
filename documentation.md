***ALGORITHM***
Step 1: Start Program
Step 2: Load Student Data from File
Step 3: Display Main Menu
Step 4: Accept User Choice
Step 5: Add Record → Input Details & Calculate Result
Step 6: View Record → Search & Display Marksheet
Step 7: List Records → Show All Data in Table
Step 8: Delete Record → Find & Remove Data
Step 9: Save Updated Data to File
Step 10: Exit Program
***FLOWCHART***
<img width="1024" height="1536" alt="WhatsApp Image 2026-04-20 at 10 28 32 PM" src="https://github.com/user-attachments/assets/0cc2bb5c-d8c9-4aea-b920-81f1de5e9e93" />
***METHODOLOGY***

*The system is developed using C++ and uses a Linked List to store student records dynamically. Each node stores roll number, name, semester, marks, total, percentage, CGPA, and grade.
*At program start, data is loaded from a file (data.txt) and converted into linked list nodes using file handling and string parsing.
*During data entry, the user inputs student details and marks for 10 subjects. The system validates input and calculates:
  *Total marks
  *Percentage
  *CGPA
  *Grade and pass/fail status
*The system provides a menu-driven interface with options to:
  *Add new record
  *View individual marksheet
  *Display all records in table format
  *Delete a record
*All operations update the linked list and are saved back to the file, ensuring data persistence.
*The program continues execution until the user chooses to exit.
