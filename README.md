# python-lab
Requirements documentation for student task tracer
# python-lab
Requirements documentation for student task tracer
# Student Task Tracker
## Overview
Students need a simple way to track coursework tasks and see what remains.
The proposed system will help a student record tasks and mark them complete.
[Explain the intended benefit in your own words.
ANS: it will definitely ease the work of teachers and students as it will save the time.it help a student record tasks and mark them complete.]

## Scope
- In scope: Add a coursework task with a title.
- In scope: List saved tasks.
- In scope: Mark a task complete.
- Out of scope: Fee payments.
- Out of scope: Automatic grading.

## Stakeholders
- Student: Records tasks and checks progress.
- Instructor: [Explain what the instructor needs to know. ANS: he needs to the student progress ]
- Project maintainer: [will manage tasks]

## Functional requirements
- FR-01: The system shall let a student create a task with a title.
- FR-02: The system shall display the student&#39;s saved tasks.
- FR-03: The system shall let a student mark a task complete.

## Nonfunctional requirements
- NFR-01: With 100 saved tasks, the task list shall appear within
2 seconds in at least 95 of 100 trials on an agreed test device.
- NFR-02: Every task action shall work using only a keyboard,
checked against each documented task workflow.

## Acceptance criteria
- FR-01: Given the title &quot;Read Chapter 1&quot;, saving a new task
makes that title appear in the task list.
- FR-02: Given two saved tasks, opening the list shows both titles.
- FR-03: Marking an incomplete task complete changes its
displayed status to Complete.

## Assumptions and open questions
- Assumption A-01: [State a proposed assumption to validate.ANS: each task will have a unique titleand will belong to a student who created it]
- Question Q-01: [Ask about an unresolved stakeholder need.ANS: student should be able to edit or delete their saved tasks]
- Question Q-02: Which device will be used to test NFR-01?

## Project status and viewing
This is a documentation-only project. No application has been built.
Clone the repository and open README.md in Notepad, or read it on GitHub.

## Author
[Your name and approved course identifier ANS: MUHAMMAD FAHAD AZIZ , TEACHER: MUDASSIRA ARHSAD SHERAAZ]

## Contributing
Create a documentation branch, edit and review README.md,
commit and push the change, then open a pull request for review.
