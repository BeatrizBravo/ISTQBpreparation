**Content:**
 - [Introduction](#1)
 - [Testing levels](#2)
 - [Test Types](#3)
 - [Questions](#4)

# Intro
Testing as part of the overall software development process.





     
     
<br>


# Test Model 
 <a id="1"></a>

|Test Model | Description | Advantages            | Disadvantages                 |Diagram|
|-----------|-------------|-----------------------|-------------------------------|-------|
| V-model | A linear model where each phase of development is completed before moving onto the next phase, with testing at each stage | - Improves quality as testing occurs at each stage, leading to fewer defects in later phases<br>- Good for linear projects where requirements are well understood | - Rigid, less suitable for projects with evolving requirements<br>- Difficult to make changes once a stage has been completed | ![v-model](https://www.tutorialscampus.com/sdlc/img/v-model.png "v-model")|
| Iterative model | A cyclic model where a small set of requirements is developed and tested in each iteration, gradually building up the full system | - Good for projects with evolving requirements<br>- Allows for early testing and feedback<br>- Easier to make changes | - May not work well for projects with fixed deadlines or budgets<br>- May require more resources or time due to the iterative nature | ![iterative-model](https://wishdesk.com/sites/default/files/inline-images/itterative-design-process.jpg "iterative-model")|


<!-- <img src="https://www.tutorialscampus.com/sdlc/img/v-model.png"  width="150" height="150"
     alt="v-model"
     style="float: left; margin-right: 10px;" />
<img src="https://www.researchgate.net/publication/338710620/figure/fig4/AS:849628610166790@1579578654482/SDLC-Iterative-Model-2.jpg"   
    width="350" height="150"
     alt="iterative-model"
     style=" margin-right: 10px;" /> -->

# Testing levels
 <a id="2"></a>
|Testing Level|Definition|Testing Level2|Purpose|Preformed by|
|:----|:----|:----|:----|:----|
|Component Testing|The testing of individual components or modules of an application, typically performed by developers using unit testing frameworks.|Unit level|To detect and fix defects in code at an early stage in the development process.|developer|
|Integration Testing|The testing of the interactions and interfaces between individual components or modules of an application, typically performed by developers or dedicated integration testers.|Integration level|To detect and fix defects in the interactions and interfaces between components before they are deployed to a production environment.|component integration by developer / system integration by tester (func or non-func)|
|System Testing|The testing of the complete and integrated system, typically performed by dedicated testing teams.|System level|To test that the system meets all functional and non-functional requirements and that it behaves correctly under expected and unexpected conditions.|tester|
|Acceptance Testing|The testing of the system by end users or stakeholders to determine whether or not it meets their business requirements and is fit for purpose.|User Acceptance level|To ensure that the system is ready for deployment to a production environment and meets the needs of the end users.|user/tester/customer|
![testing-level](https://www.softwaretestingclass.com/wp-content/uploads/2012/09/levels-of-testing.jpg "testing-level")

# Test Types
 <a id="3"></a>

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
![testing-type](https://qph.cf2.quoracdn.net/main-qimg-ad4946a45fa55aa801f397b2009371cc "testing-type")



# Questions 
<a id="4"></a>
|Life cycles questions |Answers|
|:----|:----|
|What is mean by verification?|Verification is the process of evaluating whether a system or component meets its specified requirements or not|
|What is meat by validation?|Validation is the process of evaluating whether a system or component meets the customer/user needs and expectations|
|Name 3 work products typically shown in the V model|Requirements specification, Test plan, and Acceptance criteria|
|Name 2 activities typically shown in the V model|Unit testing and System testing|
|Identify a benefit of the V model|Early detection of defects|
|Identify a benefit of the V model|Clear documentation and traceability|
|Name 3 activities typically associated with an interactive model|Prototyping, User feedback, and Incremental development|
|Identify a significant benefit of an interactive model|Early and frequent user involvement|
|List 3 challenges of interactive development|Scope creep, Lack of detailed documentation, and Difficulty in measuring progress|
| | |
|Compare the work product in the V model with those in an interactive model|In the V model, work products are developed sequentially whereas in the interactive model, work products are developed iteratively with frequent feedback from users|
|List 2 documents that could be used as the test basis for unit testing|Code and Unit Test Cases|
|Describe test driven development|Test-driven development is a software development process in which unit tests are written before the code is written to ensure that the code meets the requirements and passes the tests|
|Identify 2 typical test objects used for integration testing|database, infrastructure, interfaces, Apis, microservices and Subsystems|
|List 3 documents used as the test basis for system testing|System Requirements Specification, Design documents, and Use cases|
|Compare a functional requirement with a non-functional requirement|A functional requirement specifies what the system should do whereas a non-functional requirement specifies how well the system should do it|
|What is the purpose of acceptance testing?|The purpose of acceptance testing is provide de end users with confidence that the system will function according to their expectations. Also determine whether the system meets the customer/user requirements and can be accepted for deployment|
|List 3 documents used as a test basis for acceptance testing|User manuals, Acceptance criteria, and Business/process requirements|
| | |
|Identify 3 types of acceptance testing|User acceptance testing, Operational acceptance testing, and Contractual acceptance testing|
|How do functional requirements differ from non-functional requirement?|Functional requirements specify what the system should do whereas non-functional requirements specify how well the system should do it|
|For which type of testing is code coverage measured|Code coverage is commonly measured for unit testing as it helps to determine how much of the code has been exercised during the testing process.|
|What is the purpose of maintenance testing?|The purpose of maintenance testing is to ensure that a software system remains usable and effective over time. This involves making changes and updates to the system as necessary, and testing those changes to ensure they do not introduce new defects or problems.|
|Give examples of when maintenance testing?|Examples of when maintenance testing may be needed include: when new features or functionality are added to the system, when changes are made to the underlying infrastructure, when the system is moved to a new environment, or when issues or bugs are identified and need to be fixed.|

