# Sales Funnel & Churn Diagnostics: Set2Close (Master's Capstone)

**Client analytics engagement · Northeastern University M.P.S. Analytics · June 2025**

Set2Close is a B2B sales-enablement and RevOps consultancy (HubSpot Elite Partner, 500+ CRM projects). It gave our team access to its own sales and service data. There was no fixed brief: the task was to explore the data and find out **why leads weren't converting and why customers were churning**, then recommend operational changes to leadership.

> **Data notice:** the analysis used Set2Close's proprietary CRM and service-activity data on the client's visualization platform. That data and the dashboards built on it are confidential, so they are not in this repository. This README documents the questions, method, findings and recommendations. Client-specific figures and employee names are left out.

---

## Business questions

1. Revenue lost to churn was offsetting much of the new ARR from closed-won deals. **Where is post-sale value leaking?**
2. Account volume dropped steeply between funnel stages. **Which handoffs are slow, and why?**
3. **Is sales effort reaching leads at the right stage**, and is the workload sustainable for a lean team?

## Approach

| Step | What we did |
|---|---|
| **Revenue bridge** | Compared new ARR from closed-won deals with churned revenue to size the retention problem |
| **Funnel conversion, year over year** | Tracked account transitions Lead → MQL → SAL → SQL → Won / Churned, 2024 vs. 2025 |
| **Activity by stage** | Average touches per account at each stage, split by activity type (calls, emails, meetings) |
| **Speed to stage** | Days for each rep to move accounts Lead → MQL → SQL |
| **Workload distribution** | Heatmap of logged activity by employee and functional role (Outbound SDR, account management, and so on) |
| **Cohort analysis** | Conversion to Won by SAL-month cohort over the months after acceptance |

## Findings

- **Closing more, keeping fewer.** Conversion to Won rose sharply from 2024 to 2025, but churned accounts rose just as sharply. Volume in the early stages (MQL, SQL, SAL) stayed steady, so the problem is **retention and post-sale service, not lead generation**.
- **Effort arrives late in the funnel.** The SQL stage got roughly two to three times the touches of Lead, MQL or SAL, mostly meetings. Calls were underused at every stage.
- **Handoff speed varies widely between reps.** Moving accounts to Lead and MQL took anywhere from about 9 to 30 days depending on the rep, and some reps took 40+ days to reach SQL. That points to inconsistent qualification rules and follow-up rather than lead quality alone.
- **Outbound SDR work is concentrated.** A few people handle most client-facing activity, which risks burnout and an uneven client experience. Activity logged to former staff also inflated the totals, so the data had to be cleaned before staffing could be read accurately.
- **Recent cohorts perform much better.** SAL cohorts from early 2025 converted at several times the rate of mid-2024 cohorts in their first three months, which plateaued in the low single digits. Something in the newer process is working.

## Recommendations presented to leadership

1. **Support high-effort roles** such as Outbound SDR with tooling, automation or clearer role definitions, and consider a dedicated retention or customer-success function as the company scales.
2. **Engage earlier.** Shift some effort to Lead and MQL stages and mix activity types (calls, emails, meetings).
3. **Set clear stage-transition rules and response-time expectations** (SAL → SQL especially) so reps qualify and hand off consistently.
4. **Copy what works in recent cohorts.** Identify the process changes behind early-2025 performance and make them standard.
5. **Improve data hygiene.** Reassign or flag activity owned by former employees so workload and capacity reporting reflect the current team.

## Skills demonstrated

Funnel and conversion analysis · cohort analysis · revenue churn bridge · sales-activity and workload analytics · data cleaning of CRM exports · dashboard storytelling · presenting recommendations to client leadership

**Tools:** SQL, Python (pandas), Power BI / Tableau, plus the client's HubSpot-based reporting platform

**Team:** Sukrit Tripathi, Tingyu Long, Kshama Upadhyay, Nikhil Kumar, Shilin Wang · Advisor: Prof. Kenneth Parker

---

Repository maintained by [Kshama Upadhyay](https://github.com/Kshama16).
