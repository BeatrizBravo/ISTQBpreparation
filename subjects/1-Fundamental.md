**Content:**
 <a id="x"></a>

- [Introduction](#1)
- [Typical Objetives of Testing](#200)
- [Testing and debugging](#2)
- [verification and validation](#202)
- [Regression and retesting](#3)
- [Testing Principle](#4)
- [Entry Criteria and Exit Criteria](#5)
- [Test process of Testing](#10)
  - [Organizational test process](#11)
  - [Definition](#12)
  - [Tasks](#13)
  - [Work products](#14)

- [Comparing test activities:](#6)
  - [Test activities of analysis and design](#7)
  - [Test activities of analysis, design and implementation](#8)
  - [Test activities of implementation and execution](#9)
- [Questions](#100)


 <a id="1"></a>

# Intro

It is true that people are fallible and can make mistakes. 
```
Effect of an:

├── Error /mistake/Blunder
    ├── Defect / Bug/Fault/ Flaw
        ├── Failure /Malfunction/Breakdown


```
There are other reason why system fail and can affect the operation of hardware and firmware and lead to system failure. Then can lead to:
- loss of money
- loss of time
- loss of business reputation
- injury
- death




|TRUE|FALSE|
|:----|:----|
|Failures can be caused by environmental conditions such as radiation|A defect is produced as a result of system failure|
|Defects, bugs and faults are the same thing|Failures can cause bugs|
| |Faults always cause system failures|

<br>

[Back to content](#x)




<a id="200"></a>

# Typical Objetives of Testing

(from most important to least)

- **Prevent defects** by evaluating work products such as requirements, user stories, design, and code.
- _Verify_ whether all specified requirements have been fulfilled.
- _Validate_ if the test object works as users and other stakeholders expect Build confidence in the quality level.
- Find defects and failures by reducing the level of risk of inadequate software quality.
- Provide sufficient information to stakeholders to allow them to make informed decisions (regarding the level of quality)
- Comply with contractual, legal, or regulatory requirements or standards.
<br>

[Back to content](#x)


<a id="2"></a>

# Testing and debugging


| testing                                                                                                   | debugging                                                                                                    |
|:----------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------|
| Identifies failures  (determine whether it satisfies the specified    requirements)      |  Investigates the cause of a fault (root cause)                                                              |
| performed **before** debugging and focuses on verifying that the system meets the specified requirements. | performed **after** testing focuses on identifying and resolving defects or issues in a system or component. |
| It involves designing and executing test cases to uncover defects or issues.                              | It involves analyzing and fixing defects by modifying code, data, or configurations.                         |
| Confirms whether a failure has been fixed                                                                 |  Fixes software if necessary                                                                                 |
|                                                                                                           | Checks the defect has been fixed                                                                             |
|                                                                                                           | Steps through program code                                                                                   |
|                                                                                                           |                                                                                                              |
| --                                                                                                        | --                                                                                                           |
| by the tester                                                                                             | by the developer                                                                                             |

<br>





[Back to content](#x)

<a id="202"></a>

# verification and validation
| Verification                                                                                                                                                                                | Validation                                                                                                                                                                                                                              |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Focuses on checking whether the software meets specified requirements and operates correctly according to its design and intended use.                                                      | Focuses on evaluating the software to ensure that it satisfies the user's needs and expectations.                                                                                                                                       |
| to ensure compliance with standards and specifications                                                                                                                                      | to validate its behavior and functionality.                                                                                                                                                                                             |
| Performed throughout the SDLC to catch defects early and prevent them from propagating to later stages.                                                                                     | to validate its behavior and functionality.                                                                                                                                                                                             |
| Actities:                                                                                                                                                                                   | Actities:                                                                                                                                                                                                                               |
| Static testing      **[type of reviews](https://github.com/BeatrizBravo/ISTQBpreparation/blob/main/subjects/3-static-testing.md#type-of-review)** (reviews, walkthroughs, and inspections.) | Testing levels **[type of reviews](https://github.com/BeatrizBravo/ISTQBpreparation/blob/main/subjects/2-Life-cycles.md#testing-levels)**  (system testing, acceptance testing, and user acceptance testing.)  preformed by the tester. |


[Back to content](#x)

<a id="3"></a>

# Regression and retesting


|REGRESSION|RETESTING|
|:----|:----|
|Regression testing is checking that there are no additional problems in previously tested software. |retesting is demonstrating that the reported defect has been fixed.|

[Back to content](#x)

 <a id="4"></a>

# Testing Principles


|Testing Principles|Description|
|:----|:----|
|Testing shows the presence of defects|Testing can show that defects are present, but it cannot prove that there are no defects. Even with thorough testing, it is possible that some defects may remain undetected.|
|Absence of Error Fallacy|Finding and fixing defects does not necessarily mean that the system is ready for release or will meet the needs of its users.Just because a system does not have any known defects does not mean that it is fit for its intended purpose.It is important to focus on fulfilling the requirements and meeting the needs of the users, rather than just finding and fixing defects.|
|Exhaustive testing is impossible|It is not possible to test all possible combinations of inputs and preconditions due to the large number of possibilities.Therefore, it is not possible to find all defects in a system through testing.|

[Back to content](#x)

<a id="5"></a>

# Entry Criteria and Exit Criteria
 


|Entry Criteria|Exit Criteria|
|:----|:----|
|Pre-requisite condition for testing|Post-testing condition|
|Defines when to start testing|Indicates when to stop testing|
|Deals with basic scenarios of testing|Deals with conditions outside basic scopes|
|Points out what should be tested and when to start testing|Gives warning about what problems still exist in an application even after completing all tests|

[Back to content](#x)

<a id="10"></a>


# Test process


<a id="11"></a>

## Organizational test process:
| Organizational test process: | |
|:-----------------------------|:----|
| Test ACTIVITY  and TASK      |WORK|
| Test WORK product            |OUTPUT|
| Traceability                 |relation throughout the test process btw each element test basis and|


[Back to content](#x)

<a id="12"></a>


|Definition| | | |                                                                                                                                                                                                                                                                                                                                                                                 | | |
|:----|:----|:----|:----|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----|:----|
|Test planning|Test Monitoring and Test Control|Test Analysis|Test desing| Test implementation                                                                                                                                                                                                                                                                                                                                                             |Test execution|test completion|
|Defining test objetive<br>Defining test approach (achieve CONTEXTUAL factor that INFLUENCE the test process)<br>updating PLAN bse on feedback|on-going COMPARASION of actual progress AGAINTS planned progress, using metrics define in the test plan => Are we on track?<br><br>control taking actions necessary to meet the objetive of the test plan => are we doingi alrigh?<br>both = SUPORTED by evaluation of EXIT CRITERIA -defintion of done (checking, assessing , determining if more test are needed)<br><br>COMUNICATION to STAKEHOLDERS (test progress against the plan, deviations from te plan and infromation to support any decision to stop testing.|Test basis is analyzed ( - testable feature, - associated with test condition, )<br><br>Identify testable feature<br> Define test conditions|During test design, the test conditions are elaborated into:  - high-level test cases,  - sets of high-level test cases, and  - other testware<br><br>How to test? (test condition are elaborated into hing-level test cases and Identification of defects in the test baseis)| During test implementation, the testware necessary for test execution is created and/or completed, including sequencing the test cases into test procedures.<br><br>Have everyting to test? (Testware necessary for test execution is created and/or completed, Sequencing the test cases into test procedures (low level test case), Test scripts,Is everything there to test?) |During test execution, test suites are run in accordance with the test execution schedule.<br><br>Are all test run? (test suit are run, compare and evaluate results)|Data  & expereince is collected.|


[Back to content](#x)

<a id="13"></a>

## Tasks

|Test planning|Test Monitoring and Test Control|Test Analysis|Test desing|Test implementation|Test execution|test completion|
|:----|:----|:----|:----|:----|:----|:----|
|Deciding on entry and exit criteria| | - Analyse the test basis appropriate to the test level being considered| - Designing and prioritizing test cases and sets of test cases| - Developing and prioritizing test procedures, and, potentially, creating automated test scripts| - Recording the IDs and versions of the test item(s) or test object, test tool(s), and testware| - Checking whether all defect reports are closed,|
|Evaluating the test estimate| |  - Evaluating the test basis and test items to identify defects of various types.| - Identifying necessary test data to support test conditions and test cases| - Creating test suites from the test procedures and (if any) automated test scripts| - Executing tests either manually or by using test execution tools| - Creating a test summary report to be communicated to stakeholders|
|Planning: WHEN and HOW to test and deciding HOW  the test result will be evaluated.| | - Identifying features and sets of features to be tested (content to test)| - Designing the test environment an Identify any required infrastructure and tools| - Test suit| - Comparing actual results with expected results| - Finalizing and archiving the test environment, the test data, the test infrastructure, and other testware for later reuse|
| | | - Define an prioritize test conditions for each feature based on analysis of the test basis| |  - grouping  the test case in certain order| - Analyzing anomalies to establish their likely causes| - Handing over the testware to the maintenance teams, other project teams, and/or other stakeholders who could benefit from its use|
| | | | | - Arranging the test suites within a test execution schedule in a way that results in efficient test execution| - Reporting defects based on the failures observed| - Analyzing lessons learned from the completed test activities to determine changes needed for future iterations, releases, and projects|
| | | | | - Building the test environment (including, potentially, test harnesses, service virtualization, simulators, and other infrastructure items) and verifying that| - Logging the outcome Of test execution (e.g., pass, fail, blocked)| - Using the information gathered to improve test progress maturity|
| | | | | - everything needed has been set up correctly| - Repeating test activities either as a result Of action taken for an anomaly, or as part of the| |
| | | | | - Preparing test data and ensuring it is properly loaded in the test environment|planned testing| |
| | | | | | | |
| | | - Capturing bi-directional traceability between test basis and test conditions| - Capturing bi-directional traceability between the basis, test conditions, and test cases| - Verifying and updating bi-directional traceability between the test conditions, tst cases, test procedure, and test suites.| - Verifying and updating bi-directional traceability between the test basis, test conditions, test cases, test procedures, and test results| |


[Back to content](#x)

<a id="14"></a>

| Work Product                                                                               |                                                                            |                                         |                                            |                                                                                                |                                                                                                                                              |                                               |
|:-------------------------|:----------------------------------------------------------------|:----------------------------------------|:-------------------------------------------|:------------------------------------------------|:-------------------------|:----------------------------------------------|
| Test planning            | Test Monitoring and Control                                    | Test Analysis                           | Test desing                         | Test implementation                | Test execution                                | test completion                               |
| Test planning                                                                              | TEST PROGRESS REPORTS                                                      | Defined and prioritized test conditions | Test cases and sets of test cases.         | Test procedures and the sequencing of those test procedures.                                   | Documentation of the status of individual test cases or test procedures (e.g., ready to run, pass, fail, blocked,deliberately skipped, etc.) | Test summary reports                          |
| Test Plans                                                                                 | TEST SUMMARY REPORTS                                                       | Creation of test charters               |                                            |                                                                                                |                                                                                                                                              |                                               |
| (A test charter provides the test conditions to cover during a time-boxed testing session) | Design and/or identification of the test data                              | Test suites.                            | Defect reports                             | Action items for improvement of subsequent projects or iterations                              |                                                                                                                                              |                                               |
| Exit Criteria                                                                              | Audience relevant report and report addressing project management concerns | Defects in the test basis               | Identification of infrastructure and tools | A test execution schedule.                                                                     | Documentation about which test item(s), test object(s), test tools and testware were involved in the  testing                                | Change requests or product backlog items, and |
|                                                                                            |                                                                            |                                         | Design of the test environment             | Service virtualization and automated test scripts.                                             | Comparing actual results with expected results                                                                                               | Finalized testware                            |
|                                                                                            |                                                                            |                                         |                                            | Creation and verification of test data is properly loaded into  the test environment.          |                                                                                                                                              |                                               |
|                                                                                            |                                                                            |                                         |                                            | Test conditions defined in test analysis maybe for the further refiened in test implementation |                                                                                                                                              |                                               |
|                                                                                            |                                                                            | Hight level of test cases               | Hight level of test cases                  | LOWER level of test cases                                                                      |                                                                                                                                              |                                               |
|                                                                                            |                                                                            |                                         |                                            |                                                                                                | Verifying and updating bi-directional traceability between the test basis, test conditions, test cases, test procedures and test results     |                                               |













 <a id="6"></a>

# Comparing test activities:


<a id="7"></a>

 ## Test activities of analysis and design

|Test activities|ANALYSIS|DESIGN|
|:----|:----|:----|
|Designing test cases| |x|
|Prioritized test conditions|x| |
|prioritizing test cases| |x|
|Identifying test conditions|x| |
|Identifying necessary test data to support test cases| |x|
|Identifying necessary test data to support test conditions| |x|
|Designing the test environment| |x|
|Identifying features and sets of features to be tested|x| |
|Evaluating the test basis and test items to identify defects of various types|x| |
|Capturing bi-directional traceability between the test basis, test conditions, and test cases| |x|
|Capturing bi-directional traceability between each element of the test basis and the associated test conditions|x| |



[Back to content](#x)

<a id="8"></a>

## Test activities of analysis, design and implementation

|Test activities|ANALYSIS|DESIGN| IMPLEMENTATION |
|:----|:----|:----|:---------------|
|Creating test suites| | | x              |
|Developing test procedures,| | | x              |
|Service virtualization| | | x              |
|Verifying that everything needed has been set up correctly| | | x              |
|Identifying necessary test data to support test cases| |x|                |
|Building test harnesses and simulators| | | x              |
|Designing the test environment| |x|                |
|Verifying that everything needed has been set up correctly| | | x              |
|Evaluating the test basis and test items to identify defects of various types|x| |                |
|Capturing bi-directional traceability between the test basis, test conditions, and test cases| |x|                |
|Capturing bi-directional traceability between each element of the test basis and the associated test conditions|x| |                |

 <a id="9"></a>
 
[Back to content](#x)

## Test activities of implementation and execution

| Test activities                                                               | Implementation | Execution | 
|:------------------------------------------------------------------------------|:---------------|:----------|
| Developing test procedures, and. potentially, creating automated test scripts | x              |           |
| Logging the outcome of test execution                                         |                | x         |
| Executing tests manually                                                      |                | x         |
| Creating test suites from the test procedures                                 | x              |           |
| Repeating test activities either as a result of action taken for an anomaly   |                | x         |
| Prioritizing test procedures                                                  | x              |           |
| Preparing test data                                                           | x              |           |
| Comparing actual results with expected results                                |                | x         |
| Ensuring it is properly loaded in the test environment                        | x              |           |

[Back to content](#x)

<a id="100"></a>

# Questions 

| questions                                                                                                      |answeres|
|:---------------------------------------------------------------------------------------------------------------|:----|
| Describe the interaction between errors, defect and failures.-                                                 |ERROR: An error is a HUMAN MISTAKE that can occur during the development process. It can be a mistake in the program code or in a document.<br>DEFECT: An error can produce a DEFECT (also known as a FAULT or BUG) in the program code, software, system or document.<br>FAILURE: If a DEFECT in the code is executed, the SYSTEM may FAIL to do what it should do (or do something it shouldn’t), CAUSING a FAILURE. Not all defects result in failures.<br>An error can lead to a defect, and when these defects go undetected, they can lead to failure.|
| Software failures can cause losses. Give 3 consequences of software failure.-                                  |FINANCIAL LOSS: Software failure can result in severe financial loss for the company due to loss of usage, loss of revenue, and the cost of making things right for the customers.<br>DAMAGE TO REPUTATION: Software failure can result in bad reviews, bad press, and brand damage which can have a long-term impact on the company’s reputation.<br>LOSS OF CUSTOMERS: Software failure can result in losses to competitors as customers may switch to alternative solutions.|
| what are the vertices of the 'triangle of resources'?                                                          |The “triangle of resources” in software development represents the three major factors/constraints that must be balanced in a software development project.<br>&nbsp; &nbsp; &nbsp;   -QUALITY or SCOPE (what must be built), <br>&nbsp; &nbsp; &nbsp;   -TIME or SCHEDULE (when it must be built by), and <br>&nbsp; &nbsp; &nbsp;   -MONEY or RESOURCES (how much it must cost).|
| Describe static testing and dynamic testing.                                                                   |TYPES of SOFTWARE TESTING:<br>**STATIC TESTING**: This type of testing involves REVIEWING the CODE, DOCUMENTATION, and other SOFTWARE ARTIFACTS without executing the code. The goal of static testing is to find ISSUES early in the DEVELOPMENT PROCESS, when they are easier and less expensive to fix. <br>common static testing techniques include:<br>&nbsp; &nbsp; &nbsp;   -CODE REVIEWS<br>&nbsp; &nbsp; &nbsp;   -WALKTHROUGHS<br>&nbsp; &nbsp; &nbsp;   -INSPECTIONS<br>&nbsp; &nbsp; &nbsp;   -STATIC ANALYSIS<br><br>**DYNAMIC TESTING**: This type of testing involves EXECUTING the CODE and OBSERVING its BEHAVIOR. The goal of dynamic testing is to find ISSUES that only become apparent when the code is RUN. <br>common dynamic testing techniques include:<br>&nbsp; &nbsp; &nbsp;   -UNIT TESTING<br>&nbsp; &nbsp; &nbsp;   -INTEGRATION TESTING<br>&nbsp; &nbsp; &nbsp;   -SYSTEM TESTING<br>&nbsp; &nbsp; &nbsp;   -ACCEPTANCE TESTING|
| <br>[Back to content](#x)<br>                                                                                  |        |
| What is debugging?                                                                                             |DEBUGGING is the process of GO through the code  to IDENTIFY and REMOVE ERRORS from SOFTWARE. <br><br>DEBUGGING is the process of FINDING and RESOLVING BUGS (defects or problems that prevent correct operation) within computer programs, software, or systems.<br>DEBUGGING - is something a programmer does to FIND the ROOT CAUSE of a bug. <br>Root cause - why the defect came about.|
| what other elements apart from 'test execution' are included in 'testing'?                                     |TESTING is the process of EVALUATING and VERIFYING that a SOFTWARE PRODUCT or APPLICATION does what it is supposed to do. <br>The benefits of TESTING include PREVENTING BUGS, REDUCING DEVELOPMENT COSTS and IMPROVING PERFORMANCE. <br>There are many different types of SOFTWARE TESTS, each with specific OBJECTIVES and STRATEGIES. <br><br>Apart from TEST EXECUTION, other elements included in TESTING are:<br>&nbsp; &nbsp; &nbsp; -ACCEPTANCE TESTING: Verifying whether the whole system works as intended.<br>&nbsp; &nbsp; &nbsp; -INTEGRATION TESTING: Ensuring that software components or functions operate together.<br>&nbsp; &nbsp; &nbsp; -UNIT TESTING: Validating that each software unit performs as expected.<br>&nbsp; &nbsp; &nbsp; -FUNCTIONAL TESTING: Checking functions by emulating business scenarios, based on functional requirements.<br>&nbsp; &nbsp; &nbsp; -PERFORMANCE TESTING: Testing how the software performs under different workloads.<br>&nbsp; &nbsp; &nbsp; -REGRESSION TESTING: Checking whether new features break or degrade functionality.<br>&nbsp; &nbsp; &nbsp; -STRESS TESTING: Testing how much strain the system can take before it fails.<br>&nbsp; &nbsp; &nbsp; -USABILITY TESTING: Validating how well a customer can use a system or web application to complete a task.|
| why is 'zero defects' an insufficient guide to software quality?                                               |Zero defects is a philosophy that reinforces the notion that defects are not acceptable and that everyone should “do things right the first time”.<br> However, striving for zero defects can be insufficient guidance to software quality for several reasons:<br>&nbsp; &nbsp; &nbsp; •Any piece of modern commercial software is infinitely complex, and the ways in which it can interact with itself or its environment are also infinite. It’s only possible to find every defect if you have an infinite amount of time to test .<br>&nbsp; &nbsp; &nbsp; •Even if you could find every last defect the first time around, you wouldn’t have time to fix them all and ship a product this century—time-to-market is a real thing. So even if found, you will have to ship with them .<br>&nbsp; &nbsp; &nbsp; •The motivation behind the zero-defect mantra is not wrong in itself. It’s just been misdirected from its true target. Make that adjustment, and meaningful, measurable definitions of acceptable software quality become possible.<br><br>Any piece of modern commercial software is infinitely complex, and the ways in which it can interact with itself or its environment are also infinite. It’s only possible to find every defect if you have an infinite amount of time to test <br>Even if you could find every last defect the first time around, you wouldn’t have time to fix them all and ship a product this century—time-to-market is a real thing. So even if found, you will have to ship with them <br>The motivation behind the zero-defect mantra is not wrong in itself. It’s just been misdirected from its true target. Make that adjustment, and meaningful, measurable definitions of acceptable software quality become possible <br>Remember, you are learning testing to achieve ISTQB Foundation level certification.|
| give 3 reasons why defect clustering may exist.                                                                |DEFECT CLUSTERING refers to the situation where a SMALL NUMBER of MODULES or FEATURES in an APPLICATION contain the MAJORITY of the DEFECTS. <br>Pareto Principle: 80% of problems are found in 20% of each of the following module:<br>Here are THREE reasons why DEFECT CLUSTERING may exist:<br>&nbsp; &nbsp; &nbsp; -System Complexity (erratic third-party integrations)<br>&nbsp; &nbsp; &nbsp;-Volatile Code <br>&nbsp; &nbsp; &nbsp; -Effects of change on change (older code, new featuares)<br>&nbsp; &nbsp; &nbsp; -Development staff experience/inexperience|
| Briefly justify the idea of early testing.                                                                     |The idea of EARLY TESTING is to start TESTING as early as possible in the SOFTWARE DEVELOPMENT LIFE CYCLE (SDLC). <br>This helps to Reduce Cost to CAPTURE and ELIMINATE DEFECTS in the early stages of SDLC, such as during the ANALYSIS and DESIGN PHASES. <br><br>Some BENEFITS of EARLY TESTING:<br>&nbsp; &nbsp; &nbsp; - REDUCES DEFECTS: EARLY TESTING helps to REDUCE the NUMBER of DEFECTS and ultimately the REWORK COST in the end.<br>&nbsp; &nbsp; &nbsp; - COST REDUCTION: EARLY TESTING can help REDUCE COSTS by DETECTING ISSUES earlier in the DEVELOPMENT PROCESS.<br>&nbsp; &nbsp; &nbsp; - BETTER PERFORMANCE: EARLY TESTING can help ENSURE BETTER PERFORMANCE of the CODE from an EARLY STAGE."|
|   <br>[Back to content](#x)<br>                                                                                                                |        |
| What are the activity groups in the generalised test process described (in the correct sequence)               |TEST PROCESS consists of seven main groups of ACTIVITIES in the correct sequence:<br>&nbsp; &nbsp; &nbsp;   1.TEST PLANNING<br>&nbsp; &nbsp; &nbsp;   2.TEST MONITORING and CONTROL<br>&nbsp; &nbsp; &nbsp;   3.TEST ANALYSIS<br>&nbsp; &nbsp; &nbsp;   4.TEST DESIGN<br>&nbsp; &nbsp; &nbsp;   5.TEST IMPLEMENTATION<br>&nbsp; &nbsp; &nbsp;   6.TEST EXECUTION<br>&nbsp; &nbsp; &nbsp;   7.TEST COMPLETION|
| Give advantages of maintaining traceability between the test basis and test work products (include test cases) |ADVNTAGES are:<br>&nbsp; &nbsp; &nbsp; - Analysing the impact of changes<br>&nbsp; &nbsp; &nbsp; - Making testing auditable<br>&nbsp; &nbsp; &nbsp; - Meeting IT governance criteria<br>&nbsp; &nbsp; &nbsp; - Improving the understandability of test progress reports and test summary reports to include the status of elements of the test basis(requirements that passed their tests, requirements that failed their tests, and requirements that have pendingtests)<br>&nbsp; &nbsp; &nbsp; - Relating the technical aspects of testing to stakeholders in terms that they can understand<br>&nbsp; &nbsp; &nbsp; - Providing information to assess product quality, process capability, and project progress against business goals|
| When should the expected outcome of a test to be defined?                                                      |During the TEST DESIGN phase, testers will:<br>&nbsp; &nbsp; &nbsp;  -generate a set of input values and <br>&nbsp; &nbsp; &nbsp;  -predict the expected outcomes <br><br>by identifying FROM the specification WHAT should happen WHEN those input values are applied. <br>This process helps to ensure that the test is designed to effectively verify the behavior of the software under test.<br>EX. identifying from the specification what should happen when those input values are applied.|
| Give 3 work products that are created during the test execution group of activities.                           |*DOCUMENTATION of the STATUS of individual test cases or test procedures (EX:ready to run, pass, fail, blocked,deliberately skipped, etc.)<br>*DEFECT REPORTS<br>*DOCUMENTATION about which test item(s), test object(s), test tools and testware WERE INVOLVED in the  testing<br>*COMPARING actual results with expected results<br>*VERIFYING and UPDATING bi-directional traceability between the test basis, test conditions, test cases, test procedures and test results|
| Describe ways in which testers and developers think differently.                                               |Developer     “How can I make the application?”    BUILDER mindset<br>&nbsp; &nbsp; &nbsp;    - to design and build a product<br>&nbsp; &nbsp; &nbsp;    - Designing and building solutions<br>&nbsp; &nbsp; &nbsp;    - Confirmation bias makes IT difficult to find mistakes in their own work<br><br> Tester    “Does it work - how can I brake it?”   CRITIC mindset<br>&nbsp; &nbsp; &nbsp;    - Verifying and validating the product<br>&nbsp; &nbsp; &nbsp;    - Curiosity, a critical EYE, attention to detail<br>&nbsp; &nbsp; &nbsp;    - Motivation for good and positive communications and relationships|
| Contrast the advantages and disadvantages of developers testing their own code.                                |Advantages:<br>&nbsp; &nbsp; &nbsp;-Developers are familiar with the code they have written and can quickly:<br>    identify and FIX problems or defects as SOON as they are discovered (avoid extensive error logs)<br>&nbsp; &nbsp; &nbsp;-Testing their own code can help developers improve their understanding of the code and its behavior<br><br>Disadvantages:<br>&nbsp; &nbsp; &nbsp; It can be difficult for developers to find their own mistakes  = CONFIRMATION BIAS<br>&nbsp; &nbsp; &nbsp; Developers may have a limited understanding of the ENTIRE application and may not be able to test all possible scenarios.|
| Suggest 3 ways that confrontation can be avoided.                                                              |GOOD communication, and work on team building. <br>COMUNICATION needs to be OBJETIVE, and expressed in IMPERSONAL ways:<br>&nbsp; &nbsp; &nbsp; * Keep the focus on delivering a quality product.<br>&nbsp; &nbsp; &nbsp; * Results should be presented in a non-personal way. <br>&nbsp; &nbsp; &nbsp; * Attempt to understand how others feel;<br>&nbsp; &nbsp; &nbsp; * At the end of discussions, confirm that you have both understood and been understood.|


[Back to content](#x)