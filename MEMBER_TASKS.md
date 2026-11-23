# Member 2 - Black-box and White-box Testing

## Assigned sections

- Section 3.3 - Black-box Testing
- Section 3.4 - White-box Testing

## Objective

Analyze the PublicCare application and prepare evidence-based black-box and white-box testing documentation.

## Section 3.3 - Black-box testing

Perform the following:

1. Select 2-3 important application features.
2. Apply Equivalence Partitioning.
3. Apply Boundary Value Analysis.
4. Prepare at least one Decision Table for a suitable business rule.
5. Derive test cases from the identified partitions, boundaries and decision rules.

Possible feature areas to investigate:
- Citizen registration and login
- Report creation and validation
- Report filtering and pagination
- Administrator status updates
- Report image upload

Use the RTM and existing test plan to identify actual requirements.

For every test case record:
- Test case ID
- Requirement ID
- Feature
- Input/condition
- Expected result
- Actual result
- Execution status
- Evidence reference

Do not claim a test passed unless it was executed.

## Section 3.4 - White-box testing

Inspect the actual source code.

1. Select suitable methods from the backend.
2. Draw control-flow graphs for selected methods.
3. Calculate Cyclomatic Complexity.
4. Explain the independent paths.
5. Measure statement coverage.
6. Measure branch coverage.
7. Record the test tool and execution command.

Use the existing JUnit tests as a starting point.

Investigate JaCoCo compatibility with the current Maven project before changing build configuration.

Do not report estimated coverage as measured coverage.

## Deliverables

- Equivalence Partitioning tables
- Boundary Value Analysis tables
- Decision Table
- Derived test cases
- Control-flow graphs
- Cyclomatic Complexity calculations
- Statement and branch coverage reports
- Screenshots/logs of actual execution
- Short explanation of findings and limitations

## Constraints

- Work only in your Member2 project copy.
- Do not modify the original project.
- Do not fabricate execution results.
- Clearly identify any test that cannot be executed.
- Keep source-code changes minimal and document them.
