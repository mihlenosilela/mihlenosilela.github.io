---
layout: default
title: "Sprint Backlog"
---

{% include wil-style.html %}
{% include wil-nav.html %}

# 4. Sprint Backlog

A sprint backlog is the actionable plan of the work the team commits to in one sprint, linked to a sprint goal.

## Evidence

<!-- CHECK: confirm the Sprint 11 goal and add the Day 3 card name from your board. -->

### Sprint 1 (worked example, 13 to 14 July)

| Card | Goal | Tasks | Result |
|---|---|---|---|
| Day 1: Project planning and setup | Create the repository and folder structure | Checklist 5/5 | Completed (“Good” label) |
| Day 2: Core product catalog | Let a customer see price, size and picture | Data model, sample data, API endpoints, filtering, unit tests, each with an owner | 5/5 completed |

### Sprint 11

| Item | Detail |
|---|---|
| Sprint goal | Update the expansion model and complete the catalogue UI so the system is ready for regression, acceptance testing and deployment. |
| Day 1 | Expansion model updates |
| Day 2 | Catalogue UI |
| Day 4 | Deploy: purchase testing, debugging, UX improvements, demonstration and deployment |
| Next | Sprint 12, Day 1: End-to-end testing |
| Related work (October) | Render redeployment and Spring Security debugging; analytics widgets tested and deployed; frontend on Vercel, backend on Render |
| Team | All six members assigned |

### Final sprint: Sprint 16, Day 4 (Final deployment and handover)

| Task | Owner |
|---|---|
| Production health check | Siphokuhle Nyana |
| Final fixes | Sinobawo Nkomo |
| Complete documentation | Olwethu Mtwazi |
| Project closure report | Athini Ngquke |
| Handover and celebration | Mihle Nosilela |

The card’s user story is written for a QA Engineer: confirm the final version is stable and that documentation and handover are complete, so the project can be closed and supported in the future. All five tasks are complete.

![Trello card Sprint 16 Day 4 Final deployment and handover](/images/trello-card-sprint16.png)
*Figure 4: Trello card “Sprint 16: Day 4 - Final deployment & handover”, 100% complete.*

### Later sprints on the board

Sprint 12: Regression (Day 2), Acceptance (Day 3), Deploy (Day 4). Sprint 13: Documentation (Day 1). The system has since been tested and deployed, and all of these cards are now in Completed. After our presentation on 27 October, the next changes (the department’s red colour and a timed 3-minute presentation) start on 28 October.

![Trello board with Product Backlog 0, Sprint In Progress 0 and Sprint Completed 64](/images/trello-board-final.png)
*Figure 5: The Item Hive board at the end of the project: all 64 cards are in Sprint: Completed.*

![Trello Sprint 3 cards Authentication and Profile Dashboard, both 5/5](/images/trello-sprint3-cards.png)
*Figure 6: Completed Sprint 3 cards: Day 1 Authentication and Day 2 Profile Dashboard, each with a 5/5 checklist.*

![Trello Sprint 4 cards Payment integration and Integration and deployment](/images/trello-sprint4-cards.png)
*Figure 7: Completed Sprint 4 cards: Day 3 Payment integration and Day 4 Integration and deployment.*

### Why many cards were moved to Completed in bulk

Our team forgot to move cards to Completed as each sprint day finished, because we were busy building and testing. We therefore moved them in bulk, which is why the activity logs show many cards moved on the same day (for example 6 August) and why a few cards were reopened and finished again (the payment integration card was moved back to In Progress on 16 September and completed on 24 September). The checklists, card owners and logbooks show the real work, while the move dates only show when we updated the board.

## Reflection

<div class="reflection" markdown="1">

**What.** Across the project we completed 64 cards, starting with project setup on 13 July, and each sprint was broken into daily cards with a checklist. My own sprint work covered the catalogue API endpoints, the order-creation step of the payment flow, testing, editing our project documents, and the final handover task.

**So what.** Cards with named owners made the work visible, and the green “Good” label with a full checklist told us clearly when something was finished. We delivered a working, deployed system, so the process worked. The weakness was how we recorded it: we forgot to move cards to Completed as we finished them, so we moved them in bulk. The activity logs show this, for example on 6 August, and at the end of the project all 64 cards were moved to Completed together. That made the board less useful for tracking progress during the sprints and taught me that a board is only as honest as its last update.

**Now what.** I would update cards during the daily stand-up and estimate each sprint with the whole team, leaving time for testing.

**Connect.** The daily progress behind these cards is recorded in the [Agile Logbook](/agile-logbook).

</div>

---
[WIL Portfolio Home](/wil-agile-portfolio) | [Team Charter](/agile-team-charter) | [User Stories](/user-stories-and-tasks) | [Product Backlog](/product-backlog) | [Sprint Backlog](/sprint-backlog) | [Agile Logbook](/agile-logbook) | [Back to my portfolio](/)
