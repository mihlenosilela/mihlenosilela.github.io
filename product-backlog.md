---
layout: default
title: "Product Backlog"
---

{% include wil-style.html %}
{% include wil-nav.html %}

# 3. Product Backlog

The product backlog is the prioritised list of all the work the product needs. I used MoSCoW priorities: **Must**, **Should**, **Could**.

## Evidence

<!-- CHECK: compare this table with your 19 Product Backlog cards on Trello and adjust names or priorities. -->

| Priority | Backlog item | Linked story | Why this priority |
|---|---|---|---|
| Must | Project planning and setup (repository, folders) | Story 5 | The team could not share code without it |
| Must | Core product catalog | Story 6 | Nothing can be sold without products |
| Must | Authentication | Story 4 | Admin features must be secure |
| Must | Order creation | Customer ordering | Needed for the shop to work |
| Must | Admin panel, dashboard, product listings and image uploads | Story 4 | Needed to manage inventory |
| Must | Error handling and debugging | Story 4 | Needed before the system is production ready |
| Must | Catalogue UI | Story 6 | The catalogue is what customers see |
| Should | Expansion model updates | n/a | Prepares the system to grow |
| Should | Brand Guide | n/a | Keeps branding consistent across the system |
| Should | Business model and solution structure | n/a | Required project documentation |
| Must | Stock validation | Story 14 | Customers must not order items that are out of stock |
| Must | Payment integration | Story 16 | Customers must be able to pay |
| Should | Order confirmation emails | Story 15 | Gives the customer proof of purchase |
| Must | Debug and integrate backend classes; capture frontend data in the database | Stories 17 and 18 | The backend had to work before it could be deployed |
| Must | Secure authentication and JWT authorization | Story 19 | Protects every user’s profile |
| Should | Forgot password page | Story 21 | Lets customers regain access |
| Should | Email verification page | Story 20 | Ensures a valid email for order notifications |
| Must | Protected routes (login required before purchase) | Story 22 | Only logged-in users may buy |
| Must | Advanced customisation: live preview, real-time pricing, validated inputs | Story 7 | Core feature for ordering |
| Must | Spring Security debugging and Render backend redeployment | Story 8 | The backend must be secure and deployable |
| Must | Prepare backend for frontend integration | Story 10 | Frontend and backend must work as one system |
| Should | Analytics widgets for the admin | Story 12 | Gives the admin store insights |
| Must | Deploy frontend to Vercel and verify it communicates with the Render backend | Story 13 | The system must be live and connected |
| Must | End-to-end testing: login, catalogue, checkout, reporting | Story 11 | Confirms the whole flow works across devices |
| Must | Regression testing (Sprint 12, Day 2) | All | Confirms nothing broke after changes |
| Must | Acceptance testing (Sprint 12, Day 3) | All | Confirms the system meets requirements |
| Must | Deploy (Sprint 12, Day 4) | Story 4 | The system must be live |
| Must | Documentation (Sprint 13, Day 1) | All | Required for handover and assessment |
| Should | Apply the department’s red colour to the system | Story 23 | Lecturer feedback on 27 October; aligns with the department’s identity |
| Must | Shorten and rehearse the presentation to fit 3 minutes | n/a | Lecturer feedback on 27 October |

![Item Hive Trello board showing the Product Backlog, Sprint In Progress and Sprint Completed lists](/images/trello-board-full.png)
*Figure 3: The Item Hive Trello board: Product Backlog (19 cards), Sprint: In Progress (5) and Sprint: Completed (40).*

## Reflection

<div class="reflection" markdown="1">

**What.** The backlog holds 19 items, ordered by value to the system and by dependency: the catalogue, authentication and ordering first, then the admin features and expansion, and finally testing, deployment and documentation.

**So what.** Our priorities changed as we learned more. Sprint 1 was planning, setup and the core catalogue. Later sprints added authentication, order creation, the admin dashboard and the expansion model. In September and October the backlog moved toward advanced customisation, Spring Security debugging, deploying the frontend on Vercel and the backend on Render, analytics widgets and end-to-end testing, followed by regression, acceptance, deployment and documentation. After our presentation on 27 October, new items came straight from the lecturer’s feedback: apply the department’s red colour and fit the presentation into 3 minutes. Supervisor feedback on the frontend and the Brand Guide also changed what we worked on next. I learned that a backlog is a living list and that ordering it takes judgement, because everything feels important when you are close to the work. I also see that our backlog cards read like planned sprint days, and a stronger backlog would carry priority labels so the reason for the order is visible.

**Now what.** I would add Must, Should and Could labels on Trello and hold a short backlog refinement before every sprint.

**Connect.** The top items of this list were pulled into the [Sprint Backlog](/sprint-backlog).

</div>

---
[WIL Portfolio Home](/wil-agile-portfolio) | [Team Charter](/agile-team-charter) | [User Stories](/user-stories-and-tasks) | [Product Backlog](/product-backlog) | [Sprint Backlog](/sprint-backlog) | [Agile Logbook](/agile-logbook) | [Back to my portfolio](/)
