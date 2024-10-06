# Healthcare-Website-Automated-With-Cypress
In this Cypress automation project, the website CURA Healthcare Service is automated using Cypress for end-to-end testing. The test inputs are extracted from an Excel file, which is converted into a JSON format to easily manage the data for multiple test cases. A custom method called multiIt is implemented to streamline the process of running multiple test cases in a batch. Unlike the traditional it block, which runs only a single test case, multiIt handles multiple test scenarios efficiently, allowing different data sets to be used in each iteration, improving test coverage and reducing redundancy in the code.

This Cypress automation project is designed to test the CURA Healthcare Service website. The primary goal is to automate repetitive testing tasks, ensuring the website's functionality, consistency, and user experience.

**Key Features:**

Data-Driven Testing: Inputs for test cases are extracted from an Excel file, providing flexibility and reducing manual data entry.
Excel to JSON Conversion: Cypress converts the Excel data into a JSON format, making it suitable for consumption within the automation scripts.
Custom multiIt Method: This custom method enhances test case execution by allowing multiple test cases to be run in a batch within a single it block. This improves efficiency and organization of the test suite.
