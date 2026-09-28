# employee-attrition-analysis-tableau
Tableau dashboard analysing attrition across 1,470 employees by department, age, job role, and overtime
# Employee Attrition Analysis | Tableau


## Why This Project
When employees leave, companies lose experience and pay to replace them. This project studies an HR dataset of 1,470 employees to see **who is leaving and which groups are at higher risk**, and presents the results in an interactive Tableau dashboard.

## Questions Explored
- What share of employees left, and how does that differ by department?
- Which age groups and job roles lose the most people, relative to their size?
- Do overtime, business travel, or marital status go with higher attrition?
- Do people who left earn less or have shorter tenure than those who stayed?

## Data
HR employee dataset with 1,470 rows and 35+ fields (age, department, job role, income, overtime, tenure, satisfaction, and whether the person left). 

## Tools
Tableau Public (dashboard), Excel (data checking)

## Headline Numbers
| Employees | Left | Attrition Rate | Still Employed | Average Age |
|---|---|---|---|---|
| 1,470 | 237 | 16.12% | 1,233 | 37 |

## What I Built
- KPI cards for headcount, leavers, and attrition rate
- Attrition **rate** (not just count) by department, age group, and job role
- Comparison of attrition for overtime vs no overtime
- Income and tenure comparison for leavers vs stayers
- Filters so the views can be explored by group

## Findings
**Counts can mislead, rates tell the real story.** R&D has the most leavers (133), but the lowest rate (13.8%). Sales loses 20.6% of its people and HR 19.0%.

**Younger employees leave most.** Employees under 25 leave at 39.2%, and ages 25 to 34 at 20.2%. Rates drop to about 10% for ages 35 to 54.

**Workload and travel stand out.**
- Employees working overtime leave at 30.5%, compared with 10.4% for those who don't.
- Frequent travellers leave at 24.9%, compared with 8.0% for non-travellers.
- Single employees leave at 25.5%, compared with about 10 to 13% for married and divorced employees.

**Role, pay, and tenure.**
- Sales Representatives have the highest role-level rate (39.8%), followed by Laboratory Technicians (23.9%).
- Leavers had a median monthly income of $3,202 against $5,204 for stayers, and a median tenure of 3 years against 6.

## Limitations
These are patterns in one dataset and don't prove what causes people to leave. Some groups are small (for example, 63 employees in HR and 97 under 25), so their rates can swing easily.

## Suggested Next Steps
- Look closely at overtime policies in high-attrition roles
- Review pay and early-career support for the first 3 years
- Track attrition rate over time if dated data becomes available


## Repository Contents
| File | Description |
|---|---|
| `employee_attrition_dashboard.twbx` | Tableau workbook (includes data) |
| `hr_data.csv` | Dataset |
| `dashboard.png` | Dashboard screenshot |

## Acknowledgements
Learned the workflow through a guide; analysis and write-up done by me.
