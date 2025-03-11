# 📈 Understanding Agile Metrics & KPIs

## 🔍 Research & Learn

### ❓ What are key Agile metrics (e.g., velocity, cycle time, burndown charts, lead time)?  
🚀 **Velocity** – Measures the amount of work (usually in story points) a team completes in a sprint. It helps forecast future sprint capacity and plan releases.  
⏱️ **Cycle Time** – Tracks the time it takes for a work item to move from "in progress" to "done." It highlights process efficiency and helps identify bottlenecks.  
📉 **Burndown Charts** – Visualize the remaining work in a sprint or project over time. They help monitor progress and detect if the team is on track to meet its goals.  
🕒 **Lead Time** – Measures the total time from when a task is requested to when it is completed. It reflects the speed at which customer requests are delivered.  

### ❓ How can GitHub Projects be used to track sprint progress?  
GitHub Projects can be used to track sprint progress by organizing tasks into boards with columns representing different workflow stages (e.g., **To Do**, **In Progress**, **Done**).  
- Teams create **Issues** or **Pull Requests** for sprint backlog items and move them across columns as work progresses.  
- **Labels**, **Milestones**, and **Assignees** help categorize tasks, prioritize work, and clarify ownership.  
- The **Project view** provides a clear, real-time overview of sprint status, making it easy to track progress, identify bottlenecks, and ensure that sprint goals stay on target.  

### ❓ What are the limitations of GitHub Projects for Agile metrics, and how can they be addressed?  
GitHub Projects lacks advanced built-in analytics such as, velocity tracking, cycle time measurement, and Cumulative flow diagrams (CFDs).

Additionally, key Agile metrics like: Sprint burndown charts, lead time, Work In Progress (WIP) limits aren’t directly supported within GitHub Projects.

How to address these limitations:  
- **Integrate third-party tools** – Tools such as ZenHub or Jira can overlay Agile features and reporting directly into GitHub workflows.  
- **Use GitHub’s API** – Export data to build **custom reports** and dashboards in platforms like **Tableau** or **Google Data Studio**.  
- **Combine with other platforms** – Jira, for example, adds **Agile-specific metric tracking and reporting capabilities**, providing better visibility into team performance while still syncing with GitHub for development work.  

---

## 📝 Reflection

### ❓ Which Agile metrics would be most useful for Focus Bear?  
**Cycle Time** is the most valuable metric for Focus Bear’s backend team.  
- Intern turnover creates gaps in knowledge, slowing down progress.  
- By tracking **Cycle Time**, the team gets a clear picture of how long backend tasks (features or bug fixes) take from start to finish—regardless of who is on the team.  
- If Cycle Time increases when new interns join, it signals that onboarding or lack of mentorship is impacting productivity.  
- This insight helps Focus Bear focus on **improving documentation and knowledge-sharing practices**.  
- Predictable delivery is key, and **Cycle Time** helps maintain a steady flow of work to ensure users get regular improvements, despite intern turnover.  

### ❓ What challenges could arise when interpreting sprint data?  
- 🔄 **High Team Turnover** – Changes in team structure cause productivity metrics (like velocity and cycle time) to fluctuate. This makes it difficult to establish consistent baselines or spot clear trends.  
- ❓ **Lack of Context** – Sprint data (like cycle time) might show delays, but without context—such as new team members onboarding, unclear requirements, or technical debt—it’s easy to misinterpret the reasons behind slower progress.  

### ❓ How can data-driven insights help resolve team bottlenecks?  
**Cycle Time** highlights where tasks are getting stuck (review, testing, handover stages). Frequent team changes make onboarding and documentation critical—metrics pinpoint inefficiencies.Tools like **Cycle Time** and **Cumulative Flow Diagrams (CFD)** reveal which workflow stages (e.g., review, testing, deployment) slow things down.  
Scrum Masters or team leads can use this data to:  
  - Pinpoint process inefficiencies.  
  - Reallocate resources.  
  - Improve workflows.  

For example, if data shows long delays in code reviews, the team could:  
  - Introduce peer reviews.  
  - Dedicate specific time for pull request reviews.  
- This targeted approach helps teams make informed decisions and continuously improve delivery processes.  


