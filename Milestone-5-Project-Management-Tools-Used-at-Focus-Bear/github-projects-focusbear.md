# 🏆 Milestone: Familiarity with Project Management Tools

## 🔍 Research & Learn

### ❓ What is GitHub Projects, and how does it support Agile workflows?  
GitHub Projects is a project management tool integrated directly within GitHub. It helps teams organize and track work alongside their code repositories.  

It supports Agile workflows by providing customizable boards that manage sprints, backlogs, and tasks. Teams can structure these boards with columns such as **To Do**, **In Progress**, and **Done**, and link issues or pull requests to visualize progress and maintain transparency. This setup promotes efficient collaboration and real-time updates on sprint activities.

### ❓ How are sprint planning and backlog refinement managed in GitHub Projects?  
Sprint planning in GitHub Projects is managed by organizing issues into boards or lists representing the sprint backlog. Teams can prioritize tasks by ordering cards, assigning them to team members, and setting milestones or due dates.  

Backlog refinement is conducted by regularly reviewing the backlog, updating issue details, adding labels, estimates, or comments, and clarifying acceptance criteria. This ensures the backlog remains clear, prioritized, and ready for future sprints.

### ❓ What is the difference between the Sprint Planning Project and the Codebase-Specific Roadmap Projects at Focus Bear?  
The **Sprint Planning Project** focuses on short-term deliverables and tracks the day-to-day tasks for the current sprint. It helps organize immediate work, monitor assignments, and manage progress toward sprint goals.  

In contrast, **Codebase-Specific Roadmap Projects** provide a higher-level view of long-term objectives and feature development for specific areas of the product, such as the backend or frontend.  

This separation ensures clarity between the immediate tasks handled in sprints and the strategic planning captured in the roadmap projects, keeping both short-term execution and long-term vision aligned.

### ❓ How can Scrum Masters monitor sprint progress and track blockers in GitHub Projects?  
Scrum Masters monitor sprint progress in GitHub Projects by using boards that display tasks across different stages, typically **To Do**, **In Progress**, and **Done**.  

They track blockers by identifying issues that remain in the same column for too long or are labeled as “Blocked.” Regularly reviewing these boards during daily standups allows Scrum Masters to surface delays early and facilitate solutions to remove impediments.

---

## 📝 Reflection

### ❓ What are the benefits of using GitHub Projects instead of traditional Scrum boards?  
Because GitHub is already our primary workspace, using GitHub Projects allows for seamless synchronization between issues, pull requests, and project tasks. This eliminates the need for duplicate data entry, which often happens when using separate tools like Jira or Trello.  

With GitHub Projects, updates occur in real time. When a developer moves an issue to “In Progress” or closes a pull request, it’s automatically reflected on the board. This improves transparency, reduces overhead, and ensures that both the team and stakeholders have an up-to-date view of sprint progress.  

From a project management perspective, GitHub Projects streamlines sprint planning, daily tracking, and reporting. It saves valuable time and helps maintain alignment without requiring context switching between platforms.

### ❓ How can a Scrum Master ensure that tasks are correctly updated and tracked in GitHub Projects?  
As a Scrum Master, one of my key responsibilities is ensuring tasks are accurately updated in GitHub Projects to maintain transparency and alignment. During daily standups, I confirm task status directly with developers or QA members and remind the team to update their items as they make progress.  

Additionally, I conduct regular reviews of the GitHub Project board—usually at the end of each day or sprint milestone—to identify discrepancies or outdated tasks and follow up with the team as needed. Over time, this consistent attention helps foster a culture of accountability where team members take ownership of keeping GitHub Projects accurate and current.

### ❓ What are the challenges of managing Agile work in GitHub Projects, and how can they be addressed?  

⚠️ **Challenge 1: Limited Agile-Specific Features**  
GitHub Projects does not offer built-in Agile reports like velocity charts, sprint burndown charts, or cumulative flow diagrams.  
✅ **How I address it:** I manually track key metrics, such as cycle time, by exporting GitHub data into Google Sheets. I review this data during retrospectives and am also learning to integrate third-party tools like Notion and Jira to supplement GitHub’s capabilities.

⚠️ **Challenge 2: Reliance on Team Members to Update Tasks**  
Developers and interns sometimes forget to move issues between columns or close completed tasks, making it difficult to get a real-time view of progress.  
✅ **How I address it:** I follow up during daily standups to confirm task status and remind the team to update their tasks. Additionally, I plan to create a lightweight onboarding guide that outlines this responsibility for new interns joining the team.

⚠️ **Challenge 3: No Direct Time Tracking or Estimation**  
GitHub Projects lacks time tracking or estimation tools, which makes balancing workloads more challenging.  
✅ **How I address it:** We use point-based labels to indicate task complexity and discuss team capacity during sprint planning. This approach helps balance assignments, even when team members work varying schedules.

---

## 🛠️ Task

### ❓ Identify the current sprint project and a codebase-specific roadmap project.  Write a short summary of how GitHub Projects is used for sprint planning & backlogs at Focus Bear.
Based on my observations of the **Team Windows App Roadmap Project**, Focus Bear uses GitHub Projects to manage sprint planning and backlogs by organizing issues into clearly defined, prioritized columns that reflect the different stages of development.

Tasks move through stages such as **Backlog**, **In Progress**, **Clarification Needed**, **QA**, and **Done**, which helps the team visualize workflow throughout the sprint. Priority labels like **High Priority**, **Very Low Priority**, and **Super Low Priority** guide the team on what to tackle first. For example, when a developer begins work on a task, they move it to **In Progress**. If clarification is needed, the task is moved to **Clarification Needed**. Once complete, it transitions to **QA**, as seen with the task *“Always blocked URLs - show the oops I actually need it”*, which is currently awaiting review.

This setup allows both developers and project managers to track progress in real time, quickly identify blockers (such as tasks marked **Clarification Needed** or **Blocked**), and ensure work is progressing smoothly toward sprint goals.
