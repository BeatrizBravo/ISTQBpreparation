
**Content:**
<a id="x"></a>

- [Independent Testing](#1)
- [Benefits of Test Independence](#2)
- [Typical test manager tasks and tester tasks](#3)
- [Test Strategy and Test Approach](#4)
- [Entry Criteria and Exit Criteria ](#5)
- [Test executuion Schedule ](#6)
- [Product vs Project Risk  ](#7)
- [Questions  ](#100)


|Independent Testing| | | | |
|:----|:----|:----|:----|:----|
|Low Level of Independence| | | |High Level of Independence|
|No independent testers |Independent developers or testers **within** development team|Independent Tester|Independent Tester|• Independent Tester|
|• Developers testing their own code| |• Same organization|• Same organization|• Different Organization|
| | |• Same Manager|• Different Manager| |


<a id="2"></a>

|Benefits of Test Independence|Drawbacks of Test Independence|
|:----|:----|
|Testers can provide an OBJECTIVE and UNBIASED view of the software quality and risks|Testers may be ISOLATED from the development team, leading to a lack of collaboration, delays in providing feedback, or an adversarial relationship|
|Testers can apply different SKILLS, EXPERIENCE, and PERSPECTIVES than the developers, leading to more effective and efficient testing|Testers may have LIMITED access to project information, resources, or support from the development team, leading to difficulties in understanding the requirements, design, or implementation|
|Testers can avoid the ASSUMPTIONS, OVERSIGHTS, or BLIND SPOTS that the developers may have, leading to more thorough and diverse testing|Testers may have HIGHER costs or overheads associated with test independence, such as hiring external testers, managing contracts, or transferring knowledge|


<a id="3"></a>

| Typical test manager tasks and tester tasks                                                                                                                                                                 | |
|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----|
|                                                                                                                                                                                                             | |
| Test Manager Tasks                                                                                                                                                                                          |Tester Tasks|
| Define the TEST STRATEGY and TEST APPROACH for the project based on the organizational test strategy and the project context                                                                                |Contribute to the TEST PLAN by reviewing and writing test plans and submitting plan documents for final review to the test manager|
| Manage and coordinate the TEST TEAM and their activities, including assigning tasks, monitoring progress, providing feedback, resolving issues and conflicts, and ensuring adequate skills and competencies |Analyze, review and assess USER REQUIREMENTS, stories, specifications, and acceptance criteria|
| Manage the TEST RESOURCES, such as test environments, test data, test tools, etc., and ensure their availability, suitability, security, and maintenance                                                    |Design, prioritize, implement and execute TEST CASES and TEST PROCEDURES based on the test basis and test objectives|
| Manage the TEST STAKEHOLDERS, such as customers, users, developers, sponsors, etc., and ensure effective communication, collaboration, reporting, and expectation management                                |Record and evaluate TEST RESULTS and report any defects or deviations from expected behavior|
| Manage the TEST PROCESS, such as planning, monitoring, controlling, evaluating, reporting, and improving the test activities and deliverables                                                               |Perform REGRESSION TESTING and RETESTING as needed after defect fixes or changes|
| Manage the TEST RISKS and issues that may affect the test objectives, scope, schedule, quality, or resources                                                                                                |Support other test levels or types, such as integration testing, system testing, acceptance testing, performance testing, etc., as needed|

[Back to content](#x)

<a id="4"></a>

| Test Strategy                                                                                       |Test Approach|
|:----------------------------------------------------------------------------------------------------|:----|
| **generalized** description of the test process                                                     |**tailors** the test strategy for a particular project or release. Help to select test techniques, levels and types and define test entry/exit criteria|
| types:                                                                                              |about the context and factors:|
| Analytical (some factor. Example Risk or requirement)                                               |Risk|
| Model-base (model/requirement of the product functinal or non-funct.)                               |safety|
| Methodical (use predefined set of test/conditions Example taxonomy                                  |available resouces and skills|
| Process compliant (rules/standars)                                                                  |technology|
| Directed (advice/instructins stakeholdes, business domain, etc)                                     |nature of the system|
| Regression-averse (reuse existing testware)                                                         |test objetives|
| reactive (event occurring during teste execution -> response -->knowloge gained -> explorative testing |regulation, etc.|


[Back to content](#x)

<a id="5"></a>

|Entry Criteria| Exit Criteria                                                                                                                                                                                                                                                                                                 |
|:----|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|PREREQUISITES/precondition that must be met **before test activities** can begin, such as **availability** of test basis, test plan, test environment, test data, test tools, other necessary resources.| CONDITIONS that **must be met** before  test level or a set of test is declare completed, such as achievement of test objectives, planned tests have been executed, defined level of coverage (#unresolved defect is within agreed limit/estimated remaining defects is sufficiently low, quality, or budget) |
|Entry criteria help to ensure that testing is PLANNED, PREPARED, and READY to start, and that the test items are stable and testable| Exit criteria help to ensure that testing is COMPLETED, EVALUATED, and REPORTED, and that the test items meet the stakeholder expectations and requirements                                                                                                                                                   |
|Agile: Definition of ready| Agile: definition of done                                                                                                                                                                                                                                                                                     |
Intro to [entry/exit criteria](https://github.com/BeatrizBravo/ISTQBpreparation/blob/main/subjects/1-Fundamental.md#5)


[Back to content](#x)

<a id="6"></a>

## Test executuion Schedule
Diference [Test script/case](https://github.com/BeatrizBravo/ISTQBpreparation/blob/main/subjects/4-test-disign-techniques.md#4)

|Factors|
|:------|
|prioritization|
|dependencies|
|confirmataion tests|
|regression test|
|sequence for executing the tests|

If a higer priority test case is dependent on lower priority test case, the lower priority test case **must** be executed **first**

[Back to content](#x)

<a id="7"></a>
 
### Risk
a factor taht could result in future negative consquences, usually expressed as impact and likelihud.

#### Types:

#### Level of Risks:
Level of Risks = probability of the risk ocurring X impact if it did happen (manage by the manager)

| Product Risk   | Project Risk                                                                                                          |
|:---------------|:----------------------------------------------------------------------------------------------------------------------|
| A risk that affects the QUALITY or RELIABILITY of the software product. | A risk that affects the COST, SCHEDULE, or RESOURCES of the software project.                                         |                                        |
| Examples: FUNCTIONALITY, PERFORMANCE, SECURITY, USABILITY, or COMPATIBILITY issues. | Examples: BUDGET, SCOPE, STAFFING, TECHNOLOGY, or STAKEHOLDER issues.                                                 |
| The impact of product risk is mainly on the CUSTOMERS or END-USERS of the software product. | The impact of project risk is mainly on the DEVELOPERS or MANAGERS of the software project.                           |
| Product risk can be identified and analyzed by using techniques such as REQUIREMENTS REVIEW, RISK-BASED TESTING, or EXPLORATORY TESTING. | Project risk can be identified and analyzed by using techniques such as RISK MANAGEMENT PLAN, RISK REGISTER o MATRIX. |

[Back to content](#x)

<a id="100"></a>

# Questions

||Questions|Answers|N. Page|
|:----|:----|:----|
|What are the two types of risk that have to be considered in testing?| product risk and project risk.|162|
|Compare and contrast these 2 risk types.|Product risk refers to the risk associated with the quality of the software product being developed. It includes risks related to functionality, performance, usability, security, and other quality attributes. Product risks can impact the success of the project and the satisfaction of the end-users.<br>Project risk, on the other hand, refers to the risks associated with the project itself, such as schedule delays, budget overruns, resource constraints, and communication issues. Project risks can impact the overall project timeline, cost, and quality.| |
|How early in the Life Cycle can risk impact the testing approach?|As early as the requirements gathering phase of the software development life cycle. <br><br>During this phase, **risks** related to incomplete or ambiguous requirements can be identified, and appropriate testing strategies can be planned to mitigate those risks.| |
|What does MISRA determine when the level of risk is understood?|Motor Industry Software Reliability Association determines the level of risk associated with software development and provides guidelines for the development of reliable and safe software systems. <br>When the level of risk is understood, MISRA can help in identifying the appropriate coding standards and practices to reduce the risk of software failures and vulnerabilities.| |
|Why is independent testing more effective at finding errors than simply allowing the developer and author to test their ow product?|Independent testing is more effective at finding errors because it brings a fresh perspective and unbiased approach to the testing process. <br>When developers and authors test their own products, they may have inherent biases and assumptions that can lead to overlooking certain defects or issues. <br>Independent testers, on the other hand, can provide a different viewpoint and are more likely to identify potential problems that might have been missed by the developers.|164|
|Name 2 benefits of independence.|Unbiased evaluation: Independent testers can provide an unbiased evaluation of the software product, as they are not involved in its development. This helps in identifying defects and issues that might have been overlooked by the development team.<br>Fresh perspective: Independent testers bring a fresh perspective to the testing process. They can think outside the box and approach testing from different angles, which can lead to the discovery of new defects and improvement opportunities.| |
|Which organisation provides de lowest level of independence, and which provides the highest?|The organization that provides the lowest level of independence is the **development team itself**. Since they are directly involved in the development of the software, their testing activities may be influenced by their biases and assumptions.<br>The organization that provides the highest level of independence is an **external independent testing team*. They are not involved in the development process and can provide an unbiased evaluation of the software product.| |
|Name and explain 5 approaches to the development of the test approach or test strategy.|The five approaches to the development of the test approach or test strategy are:<br><br>**Analytical approach**: This approach involves analyzing the project requirements, risks, and constraints to develop a test strategy that addresses specific testing objectives and priorities.<br><br>**Model-based approach**: In this approach, testing is based on models that represent the system or its components. Models can include diagrams, flowcharts, or other representations that help in defining test cases and test coverage.<br><br>**Methodical approach**: This approach follows a predefined set of rules or methods for test planning, test design, and test execution. It ensures consistency and repeatability in the testing process.<br><br>**Process-compliant approach**: This approach aligns the test strategy with the organization's defined processes and standards. It ensures that testing activities are compliant with industry best practices and regulatory requirements.<br><br>**Consultative approach**: This approach involves consulting with stakeholders, such as developers, business analysts, and end-users, to gather their input and incorporate their perspectives into the test strategy. It promotes collaboration and shared ownership of the testing process.|168|
|Name one of the standards referred to that dictate the test approach.|One of the standards referred to that dictate the test approach is the **ISTQB** (International Software Testing Qualifications Board) standard. <br><br>ISTQB provides a globally recognized **framework for software testing** and defines the principles, processes, and techniques that guide the test approach.| |
|Can discretion be used when defining a test approach testing?|Yes, discretion can be used when defining a test approach.<br><br> The test approach should be tailored to the specific needs and requirements of the project. <br><br>It should take into account factors such as project size, complexity, risks, and available resources. <br><br>Testers can use their professional judgment and discretion to define a test approach that best suits the project's context.| |
|What is the international standard for testing called?|The international standard for testing is called the ISTQB (International Software Testing Qualifications Board) standard. It provides a globally recognized framework for software testing and is widely adopted by organizations and professionals in the field of software testing|174|
|Identify the 15 sections of the test plan.|Introduction: Provides an overview of the test plan.<br><br>Test Items: Lists the items or components to be tested.<br><br>Features to be Tested: Specifies the features or functionalities to be tested.<br><br>Features Not to be Tested: Identifies the features or functionalities that will not be tested.<br><br>Test Approach: Describes the overall approach to be followed during testing.<br><br>Item Pass/Fail Criteria: Defines the criteria for determining whether an item has passed or failed the testing.<br><br>Suspension Criteria and Resumption Requirements: Outlines the conditions under which testing may be suspended and the requirements for resuming testing.<br><br>Test Deliverables: Lists the documents or artifacts to be produced as part of the testing process.<br><br>Testing Tasks: Details the specific tasks to be performed during testing.<br><br>Environmental Needs: Specifies the hardware, software, and other resources required for testing.<br><br>Staffing and Training Needs: Identifies the personnel and their roles in the testing process, as well as any training requirements.<br><br>Responsibilities: Outlines the responsibilities of different stakeholders involved in testing.<br><br>Schedule: Provides a timeline for the testing activities.<br><br>Risks and Contingencies: Identifies potential risks and the contingency plans to address them.<br><br>Approvals: Specifies the individuals or groups who need to approve the test plan.| |
|What activities are contained within test planning?|Test planning involves several activities, including:<br><br>Defining Test Objectives: Clearly stating the goals and objectives of the testing effort.<br><br>Identifying Test Deliverables: Determining the documents or artifacts that need to be produced during testing.<br><br>Estimating Test Effort: Assessing the time, resources, and effort required for testing.<br><br>Identifying Test Risks: Identifying potential risks and their impact on the testing process.<br><br>Defining Test Strategy: Outlining the overall approach and strategy for testing.<br><br>Creating Test Plan: Developing a comprehensive test plan document that covers all aspects of testing.<br><br>Identifying Test Environment: Determining the necessary hardware, software, and other resources for testing.<br><br>Defining Test Schedule: Establishing a timeline for the testing activities.<br><br>Assigning Roles and Responsibilities: Allocating responsibilities to team members and defining their roles.<br><br>Reviewing and Approving Test Plan: Conducting a review of the test plan and obtaining necessary approvals.| |
|Detail 4 typical exit criteria|Exit criteria are the conditions that must be met for a testing phase or activity to be considered complete. Here are four typical examples of exit criteria:<br><br>Test Coverage: A certain level of test coverage, such as code coverage or requirement coverage, has been achieved.<br><br>Defect Closure: All critical and high-priority defects have been fixed and verified.<br><br>Stability: The system or application under test has demonstrated stability, with no major issues or showstoppers.<br><br>Test Completion: All planned test cases have been executed, and the test results have been reviewed and analyzed.| |
|Name 4 common test metrics|Test metrics are used to measure and evaluate various aspects of the testing process. Here are four common test metrics:<br><br><br><br>Defect Density: The number of defects found per unit of code or functionality.<br><br>Test Coverage: The percentage of code or requirements covered by tests.<br><br>Test Execution Progress: The percentage of planned test cases that have been executed.<br><br>Defect Aging: The time taken to resolve or close defects from the time they were reported.|185|
|Name the 10 heading in the ISO 29119-3 Test summary report|The ISO 29119-3 standard provides guidelines for test documentation, including the Test Summary Report. The 10 headings in the Test Summary Report are:<br><br>Introduction<br><br>Test Items<br><br>Features Tested<br><br>Features Not Tested<br><br>Test Environment<br><br>Test Deliverables<br><br>Test Execution<br><br>Test Results<br><br>Summary of Activities<br><br>Conclusion| |
|Identify 3 ways a test manager can control testing if there are more tests than there is time to complete them.|When faced with limited time and an abundance of tests, a test manager can employ the following strategies to control testing:<br><br><br><br>Prioritization: Prioritize tests based on their criticality, risk, or business impact. Focus on executing high-priority tests first.<br><br>Risk-based Testing: Identify and prioritize tests that address the highest risks to the system or application under test.<br><br>Test Optimization: Optimize test execution by using techniques such as test automation, test data management, and test case reuse to reduce the time required for testing.| |
|Identify 3 details that are usually included in a defect report.|A defect report typically includes the following details:<br><br>Defect ID: A unique identifier assigned to the defect for tracking purposes.<br><br>Description: A detailed description of the defect, including steps to reproduce it and any relevant screenshots or logs.<br><br>Severity: The impact or seriousness of the defect on the system or application under test.<br><br>Priority: The importance or urgency of fixing the defect.<br><br>Status: The current status of the defect, such as "Open," "In Progress," or "Closed."<br><br>Assigned To: The person or team responsible for fixing the defect.<br><br>Found By: The individual who discovered and reported the defect.<br><br>Date Found: The date when the defect was identified.<br><br>Attachments: Any additional files or documents related to the defect, such as log files or screenshots.|186|
|What is the name of the standard that includes an outline of a tst defect report?|The standard that includes an outline of a test defect report is called the IEEE 829-1998 Standard for Software Test Documentation. This standard provides guidelines for various test documents, including the test defect report.| |
|What is a test defect?|A test defect, also known as a software defect or bug, is an **abnormality or flaw** in a system or application that causes it to **deviate from its expected behavior**. Test defects can range from minor issues to critical errors that impact the functionality, performance, or usability of the software.<br><br> Defects are typically identified during the testing process and need to be reported, tracked, and fixed to ensure the quality of the software.| |
|Define configuration management.|Configuration management is the process of managing and controlling changes to software, hardware, or system configurations throughout their lifecycle.<br><br> It involves identifying, organizing, and tracking configuration items (CIs), which can include source code, documentation, test cases, and other artifacts.<br><br>Configuration management ensures that changes to CIs are properly controlled, documented, and communicated, enabling traceability, version control, and the ability to revert to previous configurations if needed.|187|
|What can be stored under configuration management?|Under configuration management, various items can be stored, including:<br><br><br><br>Source Code: The code files that make up the software application.<br><br>Documentation: Technical specifications, design documents, user manuals, and other related documents.<br><br>Test Cases: Test scripts, test data, and other artifacts related to testing.<br><br>Builds and Releases: Different versions or builds of the software, including installation packages and release notes.<br><br>Configuration Files: Configuration files that define the settings and parameters for the software.<br><br>Change Requests: Requests for changes to the software or system configurations.<br><br>Bug Reports: Reports of defects or issues identified during testing or production.<br><br>Deployment Scripts: Scripts or instructions for deploying the software in different environments.<br><br>Hardware Configurations: Configuration details of hardware components or systems.<br><br>Network Configurations: Configuration details of network settings and infrastructure.| |
|Why is it important to have effective configuration management?|Effective configuration management is important for several reasons:<br><br><br><br>Version Control: It allows for the proper management and tracking of different versions or releases of software, ensuring that the correct version is used and enabling easy rollback if needed.<br><br>Traceability: It provides the ability to trace changes made to software or system configurations, helping in troubleshooting, auditing, and compliance.<br><br>Collaboration: It facilitates collaboration among team members by providing a central repository for storing and sharing configuration items.<br><br>Reproducibility: It enables the recreation of specific software configurations, making it easier to reproduce and investigate issues.<br><br>Risk Management: It helps in identifying and managing risks associated with changes to configurations, ensuring that changes are properly reviewed, tested, and approved.<br><br>Efficiency: It improves efficiency by automating the management of configurations, reducing manual errors and ensuring consistency.<br><br>Quality Assurance: It contributes to the overall quality of the software by ensuring that changes are properly controlled, tested, and documented.| |

