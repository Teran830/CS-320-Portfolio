## CS 320 Portfolio Reflection

### How can I ensure that my code, program, or software is functional and secure?

I check my code against the requirements and use JUnit tests to verify both expected behavior and invalid inputs. In my contact service, this includes checking field restrictions, rejecting duplicate identifiers, and confirming that updates and deletions produce the correct results. I rerun tests after changes to check for regressions. Input validation supports reliability, but passing unit tests does not prove that software is secure. Security also requires code review, appropriate access controls, and testing for potential vulnerabilities.

### How do I interpret user needs and incorporate them into a program?

I translate user needs into specific rules that can be implemented and tested. For example, a requirement for a ten-digit phone number becomes a validation rule with tests for valid numbers, incorrect lengths, and letters. I also identify the operations users need, such as adding, updating, and deleting contacts, and check that each operation behaves as required. When a requirement is unclear, I would clarify the expected behavior before making assumptions.

### How do I approach designing software?

I begin by reviewing the requirements and dividing the program into classes with clear responsibilities. In this project, the Contact class manages contact information and validation, while ContactService manages operations on the collection of contacts. I build and test smaller parts before expanding the program. This approach helps me locate defects, keep the code understandable, and make changes without unnecessarily affecting other features.
