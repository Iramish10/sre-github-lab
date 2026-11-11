# Thesis Management System

## Overview
Students need a simple way to manage their thesis work and keep track of their research activities.

The proposed system will help students record thesis-related tasks, view their saved tasks, and mark tasks as completed.

**Intended Benefit:**

The main benefit of this system is to help students organize their thesis work, manage their progress, and complete their research activities on time. It will also help students keep track of pending and completed tasks.

## Scope

- In scope: Add a thesis task with a title.
- In scope: List saved thesis tasks.
- In scope: Mark a thesis task as complete.
- Out of scope: Thesis fee payments.
- Out of scope: Automatic thesis grading.

## Stakeholders

- **Student:** Records thesis tasks, checks progress, and manages research activities.
- **Instructor/Supervisor:** Monitors students' thesis progress and checks whether assigned tasks are completed.
- **Project Maintainer:** Manages system updates, fixes errors, and ensures that the system works properly.

## Functional Requirements

- **FR-01:** The system shall let a student create a thesis task with a title.
- **FR-02:** The system shall display the student's saved thesis tasks.
- **FR-03:** The system shall let a student mark a thesis task as complete.

## Nonfunctional Requirements

- **NFR-01:** With 100 saved thesis tasks, the task list shall appear within 2 seconds in at least 95 of 100 trials on an agreed test device.
- **NFR-02:** Every task action shall work using only a keyboard, checked against each documented task workflow.

## Acceptance Criteria

- **FR-01:** Given the title "Literature Review", saving a new thesis task makes that title appear in the task list.
- **FR-02:** Given two saved thesis tasks, opening the list shows both task titles.
- **FR-03:** Marking an incomplete thesis task complete changes its displayed status to Complete.

## Assumptions and Open Questions

- **Assumption A-01:** It is assumed that each student will use the system to manage their own thesis-related tasks.
- **Question Q-01:** Should the supervisor also be able to view students' thesis progress?
- **Question Q-02:** Which device will be used to test NFR-01?

## Project Status and Viewing

This is a documentation-only project. No application has been built.

Clone the repository and open README.md in Notepad, or read it on GitHub.

## Author

Name: [Iramish Rafique]

Course Identifier: [MAM MUDASSIRA]

## Contributing

Create a documentation branch, edit and review README.md, commit and push the change, then open a pull request for review.
