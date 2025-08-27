# Taskserver II (CCSync)

## Google Summer of Code'25
_Name : Abhishek_ <br/>
_Slack : [Link to Slack ID](https://rhccgsoc15.slack.com/team/U0646QP9HDK)_ <br/>
_Zulip : [Link to Zulip ID](https://ccextractor.zulipchat.com/#user/857337)_ <br/>
_GitHub Username : [its-me-abhishek](https://github.com/its-me-abhishek)_ <br/>
_Mentors: [Nishant Singhal](https://github.com/NishantSinghal19), [Mabud Alam](https://github.com/Pavel401)_ <br/>

## Table of contents
- [My project work](#my-project-work)
- [Work Track](#work-track)
- [Weekly Reports](#weekly-reports)
- [Personal Note](#personal-note) 

### My project work

### Work Track

1. Migrating Firestore to Browser based storage

_Objective_: To migrate the core functionality of Firestore on frontend to work with IndexedDB instead. Replace all the Firestore based functions like sync, delete, add, fetch, update, etc. with similar IndexedDB Functionality

| Name of the Task | Description | Link to work |
|------------------|-------------|--------------|
| Firestore migration | <ul><li>Migrate all Firestore functionality to similar IndexedDB functionality</li> <li>Update all unit tests to make them compatible with the latest database</li><li>Update all functions and components</li></ul> | [Link to work](https://github.com/CCExtractor/ccsync/pull/101) |

2. Workflow for Testing Frontend
   
_Objective_: To ensure frontend unit tests are verified automatically through a GitHub Actions workflow.

| Name of the Task | Description | Link to work |
|------------------|-------------|--------------|
| Workflow for testing Frontend | <ul><li>Add a testing workflow for frontend to check unit tests</li> <li>Change the flag in URL.ts to set for testing.</li></ul> | [Link to work](https://github.com/CCExtractor/ccsync/pull/103) |

3. Docker Images Workflows

_Objective_: To enable automated Docker image builds and pushing through CI/CD pipelines.

| Name of the Task | Description | Link to work |
|------------------|-------------|--------------|
| Docker images workflows | <ul><li>Add workflows to build and push Docker images</li></ul> | [Link to work](https://github.com/CCExtractor/ccsync/pull/102) |

4. Finalised Docker Production Workflow

_Objective_: To set up a complete production-ready Docker environment and corresponding documentation.

| Name of the Task | Description | Link to work |
|------------------|-------------|--------------|
| Finalised Docker Production Workflow | <ul><li>Update .env files and production build for Docker images</li> <li>Update all documentation in ccsync-docs and readme</li></ul> | [Link to work](https://github.com/CCExtractor/ccsync/pull/104) |

5. Workflow for Testing Backend
   
_Objective_: To ensure backend unit tests are verified automatically through a GitHub Actions workflow.

| Name of the Task | Description | Link to work |
|------------------|-------------|--------------|
| Workflow for testing Frontend | <ul><li>Add a testing workflow for backend to check unit tests</li></ul> | [Link to work](https://github.com/CCExtractor/ccsync/pull/105) |

6. Update Documentation

_Objective_: To update documentation according to new setup for production, development, and using with the Taskwarrior Flutter app

| Name of the Task | Description | Link to work |
|------------------|-------------|--------------|
| Updated Documentation | <ul><li>Added information on how to setup the server for production</li></ul> <ul><li>Added information about use of the Oauth keys</li></ul> | [Link to work](https://its-me-abhishek.github.io/ccsync-docs/) |

7. Search functionality

_Objective_: To add a search bar that helps in searching across tasks easily.

<img width="1677" height="357" alt="image" src="https://github.com/user-attachments/assets/47d3ee8a-1ab3-4508-8e22-9a7a9380b4ff" />

| Name of the Task | Description | Link to work |
|------------------|-------------|--------------|
| Search functionality | <ul><li>Added a search bar using debounce so as to reduce load on browser, and query through tasks based on description, tags or projects</li></ul> | [Link to work](https://github.com/CCExtractor/ccsync/pull/106) |

8. Ability to download secrets

_Objective_: To add an option to download the secrets offline for better sharing/security

<img width="1653" height="576" alt="image" src="https://github.com/user-attachments/assets/ea875377-b72e-4b45-959a-b7caac01c09f" />

| Name of the Task | Description | Link to work |
|------------------|-------------|--------------|
| Export secrets | <ul><li>Added an option to download the encryption secret and client id in a text file format using React Blob feature</li></ul> | [Link to work](https://github.com/CCExtractor/ccsync/pull/106) |
 
9. Final documentation

_Objective_: Update the documentation for clarity and better description of setup/project in general

| Name of the Task | Description | Link to work |
|------------------|-------------|--------------|
| Update Documentation for Clarity | <ul><li>Improved grammatical errors, and added more verbose descriptions</li></ul> | [Link to work](https://github.com/its-me-abhishek/ccsync-docs/pull/9) | 

### Weekly Reports
These are the weekly reports (blogs) that I had submitted to and worked on  CCSync during GSoC period:
1. [Community Bonding Period](https://abhishek31.medium.com/community-bonding-period-for-gsoc25-at-ccextractor-17ae178dbccd)
2. [Week 1](https://abhishek31.medium.com/gsoc25-week-1-at-ccextractor-463a8674f513)
3. [Week 2 & 3](https://abhishek31.medium.com/gsoc25-week-2-3-at-ccextractor-b292ab748a66)
4. [Week 4 & 5](https://abhishek31.medium.com/gsoc25-week-4-5-at-ccextractor-ae9f2f2ec3f7)
5. [Week 6](https://abhishek31.medium.com/gsoc25-week-6-at-ccextractor-304443679fe2)
6. [Week 7, 8 & 9](https://abhishek31.medium.com/gsoc25-week-7-8-9-at-ccextractor-76617d15ea86)
7. [Week 10, 11 & 12](https://abhishek31.medium.com/gsoc25-week-10-11-12-at-ccextractor-0349c7a2878a)

### Personal Note
Working again with CCExtractor Organisation on this project has been a very great experience. The progress this year was in a direction to make the project easy to setup and use, and we have been able to achieve this as well. For the future, I plan to continue working on the project, and guide any new contributors, as well as maintain the project. Apart from this would be working on more features in a broader scope in order to make the project more useful to the community.
