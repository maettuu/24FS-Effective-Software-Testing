# 24FS Effective Software Testing (EST)
This repository includes the practical assignments of the course EST. All code is written in `Java 11`.

## Assignment 1: Effective and Systematic Software Testing
Each of the eight exercises contains a problem description. For each problem test cases are composed to detect bugs in the code provided. This is achieved following the principles of *specification-based*, *structural* and *mutation testing*. For *structural testing* the [JaCoCo plugin](https://www.eclemma.org/jacoco/trunk/doc/maven.html) is used. *Mutation testing* is done using [PItest](https://pitest.org/quickstart/maven/). Test reports are included for each exercise. Furthermore, the [Documentation file](./assignment-1/Documentation.md) includes bug reports, implementation decisions and test coverage results.

Includes dependencies: `JUnit`, `JaCoCo`, `PItest`

## Assignment 2: Contracts and Property-Based Testing
For the exercises in this assignment tests to achieve 100\% line coverage are constructed. Furthermore, contracts for each problem are designed and documented including pre-conditions, post-conditions and invariants. Next, a test suite is implemented to verify that these contracts are correctly enforced. Finally, *property-based testing* techniques are applied to derive tests for the provided code. This is achieved using the [jqwik framework](https://jqwik.net/docs/current/user-guide.html#maven). Test reports as well as jqwik's logs are included for each exercise. Furthermore, the [Documentation file](./assignment-2/Documentation.md) includes design choices, testing strategies and assumptions made.

Includes dependencies: `JUnit`, `JaCoCo`, `jqwik`, `Guava`

## Assignment 3: Test Doubles and Mocks
The last assignment deals with designing for testability as well as mocking of services. For each exercise unit tests are composed to achieve a high test coverage. To deal with external services the [mockito framework](https://site.mockito.org/) is used. Test results are included for each exercise. Furthermore, the [Documentation file](./assignment-3/Documentation.md) includes implementation decisions, testing strategies and assumptions made.

Includes dependencies: `JUnit`, `AssertJ`, `Mockito`
