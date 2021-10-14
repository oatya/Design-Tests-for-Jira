# Design Tests for Jira

I've done this school team project at Codecool's tester course.

## Story

Our mission as a team was to:

- Write a test plan
- Design and implement tests based on ISTQB suggestions
- Use folders in Zephyr Scale to organize the test-cases
- Execute the test-cases
- Write reports and generate reports in Zephyr Scale

## Tasks

1. As a registered user, I want to log in to Jira, so that I can use most functionalities. Example tests - Empty credentials, Wrong password, Captcha after 3rd try, Successful Login
    - Validate that login functionalities work correctly

2. As a registered user, I want to log out from Jira, so that I can protect my private data
    - Validate that logout functionalities work correctly

3. As a logged in user, I want to Browse existing Projects, so that I can access the details of tasks
    - Validate the Browse Project functionalities
    - In Projects / View all projects the available projects should contain COALA, JETI, and TOUCAN projects

4. As a logged in user, I want to create a new issue, so that I can track my tasks in any project
    - Validate the Create Issue functionalities
    - Using the Create button to create an issue, projects COALA, JETI and TOUCAN should be available to choose from
    - Using the Create button, for projects COALA, JETI, or TOUCAN, the available issue types to create should be Story, Task, Bug, and Sub-task

5. As a logged in user, I want to browse existing issues, so that I can access the details of tasks
    - Validate the Browse Issue functionalities
    - TOUCAN project has at least 3 issues that can be browsed individually (with ID 1, 2, 3)
    - JETI project has at least 3 issues that can be browsed individually (with ID 1, 2, 3)
    - COALA project has at least 4 issues that can be browsed individually (with ID 1, 2, 3, 4)

6. Every issue is editable by your user
    - Validate the Edit Issue functionalities
    - TOUCAN project’s issue with ID 1, 2 and 3 can be edited by your user
    - JETI project’s issue with ID 1, 2 and 3 can be edited by your user
    - COALA project’s issue with ID 1, 2, 3 and 4 can be edited by your user

7. Write a test plan
    - Determining the scope and objectives of testing
    - Defining the overall approach of testing, the test strategy and test schelude
    - Defining the preconditions and definition of done
    - Identify the risk assumptions

8. Write the purposes and contents for test reports
    - The test report should be included summary of all test activites and test results, such as number of test cases and bugs, duration etc. You can use Jira dashboard.

9. Determining defect management process
    - You can use traceability matrix for the test results are shown on different environments