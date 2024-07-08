# Programming-project-1.1
Group Members:
Imran Hamid - 191730
Samuel Omambia - 101861
Nathen Simbili - 191726
Yusuf Mahamud - 147613
Hamza Abdi - 191297


This C++ program is a Co-curricular Activities Management System designed to manage students, their participation in sports, and clubs/societies. Let's break down the code and its functionality:

For the first parts that have include, These are standard C++ library includes for input/output, file handling, data structures (vector), string manipulation, algorithms (count_if), and random number generation.

For the constants, These are constants defining maximum capacities and percentages for groups, sports, and clubs

For the structures, struct defines a Student structure to hold student information including name, gender, age, group, sport participation, and clubs.

The CoCurricularManager class encapsulates methods (run(), addStudent(), viewStudents(), etc.) to manage student data and operations related to sports and club

Methods Overview
run(): Main loop to display menu options and handle user input.
displayMenu(): Displays menu options for user interaction.
addStudent(): Prompts user to input student details including participation in sports and clubs.
canParticipateInSport(): Checks if a student can participate in a sport based on current student data.
canParticipateInClubs(): Checks if a student can participate in clubs based on current student data.
viewStudents(): Displays a list of students participating in sports and clubs (placeholder implementation using random names).
generateRandomName(): Generates a random name based on gender ('M' or 'F').
viewClubs(): Displays a list of available clubs.
viewSports(): Displays a list of available sports.
viewGroupedStudents(): Placeholder method for future implementation.
saveToFile(): Saves student data to a CSV file (students.csv)

Usage
The program allows administrators to manage and track student involvement in various co-curricular activities, ensuring limits on participation in sports and clubs are observed.

This overview covers the basic structure and functionality of the Co-curricular Activities Management System. If you have specific questions about any part of the code or its functionality, feel free to ask!



