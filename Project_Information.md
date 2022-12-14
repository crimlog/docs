# CrimLog Project Board

## How to Use

The CrimLog Project Board provides insight into the implementation plan for CrimLog. Additionally, it provides tracebility between GitHub Project Cards and CrimLog User Stories and Architectural Plan ([documents found below](#supporting-documents)).

### Repositories

CrimLog utilizes the following repositories:
- [api](https://github.com/crimlog/api) 
- [hardware](https://github.com/crimlog/hardware) 

### Status Sections
The KanBan Board has numerous sections, which represent the current status of the item, which is described below.

- Backlog - The Backlog status features all issues that are planned for completion, but not in the current sprint.

- Sprint Backlog - The Sprint Backlog status features all issues that are planned for completion in the current spring.

- In Progress - The In Progress status includes all issues that are currently in development.

- Ready for QA - The Ready for QA status includes all issues with an open PR that is ready for review.

- In QA - The In QA status includes all issues with an open PR that are being actively reviewed by testers, including Unit Tests when applicable.

- Done - The Done status includes all issues where all necessary code changes and PRs related to the issue are merged.

- Released - The Released status includes all issues that have been published in a version release.

### Items

Items on the KanBan board are added from Issues within the repositories. Items will contain a description, which are comments left by developers, which include information required for the development and testing of the item, usually in a chekcbox format, which will represent tasks. All items will have different fields, which are described below. 

- Assignees - The people who have been assigned to the item.

- Status - The current status of the item, described more [above](#status-sections).

- Linked Pull Requests - The Pull Requests linked to the story, which allows for easy access to commit information and history.

- Estimate Amount of Hours - The estimated amount of hours a developer would need to develop and test the item.

- Actual Amount of Hours - The actual amount of hours a developer takes to develop and test the item.

- Percent Complete - The percentage of an item that has been completed.

- User Story - The user stories where the item or issue originates from. 

- Architectural Plan - The section of the design report/architectural plan where the item was initially designed. This design report/architectural plan can be found in the [supporting documents below](#supporting-documents).

- Code Module - The code module provides a link to the list of files that have been modified to complete the item.

- Test Case - The test case provides a link to the unit test that has been run to complete the item.

### KanBan Board

The KanBan Board sections show the status of items within the project that can be moved on the KanBan board. Items are added from GitHub issues from the repositories. 

### List Board

The List Board view shows a list of items by title. Each item in the chart also includes status information about each item.


## Supporting Documents

[Design Report/Architectural Plan](https://1drv.ms/b/s!AiCF1hcKxI7hhyieEy8h1eWCUFS_?e=PBor82)

