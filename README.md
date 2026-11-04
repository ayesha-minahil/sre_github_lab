# Student Task Tracker

## Overview
The Student Task Tracker is a simple system designed to help students manage and track their coursework tasks. Students can add tasks, view their recorded tasks, and mark tasks as complete. The system aims to improve organization, time management, and academic progress tracking.

## Scope
- In scope: Add a coursework task.
- In scope: List recorded tasks.
- In scope: Mark a task complete.
- Out of scope: Fee payments.
- Out of scope: Automatic grading.

## Stakeholders
- Student: Records tasks and checks progress.
- Instructor: Ensures the system supports students in managing coursework effectively.
- Project maintainer: Maintains the system, fixes bugs, and ensures its proper functioning.

## Functional Requirements
- FR-01: The system shall let a student create a task with a title.
- FR-02: The system shall display the student's recorded tasks.
- FR-03: The system shall let a student mark a task as complete.

## Non Functional Requirements
- NFR-01: For 100 stored tasks, the task list shall appear within
2 seconds in at least 95 of 100 trials on the agreed test device.
- NFR-02: All task actions shall be operable using a keyboard
alone, verified against each documented task workflow.

## Acceptance Criteria
- Given that a student enters "Read Chapter 1" as a task title, when the student clicks the Save button, then the system shall display "Read Chapter 1" in the task list immediately after saving.
causes that title to appear in the task list.
- FR-02: With two saved tasks, opening the list shows both titles.
- FR-03: Marking an incomplete task complete changes its displayed
status to Complete.

## Assumptions and Open Issues
- Assumption A-01: Each student will manage their own coursework tasks using the system.
- Question Q-01: Should students be allowed to edit or delete previously recorded tasks?
- Question Q-02: Which device and environment will test NFR-01?

## Project Status and Viewing
Documentation only. Application implementation has not started.
Clone this repository and open README.md in a Markdown viewer,
or read the rendered file on GitHub.

## Author
Ayesha Minahil SRE

## Contributing
Create a documentation branch, edit and review the README, commit the change, push the branch, and open a pull request.