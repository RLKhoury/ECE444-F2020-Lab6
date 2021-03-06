# ECE444-F2020-Lab6

This repo follows https://github.com/mjhea0/flaskr-tdd

Project Test is on lab6_tests branch of project repository: https://github.com/ECE444-2020Fall/project1-webapp-group9-nente/tree/lab6_tests

## Test Driven Development (TDD)

Test driven development is a methodology that one implements when working on a development project. The method involves putting the emphasis on writing tests for the intended functionality before implementing said functionalitly. Running the tests before implementation should yield a fail. When implementing, the goal is to get the test to a state such that it passes. Once all the test cases written are passed, the development of that functionality is 'done'. 

Employing a TDD methodoly nominaly increases confidence in the written code. Given that the test cases were thorough and set up well, you can be confident that the implementation was successful. Also, since TDD focuses on smaller unit tests, the code, by nature, will be modular (created by a combination of smaller functional components). This means that TDD enforces the key principles of modular design. Moreover, the test cases written can function as a sort of 'documentation' for your code. Since each test is individual and separately tests the components, you will have an explanation of what each component does simply by looking at the test cases. TDD also helps prevent bugs and defects in the code implementation. This is important in quick development-release cycles. You can automate the test cases to run on every developer's commit - rejecting if cases should fail - and this will ensure that releases always have the intended functionalities. This will also speed up the release cycle. During my PEY co-op year, I worked on setting up a new pytest framework for a component of the company's algorithm. I could do this without needing to understand the whole algorithm. Writing the test cases gave me intimate knowledge of the specific component, a great advantage for any developer.

However, with TDD comes the cost of upkeep. The tests must be prioritized as they are the basis of the project's development. This means that time must be allocated to maintaining the tests, ensuring their quality. This is time that is taken away from development and progress that can be made in adding more functionality. TDD also incurs a startup cost. Components must have tests before implementation and so there will always be a delay between conception and development wherein the test cases must be compiled and the tests themselves written. 
