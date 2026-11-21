# LuxeMart Employee Retention: Business Analysis Case Study

![LuxeMart retention dashboard](LuxeMart%20Dashboard%201.png)

> **The problem:** LuxeMart's customer support and warehouse staff keep leaving, and HR doesn't know why.
>
> **What I found:** turnover was moderate (7.9%, below the UK average), but the warning signs were strong: 43% of staff dissatisfied, twice the overtime of other teams, and 1 in 4 hires gone within three years.
>
> **What I delivered:** three evidenced root causes, 29 prioritised requirements, a Jira-ready backlog, a BRD and a 12-month roadmap. I presented the findings and recommendations to the key stakeholders, who accepted them.
>
> **My role:** sole business analyst on a case from the Amdari business analysis programme. The brief and dataset were provided; all analysis, documentation and the dashboard are my own work.

**[View the live interactive dashboard](https://lolabode.github.io/luxemart-employee-retention/)**

---

## At a glance

| Business analysis skill | Evidence in this project |
|---|---|
| Problem framing | Six case questions, clear scope, and a brief I challenged with a UK benchmark |
| Stakeholder analysis | 14 stakeholder groups on a power-interest grid; RACI across 22 activities |
| Process mapping | As-is and to-be swimlanes, with assumed steps clearly marked |
| Root cause analysis | Fishbone diagram for breadth, five whys for depth |
| Requirements | 28 functional and 17 non-functional requirements; 23 use cases |
| Prioritisation | MoSCoW across 29 requirements |
| User stories | 29 stories with 62 Given/When/Then acceptance criteria, in 6 epics |
| Testing and traceability | 24 UAT scenarios; every requirement traced to a root cause and a test |
| Data analysis | 500-employee HR dataset analysed in Excel and Python; interactive dashboard |
| Communication | BRD, retention strategy, stakeholder presentation |

## 1. The question

**Why are LuxeMart's customer support and warehouse staff leaving, and what can LuxeMart change to keep them?**

1. How big is the problem?
2. Who is most affected?
3. Why do they leave?
4. When do they leave?
5. Can LuxeMart see it coming?
6. What should change, and how will we know it worked?

**Scope:** UK only, customer support and warehouse teams, no pay changes and no new software.

## 2. What the data showed

| | |
|---|---|
| **7.9%** | Turnover in 2024, below the UK average of about 15% (CIPD, 2025), but rising |
| **43%** | Rate their job satisfaction 1 or 2 out of 5 (16% in HR, IT and Management) |
| **48%** | Of resignations cite overtime or work-life balance; only 15% cite pay |
| **10.5 hrs** | Average overtime per person per month, about twice other teams |
| **1 in 4** | Hires gone within three years |

![Dashboard: workload and tenure](LuxeMart%20Dashboard%202.png)

*The dashboard opens on all departments (46% of resignations cite workload). Filter to Customer Support and Warehouse to see the 48% quoted above.*

### Decisions I made along the way

- **I challenged the brief.** It said turnover was high. A UK benchmark showed it was below average, so I reframed the story around the warning signs underneath it.
- **I checked a finding before presenting it.** I nearly reported that frontline staff leave the most, but HR, IT and Management actually had higher turnover in 2024 (12.3%).
- **I used a retention curve, not a simple count,** so people still employed were included fairly in the "1 in 4" figure.
- **I reported what the data could not do.** Leavers and stayers scored almost the same, survey scores were undated, and a predictive model performed no better than chance. That gap became a recommendation.

### Limits I flagged

- No hires were recorded after 2023, which flatters the 2024 turnover rate.
- A 20 to 30% cut in turnover means only 4 to 5 fewer leavers a year, so results should be judged over two years.
- Exit reasons are what people said when they left, not proven cause and effect.

## 3. As-is process

![As-is swimlane](AS-IS%20Swimlane.png)

A concern raised with a manager goes nowhere, and HR first hears about a problem when someone resigns. Dashed steps are assumptions to confirm with supervisors.

## 4. Root causes

![Fishbone diagram](Fishbone%20Diagram.png)

**Three root causes:**

1. Scheduling has no capacity planning, fairness rules or overtime monitoring.
2. There is no structured development journey from onboarding to promotion.
3. Retention has no owner, KPIs or early warning data.

Two links in the five whys chains are assumptions and should be validated in a workshop.

## 5. To-be process

![To-be swimlane](TO-BE%20Swimlane.png)

The future journey adds control points (fair rota rules, a swap process, overtime limits) and early warning (check-ins, a pulse survey, exit interviews and a monthly leadership review).

## 6. Requirements, prioritisation and traceability

- **MoSCoW:** 29 requirements: 12 Must (52% of in-scope items), 6 Should, 5 Could and 6 Won't.
- **Requirements:** 28 functional and 17 non-functional, covering UK GDPR, working time rules, accessibility and data quality.
- **Use cases:** 23 use cases across 8 actors.
- **User stories:** 29 stories in 6 epics, with 62 Given/When/Then acceptance criteria and a MoSCoW priority each, ready for a delivery team.
- **Testing:** 24 UAT scenarios.

![MoSCoW board](MoSCoW%20Board.png)
![Use case diagram](Use%20Case%20Diagram.png)

**Traceability:** every requirement links back to a root cause and forward to a test.

![Traceability matrix](Traceability%20Matrix.png)

## 7. How I gathered requirements

There were no live interviews, so I elicited requirements from the brief and the 500-employee HR dataset. To close the evidence gap, I designed an employee satisfaction survey, a 10-question quarterly pulse survey and interview questions for each stakeholder group. Every assumed process step is clearly marked.

## 8. Recommendations

1. **Confirm a hiring plan first,** then set overtime limits and fair rota rules. Headcount is down 13%, so limits alone would leave rotas uncovered.
2. **Name a retention owner,** and launch a quarterly pulse survey and exit interviews.
3. **Validate the root causes** with staff and managers before signing off the BRD.
4. **Ask Finance for the cost per hire,** so savings can be calculated rather than guessed.
5. **Introduce recorded 30, 60 and 90-day check-ins** and regular manager one-to-ones.
6. **Publish career pathways** and advertise vacancies internally first.

## 9. Measuring success

The turnover target (a 20 to 30% reduction, from the brief) means about 4 to 5 fewer leavers a year. I set 17 KPIs with baselines and targets so benefits can be tracked. Once Finance confirms the cost per hire, the saving is: fewer leavers × cost per hire, plus training time saved. I deliberately didn't estimate a cost, because the data didn't include one.

## 10. Business documentation

| Document | What it covers |
|---|---|
| Business Requirements Document (BRD) | Problem, scope, stakeholders, as-is and to-be, root causes, requirements, recommendations, KPIs, risks |
| Retention strategy and KPIs | 5 recommendations, 12-month roadmap, risk register, 17 KPIs with baselines and targets |
| Employee satisfaction survey | Baseline survey and a 10-question quarterly pulse, each question linked to a pain point |
| Requirements workbook | MoSCoW, functional and non-functional requirements, traceability |
| Risks, assumptions and test scenarios | Risk register, assumptions log, 24 UAT scenarios |
| Stakeholder presentation | The case study story, from question to recommendations |

![BRD preview](BRD%20Preview.png)

## 11. What I would do differently

- **Run real stakeholder interviews** to replace the assumed process steps.
- **Find a turnover benchmark on day one,** because it changed my whole narrative.
- **Draft the KPI table in week one** and refine it as the data came in.

## 12. Lessons learned

The biggest lesson was to question the brief. It said turnover was high, but the data said turnover was moderate with strong warning signs. Reporting what the data showed, including what it couldn't show, made the recommendations more credible.

I also learned to keep diagrams simple for non-technical audiences. My first use case diagram was unreadable, so I split it into four panels, and I removed colour tags from the fishbone because they confused people.

## Tools and skills

**Business analysis:** stakeholder analysis, RACI, process mapping, root cause analysis, MoSCoW, BRD, functional and non-functional requirements, use cases, user stories, acceptance criteria, UAT, traceability, risk management, KPI design

**Tools:** Jira, Excel, Python, HTML and Chart.js, draw.io, Word, PowerPoint

## Files in this repository

| File | Contents |
|---|---|
| `index.html` | Live interactive dashboard |
| `LuxeMart Dashboard 1.png`, `LuxeMart Dashboard 2.png` | Dashboard screenshots |
| `AS-IS Swimlane.png`, `TO-BE Swimlane.png` | Process maps |
| `Fishbone Diagram.png` | Root cause analysis |
| `MoSCoW Board.png`, `Use Case Diagram.png`, `Traceability Matrix.png` | Requirements artefacts |
| `BRD Preview.png` | Preview of the Business Requirements Document |

**Note on the data:** the HR dataset belongs to the case study and is not included in this repository.
