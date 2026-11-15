# Team 16 (DND) — Project deliverables, in lesson-plan order

Each folder holds the project deliverable due alongside that lab in the SE lesson plan.
The source code is in `backend/` and `frontend/` at the top of the repo.

| # | Lab | Project deliverable (lesson plan) | Folder |
|---|-----|-----------------------------------|--------|
| 1 | Lab 1: Requirements engineering and use cases<br>Lab 2: Jira hands-on | Deliverable 1: SRS; Jira update started | [Lab1-2_Deliverable1_SRS](Lab1-2_Deliverable1_SRS) |
| 2 | Lab 2: Jira backlog and sprint simulation | Deliverable 2: Project Test Plan; complete Jira backlog | [Lab2_Deliverable2_TestPlan_JiraBacklog](Lab2_Deliverable2_TestPlan_JiraBacklog) |
| 3 | Lab 3: Architectural pattern and component diagram | Deliverable 3: SW Architecture document | [Lab3_Deliverable3_SW_Architecture](Lab3_Deliverable3_SW_Architecture) |
| 4 | Lab 4: AI-assisted development | Deliverable 4: SW Design document and Validation Spec update | [Lab4_Deliverable4_SW_Design](Lab4_Deliverable4_SW_Design) |
| 5 | Lab 5: Static code analysis | Deliverable 5: Sprint 1 completed; retrospective | [Lab5_Deliverable5_Sprint1](Lab5_Deliverable5_Sprint1) |
| 6 | Lab 6: Code and branch coverage | Deliverable 6: Sprint 2 completed; retrospective; coverage | [Lab6_Deliverable6_Sprint2](Lab6_Deliverable6_Sprint2) |
| 7 | Lab 7: Fuzzing for input validation | Final: all test reports, System Validation Report and Maintenance Plan, demo | [Lab7_Final_Validation_and_Demo](Lab7_Final_Validation_and_Demo) |

## Contents

1. **SRS:** `Team16_SRS.pdf`
2. **Test Plan and Jira:** `Team16_Project Test Plan.docx`, `Team16_Jira Backlog.xlsx`, Jira import CSV. Live tracking is in GitHub Issues and the Project board.
3. **Architecture:** `Team16_SW Architecture.docx`, component diagram (`.drawio` and `.pdf`)
4. **Design:** `Team16_SW_Design.docx` (UML, API and ABI, division of work), `Team16_Validation_Spec_Update.docx` (test plan v2.0, traceability)
5. **Sprint 1:** `Sprint1.mp4`, `retrospectives.md`. Static analysis runs in CI with ruff, the ESLint frontend lint and the SonarQube quality gate (`.github/workflows/ci.yml`).
6. **Sprint 2:** `Sprint2.mp4`, `test-and-coverage-report.md` (270 tests, 97.7% line and 90.3% branch coverage; CI enforces an 85% gate)
7. **Final:** `Team16_System_Validation_Report_and_Maintenance_Plan.docx`, `demo-script.md`, `deviations.md`
