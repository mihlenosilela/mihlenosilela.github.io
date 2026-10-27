---
layout: default
title: "User Stories and Tasks"
---

{% include wil-style.html %}
{% include wil-nav.html %}

# 2. User Stories and Tasks

A user story is a short description of a feature written from the user’s point of view. Each story is broken into tasks that team members own.

## Evidence

### Stories from our task board

| # | User story | Sprint / card | Status |
|---|---|---|---|
| 1 | As a supervisor, I want to see all the sprints and the tasks for each day for each member, so that I can be sure everyone is working on something. | Sprint 2: Product backlog | Completed |
| 2 | As a supervisor, I want everyone to submit the presentation deck, so that I can be sure everyone has access to all the group work. | Sprint 2: Presentation deck | Completed |
| 3 | As a group, we need to appoint a member to work on the frontend, so that no gap hinders us from finishing on time. | Sprint 1: Member appointment | Completed |
| 4 | As a developer, I want to debug and deploy the integrated system so that it is production ready. As an admin, I want to authenticate and access a secure dashboard so that I can manage system operations. As an admin, I want to manage product listings and image uploads so that shop inventory is properly maintained. | Error handling, Admin panel, Dashboard functionality | Error handling completed |
| 5 | As a developer, I want the GitHub repository and folder structure so that the team can push the source code and conduct peer programming. | Sprint 1, Day 1: Project planning and setup | Completed |
| 6 | As a customer, I want to see the price, size and picture of the product, so that I can decide if I really want it. | Sprint 1, Day 2: Core product catalog | Completed |
| 7 | As a user, I want to access expanded options, a live preview, dynamic real-time pricing, validated inputs and improved UI styling, so that I can customise what I order. | Advanced customisation (September) | Completed |
| 8 | As a developer, I want to debug Spring Security issues so that the backend can be deployed reliably. | Render redeployment (October) | In the October logbook |
| 9 | As a developer, I want to ensure backend stability and security checks so that the system is secure. | Backend stability | In the October logbook |
| 10 | As a developer, I want to prepare the backend for frontend integration so that the whole system works together. | Authentication and protected routes | In the October logbook |
| 11 | As a QA tester, I want end-to-end tests so that login, catalogue browsing, checkout and reporting work across devices and environments. | Sprint 12, Day 1: End-to-end testing | In the 19 October logbook |
| 12 | As an admin, I want analytics widgets tested and deployed so that I can securely view store insights. | Admin testing and integration checks | In the 19 October logbook |
| 13 | As an admin, I want the frontend tested and deployed so that I can safely view the web application. | Deploy frontend to Vercel, backend to Render | In the 19 October logbook |
| 14 | As a customer, I want product items to have accurate stock levels so that I do not try to order items that are out of stock. | Sprint 5, Day 1: Stock validation | In the 21 September logbook |
| 15 | As a customer, I want to receive order communication through my email so that I always have proof of purchase. | Sprint 5, Day 2: User email feedback | Completed |
| 16 | As a customer, I want a smooth payment process so that I can successfully pay for my order. | Sprint 5, Day 3: Payment integration | In the 21 September logbook |
| 17 | As a developer, I want the backend code to work with the frontend, and to debug and integrate the backend classes, so that the system works without faults. | Sprint 5, Day 4 and Sprint 6, Days 1 to 4 | In the 21 and 28 September logbooks |
| 18 | As a developer, I want all data from the frontend captured in the database, and the backend deployed, so that the frontend can interact with it. | Sprint 6, Days 2 and 3 | In the 28 September logbook |

### One story broken into tasks (Sprint 1, Day 2: Core product catalog)

| Task | Owner |
|---|---|
| Product data model | Athini Ngquke |
| Product sample data | Olwethu Mtwazi |
| Fetching and filtering API endpoints | Mihle Nosilela |
| Price range and size filtering | Sinobawo Nkomo |
| Unit tests for the product API | Siphokuhle Nyana |

![Trello card Sprint 1 Day 2 Core product catalog with its user story and five subtasks all completed](/images/trello-card-day2.png)
*Figure 1: Trello card “Sprint 1: Day 2 - Core product catalog”. The user story is in the description and the five tasks each have a named owner and are 100% complete.*

![Trello card Sprint 1 Day 1 Project planning and setup with user story, members and activity](/images/trello-card-day1.png)
*Figure 2: Trello card “Sprint 1: Day 1 - Project planning & Setup”, showing the user story, all members, the “Good” label and the activity log.*

## Reflection

<div class="reflection" markdown="1">

**What.** Our stories came from the people who use or manage the system: the customer, the admin, the developer, the QA tester and our supervisor. Each story was split into tasks with owners. In the Core product catalog story, five tasks covered the data model, sample data, API endpoints, filtering and unit tests. As Frontend Designer I worked on turning these stories into screens a customer and an admin can use.

**So what.** Writing “As a customer, I want to see the price, size and picture” made me design the product page around what a customer needs in order to decide, not around what looked good. Splitting the story into five tasks let us work in parallel, but it also showed me that a story is only finished when the pieces fit together, which is why unit testing was a task of its own. Some of our early stories, such as the repository setup, were technical and did not describe value to a user, so I now see that every story should still state who benefits and why.

The stories also changed character over the project. Early ones were about planning and the catalogue, and later ones from the October logbooks were about security, deployment and testing, such as the story to debug Spring Security so the backend can be deployed reliably. That shows me that stories keep evolving as the real risks of the project appear.

**Now what.** I would add clear acceptance criteria to each story so everyone agrees what “done” means, and I would show the interface to a real user earlier.

**Connect.** These stories became the items in the [Product Backlog](/product-backlog).

</div>

---
[WIL Portfolio Home](/wil-agile-portfolio) | [Team Charter](/agile-team-charter) | [User Stories](/user-stories-and-tasks) | [Product Backlog](/product-backlog) | [Sprint Backlog](/sprint-backlog) | [Agile Logbook](/agile-logbook) | [Back to my portfolio](/)
