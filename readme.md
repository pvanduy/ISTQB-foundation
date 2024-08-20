# ISTQB Foundation Study Guide
This repository is dedicated to learning and preparing for the ISTQB (International Software Testing Qualifications Board) Foundation Level exam. It contains study materials, notes, and practice questions to help you gain a solid understanding of software testing principles.

## Table of Contents
- [Introduction](#introduction)
- [What is ISTQB Foundation?](#what-is-istqb-foundation)
- [Study Plan](#study-plan)
- [Resources](#resources)
- [Practice Questions](#practice-questions)
- [Contributing](#contributing)

## Introduction
The ISTQB Foundation Level certification is the first step in the ISTQB Certified Tester scheme. This certification is ideal for anyone involved in software testing, including testers, test analysts, test engineers, and developers.

## What is ISTQB Foundation?
The ISTQB Foundation Level covers the fundamentals of software testing, including:
- [Testing principles](#testing-principles): Basic concepts and principles that guide testing activities.
- [Testing throughout the software life cycle](#testing-throughout-the-software-life-cycle): Understanding how testing fits into different phases of the software development life cycle.
- [Static techniques](#static-techniques): Techniques for testing software without executing code.
- [Test design techniques](#test-design-techniques): Methods for designing test cases based on requirements and specifications.
- [Test management](#test-management): Concepts related to managing and planning testing activities.
- [Tool support for testing](#tool-support-for-testing): An overview of tools that can be used to support testing activities.

## Study Plan
To prepare for the ISTQB Foundation exam, follow this study plan:

1. $\textcolor{lightgreen}{Understand\ the\ syllabus:}$ Review the ISTQB Foundation Level syllabus to get an overview of the topics covered in the exam.
2. $\textcolor{lightgreen}{Study\ each\ topic:}$ Focus on each topic individually, starting with the basics and moving on to more advanced concepts.
3. $\textcolor{lightgreen}{Take\ notes:}$ Create concise notes for each topic to reinforce your understanding.
4. $\textcolor{lightgreen}{Practice\ questions:}$ Test your knowledge with practice questions after studying each topic.
5. $\textcolor{lightgreen}{Review\ and\ revise:}$ Regularly review your notes and revise the topics as needed.

## Resources
Here are some useful resources to help you study for the ISTQB Foundation Level exam:

- [ISTQB Official Website](https://www.istqb.org/)
- [ISTQB Foundation Level Syllabus](https://www.istqb.org/certification-path-root/foundation-level.html)
- [Practice Exams](https://istqb.patshala.com/tests/)

## Practice Questions
This section includes practice questions to help you prepare for the ISTQB Foundation exam. These questions are based on the syllabus and cover various topics.

1. **Question 1**: What is the main objective of software testing?
   - **Answer**: The main objective of software testing is to evaluate the quality of the software product and identify defects.

2. **Question 2**: Explain the difference between verification and validation.
   - **Answer**: Verification ensures the product is built correctly according to specifications, while validation ensures the product meets the user's needs.

(Continue adding more questions...)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

> [!IMPORTANT]
> ### TESTING PRINCIPLES
1. $\textcolor{green}{Testing\ Shows\ the\ Presence\ of\ Defects\ :}$ Testing can show that defects are present, but it cannot prove that there are no defects. Even after thorough testing, some defects may remain.

2. $\textcolor{green}{Exhaustive\ Testing\ is\ Impossible\ :}$  Exhaustive Testing is Impossible: It's impractical to test all possible inputs and conditions. Risk-based testing and prioritization help in focusing on the most critical areas.

3. $\textcolor{green}{Early\ Testing\ :}$ Testing activities should start as early as possible in the software development lifecycle to detect and fix defects early, reducing the cost and time involved.

4. $\textcolor{green}{Defect\ Clustering\ :}$ A small number of modules usually contain most of the defects. Identifying and focusing on these areas can make testing more efficient.

5. $\textcolor{green}{Pesticide\ Paradox\ (Tests\ wear\ out\) :}$ Repeating the same tests over time will no longer find new defects. To avoid this, test cases should be regularly reviewed and revised, and new tests should be designed.

6. $\textcolor{green}{Testing\ is\ Context-Dependent\ :}$ The effectiveness of testing methods varies depending on the context, such as the type of software, its criticality, and the development methodology used.

7. $\textcolor{green}{Absence-of-Errors\ Fallacy\ :}$ Just because a system is free of defects does not mean it is useful or meets the user’s needs. Testing should ensure that the software fulfills its intended purpose.

> [!IMPORTANT]
> ### TESTING THROUGHOUT THE SOFTWARE LIFE CYCLE
1. Testing Activities in Different Development Models:
   - Sequential Development Models (e.g., Waterfall, V-Model):
      - Testing is structured in phases that align with development stages. For example, testing activities such as test planning and design begin in the early stages, even as coding is ongoing, and test execution happens after the development phase.
   - Iterative and Incremental Models (e.g., Agile, DevOps):
      - Testing is continuous and occurs throughout each iteration or increment. Testers collaborate closely with developers and other stakeholders, integrating testing into the ongoing development process. Test automation is often emphasized to support frequent releases.

2. Testing Levels:
   -  Component Testing (Unit Testing):
      -  Focuses on individual components or units of software. Typically, developers perform this to verify that the smallest pieces of code function correctly in isolation.
   -  Integration Testing:
      -  Tests the interactions between integrated components or systems. Different approaches (e.g., top-down, bottom-up) are used depending on the integration strategy.
   -  System Testing:
      -  Involves testing the entire system as a whole to ensure it meets specified requirements. This level of testing covers both functional and non-functional aspects.
   -  Acceptance Testing:
      -  Conducted to determine whether the system meets the acceptance criteria and is ready for deployment. It includes User Acceptance Testing (UAT) and sometimes other forms of acceptance testing, like operational acceptance testing.

3. Test Types:
   -  Functional Testing:
      -  Ensures that the software functions as expected based on the requirements. It includes all levels of testing (unit, integration, system, acceptance) where functionality is evaluated.
   -  Non-Functional Testing:
      -  Evaluates aspects such as performance, usability, security, and reliability. It ensures the software meets non-functional requirements, which are critical for user experience and system performance.
        
![image](https://github.com/user-attachments/assets/7d598a8d-2430-4bc0-8436-f65b7e28d508)


4. Testing in Maintenance:
   -  Regression Testing:
      -  Performed after changes, such as bug fixes or new features, to ensure that existing functionality is not broken. It’s crucial in the maintenance phase to catch unintended consequences of changes.
   -  Maintenance Testing:
      -  Focuses on testing the changes made during maintenance, ensuring that new defects are not introduced and that the software continues to meet user needs.

5. Test Activities:
   -  Test Planning:
      -  Involves defining the scope, approach, resources, and schedule for testing activities. Test planning starts early in the project to ensure that testing objectives align with project goals.
   -  Test Monitoring and Control:
      -  Tracking the progress of test activities against the plan, making adjustments as necessary, and ensuring that testing stays on track.
   -  Test Analysis:
      -  Identifying test conditions based on requirements, architecture, or design documents. This is where testers determine what to test.
   -  Test Design:
      -  Designing test cases, test data, and test environments to cover identified test conditions.
   -  Test Implementation:
      -  Preparing the necessary test scripts, creating the test environment, and arranging the test data.
   -  Test Execution:
      -  Running the test cases, logging the outcomes, and reporting any defects found.
   -  Evaluating Exit Criteria and Reporting:
      -  Reviewing test results to ensure that the exit criteria are met, determining whether additional testing is needed, and making decisions about the release.
   -  Test Closure:
      -  Finalizing and archiving testware, documenting lessons learned, and evaluating the test process for future improvement.

6. Test-Driven Development (TDD) and Continuous Testing:
   -  TDD:
      -  A development approach where test cases are written before the code itself, ensuring that development is guided by the requirements from the start.
   -  Continuous Testing:
   -  Integrated with CI/CD pipelines, continuous testing involves automated testing at every stage of development to provide immediate feedback and support rapid releases.

> [!IMPORTANT]
> ### STATIC TECHNIQUES
1. Static Testing:
   -  Static testing is a software testing technique that involves examining and analyzing software work products without executing the code. It aims to find errors, ambiguities, inconsistencies, and omissions early in the development process, making it a crucial component of quality assurance.

2. Static Testing Basics:
   -  $\textcolor{green}{Techniques\ :}$ Static testing primarily includes reviews (such as inspections, walkthroughs, and technical reviews) and static analysis. These techniques are applied to various documents and code artifacts to identify defects early.
   -  $\textcolor{green}{Process\ :}$ The static testing process typically involves planning, preparation, review meetings, defect recording, and follow-up. The review process is systematic, often guided by checklists to ensure thorough coverage.
3. Work Products Examinable by Static Testing:
   -  $\textcolor{green}{Requirements\ Specifications\ :}$ Static testing can identify ambiguities, contradictions, and omissions in requirements documents.
   -  $\textcolor{green}{Design\ Documents\ :}$ Reviews of design documents help ensure that the design meets the requirements and adheres to best practices.
   -  $\textcolor{green}{Source\ Code\ :}$ Static analysis tools can be used to examine source code for coding standards compliance, security vulnerabilities, and potential bugs.
   -  $\textcolor{green}{Test\ Plans\ and\ Test\ Cases\ :}$  Reviewing test plans and test cases ensures that they are complete, accurate, and aligned with the requirements and design.
   -  $\textcolor{green}{User\ Manuals\ and\ Other\ Documentation\ :}$ Static testing can also be applied to user manuals and other documentation to check for accuracy, clarity, and consistency.
4. Value of Static Testing:
   -  $\textcolor{green}{Early\ Defect\ Detection\ :}$ By identifying defects before code execution, static testing helps prevent defects from propagating into later stages, where they are more costly to fix.
   -  $\textcolor{green}{Cost-Effective\ :}$ Since defects found during static testing are often easier and cheaper to fix than those found during dynamic testing or after deployment, static testing contributes to overall cost reduction in the project.
   -  $\textcolor{green}{Improved\ Quality\ :}$ Regular application of static testing helps improve the quality of work products, leading to a more reliable and maintainable final product.
   -  $\textcolor{green}{Enhanced\ Collaboration\ :}$ Reviews involve multiple stakeholders, fostering communication and collaboration among team members, which improves the overall development process.
5. Differences between $\textcolor{green}{Static\ Testing}$ and $\textcolor{green}{Dynamic\ Testing}$ :
   
|| Static Testing    | Dynamic Testing |
|:---:|:---:|:---:|
| Execution | Involves examining the work products (like code, documents) without executing the software. | Involves executing the software and observing its behavior during runtime to find defects. |
| Focus | Focuses on detecting defects in work products, such as requirements, design, and code, before the product is run. | Focuses on finding defects related to functional and non-functional behavior of the software during execution. |
| Timing | Typically performed early in the development process, often before any code is executed. | Occurs after the code is developed, often during or after the implementation phase. |
| Tools | Relies on tools for static analysis (e.g., code analyzers, linters) and manual review processes. | Utilizes testing frameworks, test automation tools, and environments for executing the software under test. |
| Defect Types | Detects defects such as coding standard violations, logical errors, missing requirements, and documentation issues. | Identifies runtime errors, performance issues, functional failures, and unexpected behaviors during software execution. |


> [!IMPORTANT]
> ### TEST DESIGN TECHNIQUES
1. Test Techniques Overview:
   -  $\textcolor{green}{Test\ design\ techniques\ are\ broadly\ categorized\ into\ three\ main\ types\ :}$
      -  Black-box Techniques: Focus on testing the external behavior of the software without knowledge of its internal structure.
      -  White-box Techniques: Involve testing the internal structures or workings of the software, such as code and logic paths.
      -  Experience-based Techniques: Rely on the tester’s experience, intuition, and knowledge of similar applications or defects.
2. Black-box Test Design Techniques:
These techniques are based on the functional requirements and specifications of the software. They do not require knowledge of the internal code.

   -  $\textcolor{green}{Equivalence\ Partitioning\ (EP)\ :}$
      -  Definition: Divides input data into equivalent partitions that are expected to behave similarly. Test cases are designed to cover one value from each partition, reducing the total number of test cases while maintaining coverage.
      -  Application: Helps in identifying classes of inputs that should be treated the same by the system, ensuring that each partition is tested at least once.

   -  $\textcolor{green}{Boundary\ Value\ Analysis\ (BVA)\:}$
      -  Definition: Focuses on the boundaries between equivalence partitions. Since errors often occur at the boundaries of input ranges, this technique tests values at, just below, and just above these boundaries.
      -  Application: Often used in conjunction with equivalence partitioning, especially in systems that handle ranges of inputs.

   -  $\textcolor{green}{Decision\ Table\ Testing\ :}$
      -  Definition: Uses a table format to represent combinations of inputs and their corresponding outputs or actions. Each row of the table represents a unique combination of conditions (inputs) and the expected outcome (output).
      -  Application: Effective for testing complex business logic and systems with multiple input conditions.

   -  $\textcolor{green}{State\ Transition\ Testing\ :}$
      -  Definition: Involves creating test cases based on the states the system can be in and the transitions between those states. It tests how the system behaves in each state and how it transitions from one state to another.
      -  Application: Useful for systems where the behavior depends on the sequence of events, such as workflows, user interfaces, and state-driven systems.

3. White-box Test Design Techniques:
These techniques are based on the internal workings of the system, requiring knowledge of the code and logic.

   -  $\textcolor{green}{Statement\ Testing\ and\ Coverage\ :}$
      -  Definition: Involves designing test cases to execute individual statements in the code at least once. The goal is to achieve 100% statement coverage.
      -  Application: Ensures that every line of code is tested, though it may not reveal all types of defects, especially those related to the control flow.

   -  $\textcolor{green}{Decision\ Testing\ and\ Coverage\ :}$
      -  Definition: Focuses on testing decision points in the code, such as if-else conditions. Test cases are designed to cover all possible outcomes of each decision point.
      -  Application: Provides more thorough coverage than statement testing by ensuring that all branches of the decision points are tested.

   -  $\textcolor{green}{Other\ White-box\ Techniques\ :}$
      -  Condition Coverage: Ensures that each condition in a decision statement is tested with both true and false outcomes.
      -  Multiple Condition Coverage: Tests all possible combinations of conditions in decision statements.

4. Experience-based Test Design Techniques:
These techniques rely on the tester’s experience, knowledge of similar applications, and understanding of where defects are likely to occur.

   -  $\textcolor{green}{Error\ Guessing\ :}$
      -  Definition: Involves designing test cases based on the tester’s intuition, experience, and knowledge of typical errors. The tester anticipates where defects might occur and creates test cases to target those areas.
      -  Application: Useful for identifying defects that may not be covered by systematic test design techniques.
   -  $\textcolor{green}{Exploratory\ Testing\ :}$
      -  Definition: A hands-on approach where testers actively explore the application without predefined test cases, simultaneously learning about the system and designing new tests.
      -  Application: Effective in situations where requirements are incomplete, changing, or when the tester needs to investigate a specific area of the application more deeply.

5. Collaboration-based Test Approaches:
Collaboration-based test approaches involve close cooperation between various stakeholders—such as developers, testers, product owners, and business analysts—to ensure that the product meets the desired quality and functionality. These approaches emphasize shared understanding, clear communication, and joint responsibility for defining and verifying the product’s requirements and behavior.

   -  $\textcolor{green}{Collaborative\ User\ Story\ Writing\ :}$
      -  Definition: Collaborative user story writing is a practice where stakeholders work together to create user stories that clearly define the features and functionality of the software from the end-user’s perspective. User stories are simple, concise descriptions of a feature or function that the user needs.
      -  Process:
         -  Involvement: Typically involves the product owner, developers, testers, and sometimes even end-users, all working together to ensure that the user stories accurately reflect the user’s needs and the technical feasibility.
         -  Workshops: Collaborative workshops, often referred to as "story writing workshops," are commonly used to brainstorm, discuss, and refine user stories. These workshops foster a shared understanding of what is to be built and help identify potential issues early in the development process.
         -  Outcomes: The goal is to produce clear, concise, and testable user stories that are understood by everyone involved. This clarity helps in aligning the team’s efforts and ensures that everyone is working towards the same goals.
   -  $\textcolor{green}{Acceptance\ Criteria\ :}$
      -  Definition: Acceptance criteria are the conditions that a software product must satisfy to be accepted by the user, customer, or other stakeholders. They are typically defined for each user story and describe what needs to be done for the feature to be considered complete and functioning as expected.
      -  Role in Development:
         -  Clarity: Acceptance criteria provide a clear definition of what is expected, reducing ambiguity and helping ensure that the development meets the user’s needs.
         -  Basis for Testing: They serve as the basis for acceptance tests, which are designed to verify that the software meets the specified criteria.
         -  Communication: Acceptance criteria are written in collaboration with all stakeholders, ensuring that everyone has the same understanding of the requirements and expectations.
         -  Format: Acceptance criteria can be written in different formats, such as "Given-When-Then" statements, which outline the preconditions, the action taken, and the expected outcome.
   -  $\textcolor{green}{Acceptance\ Test-driven Development\ (ATDD)\ :}$
      -  Definition: Acceptance Test-driven Development (ATDD) is a collaborative approach where acceptance tests are defined before the actual development begins. These tests are written based on the acceptance criteria and are used to guide the development process.
      -  Process:
         -  Test First: ATDD follows a "test-first" approach, where the team collaborates to write acceptance tests before any coding is done. These tests are designed to verify that the software meets the acceptance criteria.
         -  Collaboration: Involves close collaboration between developers, testers, and product owners to ensure that the acceptance tests are comprehensive and correctly reflect the user’s needs.
         -  Continuous Feedback: As development progresses, the acceptance tests are run continuously to provide feedback on whether the software meets the acceptance criteria. This helps in identifying issues early and ensuring that the product is on track to meet the user’s expectations.
      -  Benefits:
         -  Alignment: ATDD aligns development with business requirements, ensuring that the software being built is what the user actually needs.
         -  Quality Assurance: By defining tests upfront, ATDD helps prevent defects and ensures that the product meets the required quality standards.
         -  Transparency: Provides transparency and a shared understanding of what is being built, which helps in making informed decisions throughout the development process.

> [!IMPORTANT]
> ### TEST MANAGEMENT
1. $\textcolor{green}{Test\ Organization\ :}$ Discusses roles and responsibilities in a test team, including the Test Manager and Tester roles. It covers how these roles contribute to planning, executing, and evaluating test activities.

2. $\textcolor{green}{Test\ Planning\ and\ Estimation\ :}$ Involves creating a test plan that outlines the scope, approach, resources, and schedule for testing activities. Estimation techniques, such as expert-based estimation and metrics-based estimation, are used to predict the effort and resources required.

3. $\textcolor{green}{Test\ Monitoring\ and\ Control\ :}$ Focuses on tracking the progress of test activities against the test plan. Key metrics and reporting methods are used to monitor progress, while control actions are taken if the project deviates from the plan.

4. $\textcolor{green}{Configuration\ Management\ :}$ Ensures that test artifacts, such as test cases and test data, are properly controlled and versioned. Configuration management practices help maintain the integrity of test environments and deliverables.

6. $\textcolor{green}{Risk\ and\ Testing\ :}$ Involves identifying and assessing risks that may impact the quality of the product. Test management uses risk-based testing to prioritize testing activities based on the likelihood and impact of potential defects.

7. $\textcolor{green}{Incident\ Management\ :}$ Covers the process of recording, analyzing, and tracking defects or issues discovered during testing. Incident management ensures that all issues are properly documented and addressed.

> [!IMPORTANT]
> ### TOOL SUPPORT FOR TESTING
-   $\textcolor{green}{Test\ tools\ are\ software\ applications\ used\ to\ support\ various\ testing\ activitie.\ They\ can\ be\ categorized\ into\ several\ types\ :}$
   1. Test Management Tools: Manage test cases, test execution, and defect tracking. Examples include:
      -  JIRA: Used for issue tracking and test management.
      -  TestRail: Provides test case management and reporting
   2. Static Analysis Tools: Analyze code without executing it. Examples include:
      -  SonarQube: Provides code quality and security analysis.
      -  Checkmarx: Identifies vulnerabilities in source code.
   3. Test design and implementation tools – facilitate generation of test cases, test data and test procedures
   4. Test Execution Tools: Automate the execution of test cases. Examples include:
      -  Selenium: Automates web browser interaction.
      -  Appium: Automates mobile application testing.
   5. Non-functional testing tools – allow the tester to perform non-functional testing that is difficult or impossible to perform manually
   6. DevOps tools – support the DevOps delivery pipeline, workflow tracking, automated build process(es), CI/CD
   7. Collaboration tools – facilitate communication
   8. Tools supporting scalability and deployment standardization (e.g., virtual machines, containerization tools)
   9. Any other tool that assists in testing (e.g., a spreadsheet is a test tool in the context of testing)

-  $\textcolor{green}{Benefits\ of\ Test\ Automation\ :}$
   -  Time saved by reducing repetitive manual work (e.g., execute regression tests, re-enter the same test data, compare expected results vs actual results, and check against coding standards)
   -  Prevention of simple human errors through greater consistency and repeatability (e.g., tests are consistently derived from requirements, test data is created in a systematic manner, and tests are executed by a tool in the same order with the same frequency)
   -  More objective assessment (e.g., coverage) and providing measures that are too complicated for humans to derive
   -  Easier access to information about testing to support test management and test reporting (e.g., statistics, graphs, and aggregated data about test progress, defect rates, and test execution duration)
   -  Reduced test execution times to provide earlier defect detection, faster feedback and faster time to market
   -  More time for testers to design new, deeper and more effective tests

-  $\textcolor{green}{Risks\ of\ Test\ Automation\ :}$
   -  Unrealistic expectations about the benefits of a tool (including functionality and ease of use).
   -  Inaccurate estimations of time, costs, effort required to introduce a tool, maintain test scripts and change the existing manual test process.
   -  Using a test tool when manual testing is more appropriate.
   -  Relying on a tool too much, e.g., ignoring the need of human critical thinking.
   -  The dependency on the tool vendor which may go out of business, retire the tool, sell the tool to a different vendor or provide poor support (e.g., responses to queries, upgrades, and defect fixes).
   -  Using an open-source software which may be abandoned, meaning that no further updates are available, or its internal components may require quite frequent updates as a further development.
   -  The automation tool is not compatible with the development platform.
   -  Choosing an unsuitable tool that did not comply with the regulatory requirements and/or safety standards.

## Contributing
Contributions are welcome! If you have additional resources, practice questions, or suggestions, feel free to submit a pull request.
