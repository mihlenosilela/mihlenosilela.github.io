---
layout: default
title: "Agile Logbook"
---

{% include wil-style.html %}
{% include wil-nav.html %}

# 5. Agile Logbook

An Agile logbook records daily stand-ups, sprint plans and retrospective notes.

## Evidence

### Daily stand-ups

*Fifteen entries from four periods: 28 to 31 July, 4 to 7 August, 13 to 16 October and 20 to 27 October. The September and late-October logbooks recorded the task board and walkthrough only, so they appear in the walkthrough section.*

| Date | Completed since last stand-up | Planned next | Impediments |
|---|---|---|---|
| Tue 28 Jul | Completed the application screen designs and worked on the system prototype; contributed ideas to improve the UI and user experience. | Finalise remaining screens, review the prototype and prepare to present it to the supervisor. | Some design decisions were still being discussed. |
| Wed 29 Jul | Completed the prototype and presented it to the supervisor. | Review the prototype internally and prepare for changes after feedback. | No supervisor feedback, so we could not tell if the design met expectations. |
| Thu 30 Jul | Finalised the Sprint 1, 2 and 3 deliverables and reviewed completed tasks against sprint objectives. | Prepare development resources and tools for frontend implementation. | Missing feedback remained a risk of later rework. |
| Fri 31 Jul | <!-- CHECK: rewrite in your own words; the original entry repeated the previous impediment text. --> Completed the sprint review and prepared the frontend work. | Begin frontend development and turn the prototype into a working interface; I was responsible for the login page. | Still uncertain about design changes without formal feedback. |
| Tue 4 Aug | Presented the Item Hive frontend to the supervisor and received feedback. | Apply the feedback and update the Product Backlog. | Making sure we understood all the feedback correctly. |
| Wed 5 Aug | Updated the Product Backlog by moving finished sprint tasks to Completed and presented it to the supervisor. | Work on the Brand Guide so branding is consistent. | The backlog had to show all completed work. |
| Thu 6 Aug | Updated the Brand Guide, presented it, discussed supervisor feedback and made the changes. | Continue documentation and start the business model and solution structure. | Feedback meant revisiting earlier branding decisions. |
| Fri 7 Aug | Started the business model and solution structure: the problem, how the idea works and the value to customers. | Continue developing the business model so all key parts are included. | Making sure everyone understands and agrees on the final direction. |
| Tue 13 Oct | Started reviewing the backend deployment on Render and identifying the Spring Security problems that needed attention. | Continue investigating the security configuration and capture the error messages and logs. | Needed to record the exact error and whether it could be reproduced. |
| Wed 14 Oct | Reviewed what each member had tried the day before and where they left off, then continued debugging the Spring Security configuration to prepare the backend for redeployment. | Test authentication and protected-route behaviour after the changes. | The cause and fix still had to be confirmed from the logs and test results, and we were running out of time. |
| Thu 15 Oct | Continued work on backend stability and deployment readiness, focusing on how the security settings affect the deployed service. | Check application startup and the API endpoints in the Render environment. | Deployment settings or security configuration might affect how the service behaves. |
| Fri 16 Oct | Reviewed the week’s deployment and debugging progress and identified the verification still needed. | Prepare the backend for integration with the frontend and present our work. | Repeating the same work was time-consuming, and keeping integration consistent was difficult. |
| Tue 20 Oct | Our lecturer told us to prepare a presentation for the Bellville campus. | Plan and start the PowerPoint slides for the presentation. | None recorded. |
| 21 to 26 Oct | Worked as a team on the PowerPoint presentation slides. | Finish the slides and be ready to present to our lecturer. | None recorded. |
| Tue 27 Oct | Presented our ItemHive business model pitch and system to our lecturer and received feedback. | Start the changes on 28 October: add red (our department colour) to the system, and shorten and rehearse the presentation to fit the time limit. | We are only given 3 minutes, so our presentation timing needs work. |

### Weekly walkthroughs

| Week | Key points from the walkthrough |
|---|---|
| 28 July | The frontend was our key team deliverable. Bringing a new member into the team was the main blocker. |
| 4 August | No major blockers. The main risk was applying supervisor feedback while keeping the team aligned. Some members did role work not shown on the board. |
| 14 September | Advanced customisation and product management were completed; integration and testing, and reviewing and deploying the frontend on Vercel, were in progress. We needed supervisor feedback on the frontend. No blockers. |
| 21 September | Sprint 5: stock validation, order emails to the customer, payment integration, and frontend and backend integration. We needed to integrate the backend and consume its endpoints from the frontend. Nobody worked outside the board. Blocker: we could not consume the API endpoints without deploying the backend. |
| 28 September | Sprint 6: debug and integrate the backend classes, capture frontend data in the database, deploy the backend on Render, and test the integration. Nobody worked outside the board. Blocker: we could not deploy the backend without testing and debugging all the integrated backend classes. |
| 5 October | Sprint 7: secure authentication and authorization, email verification page, forgot password page, and protected routes so a user must log in before buying. We need to use Spring Boot to implement Spring Security, and the login, registration and verification pages on the frontend must be available. Nobody worked outside the board. Blocker: without the user entity on the backend, it is impossible to implement security on the frontend. |
| 12 October | The week focused on Render redeployment and debugging Spring Security. Key learning: check backend security and deployment together, not as unrelated tasks. Nobody worked outside the board. Blocker: Spring Security configuration and deployment settings. |
| 19 October | Needed to get feedback on the frontend, finish deployment checks and verify that the Vercel frontend communicates with the Render backend. Remaining: frontend deployment on Vercel, backend deployment on Render and end-to-end testing. Blocker: authentication issues. |

### Lecturer feedback on our presentation (27 October)

| Feedback | What we will do | When |
|---|---|---|
| We are only given 3 minutes, so our presentation time must improve. | Cut the presentation to the key points and rehearse it against the clock. | Starting 28 October |
| Add red to our system, to align with our department colour. | Apply the red colour to the system’s interface. | Starting 28 October |

### Retrospective

| Start | Stop | Continue |
|---|---|---|
| Asking the supervisor for feedback in writing and confirming it back. Updating Trello cards on the day the work is done. Rehearsing against the clock for timed presentations. | Waiting for feedback without following up (29 to 31 July). Updating the board in batches after the work. | Daily stand-ups, peer programming through GitHub, checklists with named owners, and the weekly walkthrough. |

### Original logbook pages

<details markdown="1">
<summary>28 to 31 July logbook (4 pages)</summary>

![28 to 31 July logbook page 1](/images/logbook-july-p1.png)
![28 to 31 July logbook page 2](/images/logbook-july-p2.png)
![28 to 31 July logbook page 3](/images/logbook-july-p3.png)
![28 to 31 July logbook page 4](/images/logbook-july-p4.png)

</details>

<details markdown="1">
<summary>4 to 7 August logbook (4 pages)</summary>

![4 to 7 August logbook page 1](/images/logbook-august-p1.png)
![4 to 7 August logbook page 2](/images/logbook-august-p2.png)
![4 to 7 August logbook page 3](/images/logbook-august-p3.png)
![4 to 7 August logbook page 4](/images/logbook-august-p4.png)

</details>

<details markdown="1">
<summary>14 September logbook (task board and walkthrough)</summary>

![14 September logbook page 1](/images/logbook-sep14-1.png)
![14 September logbook page 2](/images/logbook-sep14-2.png)
![14 September logbook page 3](/images/logbook-sep14-3.png)

</details>

<details markdown="1">
<summary>21 September logbook (task board and walkthrough)</summary>

![21 September logbook page 1](/images/logbook-sep21-1.png)
![21 September logbook page 2](/images/logbook-sep21-2.png)
![21 September logbook page 3](/images/logbook-sep21-3.png)

</details>

<details markdown="1">
<summary>28 September logbook (task board and walkthrough)</summary>

![28 September logbook page 1](/images/logbook-sep28-1.png)
![28 September logbook page 2](/images/logbook-sep28-2.png)
![28 September logbook page 3](/images/logbook-sep28-3.png)

</details>

<details markdown="1">
<summary>5 October logbook (task board and walkthrough)</summary>

![5 October logbook page 1](/images/logbook-oct5-1.png)
![5 October logbook page 2](/images/logbook-oct5-2.png)
![5 October logbook page 3](/images/logbook-oct5-3.png)

</details>

<details markdown="1">
<summary>12 October logbook (13 to 16 October stand-ups)</summary>

![12 October logbook page 1](/images/logbook-oct12-1.png)
![12 October logbook page 2](/images/logbook-oct12-2.png)
![12 October logbook page 3](/images/logbook-oct12-3.png)

</details>

<details markdown="1">
<summary>19 October logbook (task board and walkthrough)</summary>

![19 October logbook page 1](/images/logbook-oct19-1.png)
![19 October logbook page 2](/images/logbook-oct19-2.png)
![19 October logbook page 3](/images/logbook-oct19-3.png)
![19 October logbook page 4](/images/logbook-oct19-4.png)

</details>

## Reflection

<div class="reflection" markdown="1">

**What.** I kept fifteen stand-up entries across four periods (28 to 31 July, 4 to 7 August, 13 to 16 October and 20 to 27 October), each answering what was completed, what was planned and what blocked us. Across July to October I also recorded a weekly task board and walkthrough.

**So what.** Reading across the entries, the recurring blocker was feedback. On 29 to 31 July we had presented the prototype but heard nothing back, so we started the frontend unsure whether the design would be accepted. On 4 to 6 August we received feedback and had to understand it carefully before changing the frontend and the Brand Guide. As the team’s tester and editor, I felt this directly: waiting meant that work I had reviewed could still change. The weekly walkthrough also showed that a new team member slowed us in the first week and that some members did role work that was not on the board. The September walkthroughs show a chain of dependencies: on 21 September we could not consume the API endpoints without deploying the backend, and on 28 September we could not deploy the backend without first testing and debugging all the integrated backend classes. Each step was waiting on the one before it. In October the blocker changed from feedback to technical risk. The 13 to 16 October entries and the 12 and 19 October walkthroughs show our effort moving to Render redeployment and Spring Security, and authentication was still named as the only blocker a week later. The key lesson we wrote down was to check backend security and deployment together, not as separate jobs, and the entries show how time-consuming it was to repeat the same fixes while keeping the frontend and backend consistent. The logbook made these patterns visible, which I would not have noticed from memory alone. The most recent entries show the feedback loop working better. On 27 October we presented to our lecturer and left with two clear actions: keep within the 3-minute limit and add our department’s red colour to the system. In July the problem was hearing nothing, and this time the feedback arrived on the day and became next steps in the same entry. The red colour change is an interface change, so I can test it as soon as it is applied and check that the text stays readable. It also exposed a weakness in my own record keeping: not every logbook has completed daily entries, so for those weeks the task board and walkthrough are the evidence.

**Now what.** So we had intergration errors our backend and frontend had conflicts but we fixed that and our system worked all together then we presented on the 31st of July and everything was working.

**Connect.** The logbook shows how the charter’s stand-up rule, the backlog priorities and the sprint cards worked together, and the retrospective turns these lessons into changes for my next project.

</div>

---
[WIL Portfolio Home](/wil-agile-portfolio) | [Team Charter](/agile-team-charter) | [User Stories](/user-stories-and-tasks) | [Product Backlog](/product-backlog) | [Sprint Backlog](/sprint-backlog) | [Agile Logbook](/agile-logbook) | [Back to my portfolio](/)
