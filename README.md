#  Booking API Testing Project:
This project contains automated API tests for the Booking API, focusing on the end-to-end validation of booking-related functionalities. It leverages Postman to define test cases and Newman to execute tests and generate detailed reports.

# Project Overview:
This project aims to ensure that the Booking API functions as expected across various endpoints. It verifies that the API handles different scenarios, such as booking creation, retrieval, updates, and cancellations, with correct responses and behavior.

https://restful-booker.herokuapp.com/apidoc/index.html

# Execution with HTML Extra Report: 
To generate an HTML report after the tests:
```bash
   newman run "Booking API Testing.postman_collection.json" -e "Environment_Booking API.postman_environment.json" -r htmlextra --reporter-htmlextra-export newman-run-report.html
   ```


This command will create a detailed HTML report (newman-run-report.html) that you can open in any browser.
![image](https://github.com/user-attachments/assets/b8993791-093c-41d7-8a8d-d2ed2af50ec0)
![image](https://github.com/user-attachments/assets/4e7e4edf-b836-41be-9eea-e93b7f6e7b2c)

