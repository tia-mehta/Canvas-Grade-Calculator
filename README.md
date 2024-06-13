# Canvas-Grade-Calculator
Canvas Grade Calculator

Project Description:
This project involves creating a Python script that interacts with the Canvas Learning Management System API to retrieve information about assignments in a specified course. The script is designed to fetch data about assignment groups and their corresponding assignments, including details like assignment names, points possible, and scores. The retrieved data is then processed and displayed in JSON format.

Configuration Setup:
config.json file for necessary configuration variables: ACCESS_TOKEN, BASE_URL, COURSE_ID, and API_VERSION.
If any of these variables are missing, the script prompts the user to input them manually.

API Request and Data Processing:
The script constructs the API endpoint URL for fetching assignment groups and their assignments.
It sends a GET request to the Canvas API with corresponding headers and parameters.
The assignment data is retrieved, processed, and printed. The script also calculates the current and final grade percentages based on the assignment scores and weights.

Output:
The script prints the details of each assignment, including the assignment name, ID, total points possible, points earned, and weight.
It also calculates and prints the overall current and final grades for the course.
