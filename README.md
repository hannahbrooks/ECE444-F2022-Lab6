# ECE444-F2022-Lab6
### Hannah Brooks

This repo follows steps 1-18 of https://github.com/mjhea0/flaskr-tdd.

## Unit Tests
https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-2-pitcrew/blob/main/Education_Pathways/tests/test_app.py#L40-L46

## Pros and Cons of TDD
Test Drive Development (abbreviated to TDD) is a method of writing software where you begin by writing tests that fail, and slowly start writing code to make those tests pass. The key is that the test are written before the coding begins.

Some pros of this methodology include creating more modular code, helping to prevent defects and allowing for easier refactoring. When you are writing very small unit tests one at a time, you ensure that the code is written in a similar way, with smaller components becoming easily reusable and combinable. This in turn helps prevent defects as the tests will indicate failure when adding to existing code and will allow for simple mistakes to be caught early on and prevent further hassle down the road. Finally, because of the nature of TDD, there is clarity in the implementation of code with specific tests outlining the purpose of components that can help developers refactor old code if needed. There is also usually associated documentation for both the code and the tests that can help.

Of course as with any methodology, there are also cons. Some cons of TDD include slowing down development, being harder to implement and continue for legacy code and increased code maintenance. When code is initially being written, having to double the work load to wite tests for each piece of code written can greatly increase developer-time estimates. Similarly, if the team is working with an existing code base, it can become challenging to add tests for all of the code previously written. Finally, TDD requires a lot of housekeeping and maintenance to ensure that all tests are written well, up to date and can make build times much longer.

All together, there are trade offs for TDD but at the end of the day, having a testable, maintainable and modular code base is something that all developers strive to create and TDD is a useful method to get there.
