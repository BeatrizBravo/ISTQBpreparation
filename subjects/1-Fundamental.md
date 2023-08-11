**Content:**
 <a id="x"></a>

- [Introduction](#1)
- [Testing and debugging](#2)
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

<br>

[Back to content](#x)


<a id="2"></a>

# Testing and debugging


|testing |debugging|
|:----|:----|
|Identifies failures| Investigates the cause of a fault (root cause)|
|Confirms whether a failure has been fixed| Fixes software if necessary|
| |Checks the defect has been fixed|
| |Steps through program code|
|-- |-- |
| by the tester |by the developer |

<br>

|TRUE|FALSE|
|:----|:----|
|Failures can be caused by environmental conditions such as radiation|A defect is produced as a result of system failure|
|Defects, bugs and faults are the same thing|Failures can cause bugs|
| |Faults always cause system failures|

<br>

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

[Back to content](#x)

<a id="11"></a>

## Organizational test process:
| Organizational test process: | |
|:-----------------------------|:----|
| Test ACTIVITY  and TASK      |WORK|
| Test WORK product            |OUTPUT|
| Traceability                 |relation throughout the test process btw each element test basis and|


[Back to content](#x)

<a id="12"></a>


|Definition| | | | | | |
|:----|:----|:----|:----|:----|:----|:----|
|Test planning|Test Monitoring and Test Control|Test Analysis|Test desing|Test implementation|Test execution|test completion|
|Defining test objetive<br>Defining test approach (achieve CONTEXTUAL factor that INFLUENCE the test process)<br>updating PLAN bse on feedback|on-going COMPARASION of actual progress AGAINTS planned progress, using metrics define in the test plan => Are we on track?<br><br>control taking actions necessary to meet the objetive of the test plan => are we doingi alrigh?<br>both = SUPORTED by evaluation of EXIT CRITERIA -defintion of done (checking, assessing , determining if more test are needed)<br><br>COMUNICATION to STAKEHOLDERS (test progress against the plan, deviations from te plan and infromation to support any decision to stop testing.|Test basis is analyzed ( - testable feature, - associated with test condition, )<br><br>Identify testable feature<br> Define test conditions|During test design, the test conditions are elaborated into:  - high-level test cases,  - sets of high-level test cases, and  - other testware<br><br>How to test? (test condition are elaborated into hing-level test cases and Identification of defects in the test baseis)|During test implementation, the testware necessary for test execution is created and/or completed, including sequencing the test cases into test procedures.<br><br>Have eveting to test? (Testware necessary for test execution is created and/or completed, Sequencing the test cases into test procedures (low level test case), Test scripts,Is everything there to test?)|During test execution, test suites are run in accordance with the test execution schedule.<br><br>Are all test run? (test suit are run, compare and evaluate results)|Data  & expereince is collected.|


[Back to content](#x)

<a id="13"></a>


|Task:| | | | | | |
|:----|:----|:----|:----|:----|:----|:----|
|Test planning|Test Monitoring and Test Control|Test Analysis|Test desing|Test implementation|Test execution|test completion|
|Deciding on entry and exit criteria| | - Analyse the test basis appropriate to the test level| - Designing and prioritizing test cases and sets of test cases| - Developing and prioritizing test procedures, and, potentially, creating automated test scripts| - Recording the IDs and versions of the test item(s) or test object, test tool(s), and testware| - Checking whether all defect reports are closed,|
|Evaluating the test estimate| |being considered| - Identifying necessary test data to support test conditions and test cases| - Creating test suites from the test procedures and (if any) automated test scripts| - Executing tests either manually or by using test execution tools| - Creating a test summary report to be communicated to stakeholders|
|Planning: WHEN and HOW to test and deciding HOW  the test result will be evaluated.| | - Evaluating the test basis and test items to identify| - Designing the test environment an Identify any required infrastructure and tools|    - Test suit| - Comparing actual results with expected results| - Finalizing and archiving the test environment, the test data, the test infrastructure, and other testware for later reuse|
| | |defects of various types| - Capturing bi-directional traceability between the basis, test conditions, and test cases|        - grouping  the test case in certain order| - Analyzing anomalies to establish their likely causes| - Handing over the testware to the maintenance teams, other project teams, and/or other stakeholders who could benefit from its use|
| | | - Identifying features and sets of features to| | - Arranging the test suites within a test execution schedule in a way that results in efficient test execution| - Reporting defects based on the failures observed| - Analyzing lessons learned from the completed test activities to determine changes needed for future iterations, releases, and projects|
| | |be tested (content to test)| | - Building the test environment (including, potentially, test harnesses, service virtualization, simulators, and other infrastructure items) and verifying that| - Logging the outcome Of test execution (e.g., pass, fail, blocked)| - Using the information gathered to improve test progress maturity|
| | | - Define an prioritize test conditions for each| | - everything needed has been set up correctly| - Repeating test activities either as a result Of action taken for an anomaly, or as part of the| |
| | |feature based on analysis of the test basis| | - Preparing test data and ensuring it is properly loaded in the test environment|planned testing| |
| | | - Capturing bi-directional traceability between test| | - Verifying and updating bi-directional traceability between the test conditions, tst cases, test procedure, and test suites.| - Verifying and updating bi-directional traceability between the test basis, test conditions, test cases, test procedures, and test results| |

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

