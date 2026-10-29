# University Attendance Trends by Field and Gender (1989–2009)

A Tableau analysis of 20 years of university data across 17 fields of study, tracking how enrolment grew and how the balance between men and women changed.

**Tools:** Tableau (calculated fields, area charts, dashboards), Excel

## Business question

Which fields are growing, and where do gender gaps remain? This is the kind of question a university recruitment or planning team would ask when deciding where to focus outreach.

## Approach

1. Loaded yearly counts of men and women for each of 17 fields (1989–2009).
2. Created two calculated fields in Tableau:
   - **Total attendees** = Males + Females
   - **Gender Imbalance** = Males − Females
3. Built area charts of totals and gender imbalance over time, and combined them into dashboards.

## Key findings

- **Overall numbers grew 50%,** from 921,056 in 1989 to 1,379,042 in 2009.
- **Women became a growing majority,** rising from 52% to 57% of the total.
- **The fastest-growing fields** were Arts (+132%), Biology (+125%) and Health (+101%).
- **Engineering was the only field to shrink** (−2%).
- **Large gender gaps remain at both ends:**

| Field (2009) | Share of women |
|---|---|
| Health | 85% |
| Public Administration | 82% |
| Education | 79% |
| Computer Science | 18% |
| Engineering | 16% |

- **"STEM" shifted toward women overall,** from 46% women in 1989 to 55% in 2009. This dataset counts Health, Psychology, Social Science and Agriculture as STEM, and that growth came mainly from those fields. Engineering and Computer Science stayed below 20% women.

## Recommendations

1. **Target women in Engineering and Computer Science.** These are the biggest gaps, and the overall STEM numbers hide them.
2. **Target men in Health and Education,** where they are now a small minority.
3. **Plan capacity for Arts, Biology and Health,** where demand more than doubled, and review the flat Engineering pipeline.

## Files

| File | Contents |
|---|---|
| `Tableau-Unibversity_Attendees.twb` | Tableau workbook: 3 graphs and 3 dashboards |
| `Degrees-Data.xlsx` | Source data: field, STEM flag, year, males, females |
