# 📋 Management Task Tracking Dashboard — Advanced Excel Project

> **MBA Portfolio Project | Task Analytics | Project Management | KPI Dashboard**

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Domain](https://img.shields.io/badge/Domain-Project%20Management-blue)

---

## ⬇️ Download Project Files

| File | Description | Link |
|------|-------------|------|
| 📋 Excel Workbook | Full task tracking tool with dashboard, cleaned data & lookup sheets | [Download Excel](https://github.com/atishey4/management-task-tracking-dashboard/raw/main/Management_Task_Tracking_Dashboard%20Final%202.xlsx) |

---

## 📸 Screenshots

![Dashboard](screenshots/Screenshot%202026-04-14%20004315.png)

---

## 📌 Project Objective

To build an Excel-based task tracking and management dashboard that cleans messy raw task data, standardizes inconsistent entries across departments and roles, and generates an interactive KPI dashboard to monitor task status, team performance, and project health across an organization.

---

## 🏢 Industry Relevance

Task and project tracking is a core function in every organization. Tools like Jira, Asana, and Monday.com are built on the same principles demonstrated here — tracking task status, priority, resource allocation, and delivery timelines. This Excel-based solution replicates those capabilities using Power Query, PivotTables, and dynamic dashboards, making it highly relevant for PMO Analysts, Operations Managers, and Business Analysts.

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Core platform for data, formulas, and dashboard |
| Power Query | Data import, cleaning, and standardization |
| PivotTables | Dynamic task and performance aggregation |
| Excel Charts | Bar, column, donut, and pie visualizations |
| Slicers & Timeline | Interactive filtering by status, priority, department |
| SUMIFS, COUNTIFS, IF, IFS, IFERROR | KPI and task logic |
| XLOOKUP / INDEX-MATCH | Lookup-based data standardization |
| Conditional Formatting | Priority and status highlights |

---

## 📁 Folder Structure

```
management-task-tracking-dashboard/
│
├── Management_Task_Tracking_Dashboard Final 2.xlsx   # Main Excel workbook
│
├── screenshots/
│   └── Screenshot 2026-04-14 004315.png
│
└── README.md
```

---

## 📊 Dataset Description

The dataset contains **120 tasks** across **10 projects**, **8 departments**, and **15+ team members**, with messy raw data that is cleaned and standardized before analysis.

### Task Table (`RawData` / `CleanedData`)
| Column | Description |
|--------|-------------|
| Task ID | Unique task identifier (TSK-0001 to TSK-0120) |
| Project Name | Associated project (CRM Migration, Product Launch, etc.) |
| Department | IT / Finance / HR / Sales / Marketing / Operations |
| Assigned To | Team member name |
| Role | Analyst / Developer / Manager / Designer / Tester / Lead / Coordinator |
| Priority | Critical / High / Medium / Low |
| Task Category | Development / Testing / Design / Planning / Research / Review / Documentation / Deployment |
| Start Date | Task start date |
| Due Date | Task due date |
| Completion Date | Actual completion date (if completed) |
| Task Status | Completed / In Progress / Not Started / On Hold / Cancelled |
| Progress % | Percentage of task completed |
| Estimated Hours | Planned effort in hours |
| Actual Hours | Actual effort logged |
| Variance | Actual Hours − Estimated Hours |
| Remarks | Notes and blockers |

---

## 📋 Excel Sheet Structure

| Sheet | Purpose |
|-------|---------|
| `RawData` | Original messy task data with inconsistent casing, formats & values |
| `Lookup_Lists` | Standardization maps for Priority, Status, Department, Category & Role |
| `CleanedData` | Fully standardized and validated task data |
| `Dashboard` | Interactive task tracking KPI dashboard |

---

## 📈 Key KPIs Tracked

- ✅ **Total Tasks** — 120 across 10 projects
- ✅ **Task Status Breakdown** — Completed / In Progress / Not Started / On Hold / Cancelled
- ✅ **On-Time vs Delayed Completion** — Based on Due Date vs Completion Date
- ✅ **Avg Estimated vs Actual Hours** — Effort variance analysis
- ✅ **Tasks by Priority** — Critical / High / Medium / Low distribution
- ✅ **Tasks by Department** — Workload across IT, Finance, HR, Sales, Marketing, Operations
- ✅ **Tasks by Project** — CRM Migration, Product Launch, Mobile App v2, and more
- ✅ **Tasks by Category** — Development, Testing, Design, Planning, etc.

---

## 💡 Business Insights Derived

1. **High backlog in Critical & High priority** — Significant tasks are On Hold or Not Started despite high priority, signaling resource bottlenecks
2. **Effort overruns are common** — Many tasks show negative variance (Actual > Estimated), indicating planning gaps
3. **Product Launch has the most tasks** — Highest task volume project across departments
4. **IT & HR carry the highest load** — Most tasks are assigned across these two departments
5. **Cancellations cluster in Supply Chain & CRM** — Repeated cancellations suggest scope or dependency issues

---

## 📝 Resume-Ready Project Descriptions

**One-liner:**
> Built an Advanced Excel Management Task Tracking Dashboard with data cleaning, standardization, and an interactive KPI dashboard to monitor project health and team performance.

**ATS-Friendly Version:**
> Designed a Management Task Tracking Dashboard in Microsoft Excel for 120 tasks across 10 projects and 8 departments. Cleaned and standardized messy raw data using Power Query and lookup-based normalization (XLOOKUP, IFS). Tracked KPIs including task status, priority distribution, effort variance, and on-time delivery. Built an interactive dashboard with PivotTables, slicers, and conditional formatting to support data-driven project management decisions.

---

## 👤 Author

**Atishey Jain**  
MBA Student | IMI Delhi  
🔗 [GitHub](https://github.com/atishey4) | [LinkedIn](https://www.linkedin.com/in/atishey-jain-66430715b/)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
