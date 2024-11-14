# Exercise 2: Automated Text Classification Using OpenAI API

## Objective

Develop a script that classifies text data into predefined categories using the OpenAI API.

## Instructions

1. **Dataset:** You are provided with a CSV file named `incident_data.csv`, which contains the following columns:
   - `description`: A short description of an issue or incident.
   - `resolution`: The resolution taken for each issue.
   - `date`: The date the issue was recorded.

2. **Task:** Use the OpenAI API to classify each row into one of the predefined categories based on the `description` and `resolution` text fields. Categories could include, for example, **Network Issues**, **Hardware Problems**, **Software Errors**, etc.

3. **Resources Provided:**
   - **OpenAI API Token**: You will be given an API token with limited credit.
   - **Documentation**: Refer to [OpenAI API Documentation](https://platform.openai.com/docs/guides) for guidelines on usage and limits.

4. **Script Requirements:**
   - Write a Python script that:
     - Connects to the OpenAI API using the provided token.
     - Sends the `description` and `resolution` fields to the API.
     - Receives a classification label for each incident.
     - Stores the original data along with the classification label in a new CSV file called `classified_incidents.csv`.
   - Make sure to handle API limits and errors gracefully.

5. **Deliverable:**
   - Submit your script along with the resulting `classified_incidents.csv`.

## Evaluation Criteria

Your submission will be evaluated based on:
- Successful implementation of the OpenAI API for classification.
- Code clarity and error handling.
- Efficient handling of API limits and constraints.

Good luck, and feel free to reach out if you have any questions!
