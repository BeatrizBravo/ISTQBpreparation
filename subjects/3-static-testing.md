**Content:**
 <a id="x"></a>
 - [Introduction](#1)
 - [Type of review](#2)
 - [Typical defects in static testing](#3)
 - [Review Technique](#4)
 - [Questions](#5)
 - [Formal review sequence](#6)
 - [Static testing and Static Analysis ](#7)

 <a id="1"></a>
 
# Intro

**Static** test is carried out **without** executing any code.
<br>


>By:
>> -  reading and 
>>- commenting on 
> 
>Any work product such:
>>* a requirement specification
>>* a piece of code 
>>* a test plan
>>* a test case


|Static|Dynamic|
|:----|:----|
|- finds causes of failure (Defect)|- finds the failures themselves (failure)|
|- finds them early|- finds them late|
|- defect cheap to fix|- defect expensive to fix|
|-----Te techniques  are complementary----- |
| | |



<br>

|static analysis and dynamic testing have the same objective =>|identifying defects|
|:----|:----|

<br>

[Back to content](#x)
 <a id="2"></a>

# Type of review

|Type of review|Description|Advantages|Disadvantages|
|:----|:----|:----|:----|
|Informal Review|Review conducted without any formal structure or methods.|Quick and easy to conduct, suitable for small documents.|May miss important issues, may lack consistency and thoroughness.|
|Walkthrough|A formal, slow-paced review that focuses on educating reviewers and discovering defects.|Helps identify defects early, can improve understanding of the document, fosters teamwork.|Can be time-consuming, may be too informal for some contexts.|
|Technical Review|A formal, structured review that uses specific techniques and criteria to identify defects.|Unearths comprehensive list of defects, improves quality of the document.|Can be time-consuming and costly to plan and execute.|
|Inspection|A highly formal, rigorous review process that analyzes the document with the goal of finding as many defects as possible.|Finds many defects, helps ensure high quality.|Can be time-consuming, requires extensive preparation and training.|
|Peer Review|A review conducted by peers who share similar qualifications and experience, using a set of guidelines.|Can identify defects early, fosters collaboration and knowledge sharing, helps ensure high quality.|Limited to the expertise of the participants, may overlook some issues.|
<br>

[Back to content](#x)
 <a id="3></a>

# Typical defects in static testing
|Typical defects| |
|:----|:----|
|Requirement defects |inconsistencies<br> ambiguities<br> contradictions<br> omissions<br> inaccuracies<br> redundancies|
|Design defects|inefficient algorithms or database structures<br> high coupling (the lack of interdependent between modules) <br> low cohesion (associated with undesirable traits such as being difficult to maintain, test, reuse or even understand.|
|Coding defects | variables with undefined values<br> variables that are declared but never used<br> unreachable code <br>duplicate code|
|Deviations from standards |lack of adherence to coding standards|
|Incorrect interface specifications |different units of measurement used by the **calling** system than by the **called** system|
|Security vulnerabilities |susceptibility to buffer overflows|
|Gaps or inaccuracies in test basis traceability or coverage |missing tests for an criterion|


<br>

[Back to content](#x)
 <a id="4></a>

# Review Technique

|Review Technique|Description|
|:----|:----|
|Ad hoc|Review conducted without any specific method or approach, relying on the reviewer's experience and intuition.|
|Checklist based|Review based on a predefined list of items that must be checked during the review process.|
|Scenarios and dry runs|Review based on simulations and trial runs of the document or product being reviewed.|
|Role based|Review in which participants play specific well-defined roles (e.g., author, reviewer, moderator) to ensure all aspects of the review are covered.|
|Perspective based|Review in which the focus is on a specific aspect of the document or product being reviewed (stakeholder's view point).|



<br>

[Back to content](#x)
 <a id="6"></a>

# Formal review sequence


```
Formal review sequence:

├── Planning
    ├── initiate review
        ├── Individual review
            ├── Issue  communication
                ├── Analysis
```

br>

[Back to content](#x)
 <a id="7"></a>

# Static testing and Static Analysis 
|Criteria|Static Testing|Static Analysis|
|:----|:----|:----|
|Definition|A technique for evaluating software without executing code.<br>2 parts: <br>&ensp;&ensp;-Manual testing (review activities)<br>&ensp;&ensp;-Automation testing (static analysis tool) <br>**Reviews** are applied to:<br>- code, <br>-requirements,<br>- design documents, or <br>- test plans.|A technique for evaluating software through:<br>- examining code and <br> - identifying code structure and <br>- data flow issues. <br>It is code-focused rather than document-focused.<br> chapter 4|
|Main Purpose|To identify errors in early stages and improve software quality before testing.|To locate hidden bugs, security vulnerabilities and code smells, and prevent runtime issues.|
|Application|Used during the verification phase of the software development life cycle.|Can be used during development, testing, or maintenance stages.|
|Method|Includes reviews, walkthroughs, and inspections.|Includes code analysis tools, such as code scanners, which automatically examine code to locate security vulnerabilities or other defects.|
|Advantages|Helps identify and fix errors early, helps maintainability and readability of code, cost-effective.|Helps identify hidden bugs and errors that can cause runtime issues, helps identify security vulnerabilities and code smells.|
|Disadvantages|Can be time-consuming and require a lot of effort in the preparation phase, may require special training.|May produce a large volume of false positives, may require special training to use, may not account for runtime behavior.|


<br>

[Back to content](#x)
 <a id="6"></a>

<br>

# Questions
|Question|Answer|
|:----|:----|
|Identify 3 benefits of review|find defects early, improve collaboration, increase product quality|
|What happened during the planning phase of a review?|determine objectives, select reviewers, create review checklist|
|Who manages the review process?|review moderator, review leader, or review chair|
|Compare the differences between a walkthrough and an inspection|walkthrough: informal, no specific roles, goal is understanding; inspection: formal, participants play specific roles, goal is finding defects|
|Name 3 characteristics of a walkthrough|no specific roles, freeform discussion, focused on understanding|
