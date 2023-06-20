

# Intro
Testing as part of the overal software development process.


# Test Model 

|Test Model | Description | Advantages            | Disadvantages                 |
|-----------|-------------|-----------------------|-------------------------------|
| V-model | A linear model where each phase of development is completed before moving onto the next phase, with testing at each stage | - Improves quality as testing occurs at each stage, leading to fewer defects in later phases<br>- Good for linear projects where requirements are well understood | - Rigid, less suitable for projects with evolving requirements<br>- Difficult to make changes once a stage has been completed |
| Iterative model | A cyclic model where a small set of requirements is developed and tested in each iteration, gradually building up the full system | - Good for projects with evolving requirements<br>- Allows for early testing and feedback<br>- Easier to make changes | - May not work well for projects with fixed deadlines or budgets<br>- May require more resources or time due to the iterative nature |

# Testing levels
|Testing Level|Definition|Testing Level2|Purpose|Preformed by|
|:----|:----|:----|:----|:----|
|Component Testing|The testing of individual components or modules of an application, typically performed by developers using unit testing frameworks.|Unit level|To detect and fix defects in code at an early stage in the development process.|developer|
|Integration Testing|The testing of the interactions and interfaces between individual components or modules of an application, typically performed by developers or dedicated integration testers.|Integration level|To detect and fix defects in the interactions and interfaces between components before they are deployed to a production environment.|component integration by developer / system integration by tester (func or non-func)|
|System Testing|The testing of the complete and integrated system, typically performed by dedicated testing teams.|System level|To test that the system meets all functional and non-functional requirements and that it behaves correctly under expected and unexpected conditions.|tester|
|Acceptance Testing|The testing of the system by end users or stakeholders to determine whether or not it meets their business requirements and is fit for purpose.|User Acceptance level|To ensure that the system is ready for deployment to a production environment and meets the needs of the end users.|user/tester/customer|

# Test Types

| Test Type | Definition | Category | Purpose |
|-----------|------------|----------|---------|
| Unit testing | Testing of individual units or components of the application code | Functional testing | To ensure individual units are functioning properly |
| Integration testing | Testing of integrated units or components of the application code | Functional testing | To ensure different modules work together as expected |
| System testing | Testing the entire system as a whole | Functional testing | To ensure the whole system functions correctly |
| Acceptance testing | Testing by end-users or stakeholders to test if meets user requirements | Functional testing | To ensure system meets user expectations |
| Performance testing | Testing for responsiveness, speed, and stability of the system | Non-functional testing | To ensure the system performs well under expected load |
| Security testing | Testing the application or system for security vulnerabilities | Non-functional testing | To ensure the system is protected from unauthorized access |
| Usability testing | Testing the ease of use and user interface design of the system | Non-functional testing | To ensure the system is user-friendly |
| White-box testing | Testing the internal workings of an application | White-box testing | To ensure all code paths have been tested |
| Regression testing | Testing for changes or new additions to functionality do not break existing code | Testing after code has been changed | To ensure the stability of the system after changes |


