# ECE444-F2020-Lab6

## Part 3: What are the pros and cons of TDD?
### Pros of Test Driven Development:
- Better architecture: In TDD, your code need to have a good architecture. If we want our code to be unit-testable, it must be properlu modularized.
- Easier code refactoring: In TDD, you need to write the unit tests before writing implementation code. Thus, the refactoring of code becomes easier and faster.
- Prevents defects: Since every new feature will be tested before it is used for future development, we will be able to detect bugs beforehand.
- Help programmer better understanding the project: By writing the unit tests, the programmars are force to think about the corner cases. They may realize something they never thought about before.

### Cons of Test Driven Development:
- Hard to apply to existing legacy code
- Take more time to adjust to new requirments: If the project/feature requirements have changed at the start, protentially, you will need to rewrite some of the unit test or even abandon some existing unit tests.
- Consume more team effort: In order to make TDD works well, everyone on the team needs to correctly maintains their tests. Otherwise, the whole system can quickly degrade.
- Sometimes it is hard to mock the exact scenario: In order to mock things in a complex code enviroments, it requires environment setup which requires resourses like manpower, hardware and time to maintain the environments.
