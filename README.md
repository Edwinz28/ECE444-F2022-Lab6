# ECE444-F2022-Lab5
This repository is a walkthrough of: https://github.com/mjhea0/flaskr-tdd
## Heroku
https://still-taiga-63223.herokuapp.com/

## Educational Pathways Tests
I wrote all the tests for admin panel back-end testing. Name not commented in code (check git history for the file if needed): [Admin panel tests](https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-18-caffeinated/blob/dev/Education_Pathways/tests/test_admin.py)

I wrote all the tests for admin pw/private routes. Name not commented in code (check git history for the file if needed): [private route tests](https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-18-caffeinated/blob/dev/Education_Pathways/tests/test_admin_pw.py)


## Pros of TDD
TDD forces a developer to break down a larger problem into smaller "subproblems" which in turn breaks down the larger program into smaller modules. This then allows for for a developer to create tests for each of these modules ensuring that they work before continuing development. This helps avoid debugging large amounts of code which can be time consuming. These tests also act as regression tests which can be used to ensure that the development of a new feature does not break an existing feature. Additionally, the tests illustrates how the modules should be used which is a form of documentation.

The modularization of the codebase makes it easier to just maintain or develop on a single component. For example, a developer who is improving the user login system will know that their changes will only affect the user login. Finally it also make collaboration easier as the tests will alert a new developer if their changes are breaking existing functionality or doing something unexepcted.

## Cons of TDD
The main cons of TDD revolve around the idea that TDD adds more work to the development process. Making a feature and its tests is more work than just making a feature, which also means it can (not always, really depends on the nature/complexity of the feature) be slower. Furthermore, these tests need to be maintained and updated when requirements change or even when external dependencies/libraries change. Additionally everyone on the team is highly recommended to also follow TDD as if a developer does not make tests it results in untested code and cannot be used as a means to test complete functionality. Finally from my personal experience in industry, it is quite a lot harder to create tests for someone else's code vs your own which may be the case if the entire team does not follow TDD. This is the often the case if the previous developer leaves the company and you're stuck filling the gap of tests.
