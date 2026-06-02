# Post-Workshop Attendee Guide

Use this guide after the **Metrics-Based Process Mapping for Automation Discovery** workshop to continue the work started in the session.

The workshop is designed to help identify candidate automation opportunities, but the real value lies in validating the process, gathering evidence, and deciding the next best action

> **Map the work. Measure the pain. Automate with purpose.**

---

## 1. What we covered

In the workshop, we explored a lightweight approach to assessing automation opportunities

The core method was:

```text
Map the work → Measure the pain → Decide the response → Prioritise the opportunity.
```

This means:

| Step | What it means |
|---|---|
| **Map the work** | Understand how the process happens today |
| **Measure the pain** | Add evidence about effort, delay, rework, risk or impact |
| **Decide the response** | Determine whether automation, improvement, standardisation or investigation is needed |
| **Prioritise the opportunity** | Focus on the candidates that are valuable, feasible and ready |

The aim was not to design a final solution in the room. The aim was to identify whether a candidate process is worth taking forward, what evidence is missing and what should happen next.

---

## 2. What to do next

After the workshop, select 2–3 candidate processes or opportunities to take forward.

For each candidate, the next step is to:

1. Validate the process with people who do the work.
2. Confirm the start point, end point and desired outcome.
3. Capture the main steps, systems, decisions, handoffs and exceptions.
4. Gather or estimate useful metrics.
5. Identify whether the pain is effort, flow, quality, risk or user impact.
6. Assess value, feasibility and readiness.
7. Decide whether the opportunity should be automated, improved first, investigated further or deferred.
8. Add the opportunity to the backlog if it is worth tracking.

Keep the focus on the next best action rather than trying to solve everything at once.

---

## 3. Validate your process

Before moving into automation design, make sure the current process is understood.

Use the `process-mapping-canvas.md` template to validate:

- What starts the process
- Where the process begins and ends
- What outcome is needed
- Who is involved
- What systems, tools, forms or spreadsheets are used
- Where decisions or approvals happen
- Where work moves between people or teams
- Where exceptions occur
- Where pain, delay, rework or risk exists

### Suggested validation questions

Ask people who do the work:

- Is this how the process actually works today?
- What steps are missing?
- Where does it usually slow down?
- What workarounds are being used?
- What exceptions happen most often?
- What information is usually missing or unclear?
- Which systems are used as the source of truth?
- Who owns the process end-to-end?

If people disagree about how the process works, capture that. It may mean the process needs clarification before it can be automated.

---

## 4. Gather useful metrics

You do not need every metric. Gather the metrics that best explain the pain and value.

Use the `metrics-checklist.md` template to capture useful evidence.

### Effort metrics

Use these when the pain is assiciated with manual or repetitive work.

| Metric | Question |
|---|---|
| **Volume** | How often does this happen? |
| **Touch time** | How much actual human effort is involved? |
| **Manual effort** | Where are people doing repetitive or low-value work? |

### Flow metrics

Use these when the pain is delayed, waiting, handoffs or poor visibility.

| Metric | Question |
|---|---|
| **Cycle time** | How long does the process take from start to finish? |
| **Wait time** | Where does work sit idle between steps? |
| **Handoffs** | Where does work move between people or teams? |
| **Systems used** | What tools, forms or platforms are touched across the process? |

### Quality and risk metrics

Use these when the pain is due to errors, rework, exceptions, inconsistency or risk.

| Metric | Question |
|---|---|
| **Rework / errors** | How often does work need to be corrected? |
| **Exceptions** | How often does the process deviate from the standard path? |
| **Risk impact** | What happens if something goes wrong? |
| **User impact** | Who experiences the pain, delay or poor outcome? |

### Remember

Estimates are acceptable at the start, as long as they are clearly marked as estimates.

The purpose of metrics is to answer three practical questions:

1. Where is the pain?
2. How significant is it?
3. What response is most likely to help?

---

## 5. Separate cycle time, touch time and wait time

If a process feels slow, separate the type of time involved.

| Type of time | Meaning | Example |
|---|---|---|
| **Cycle time** | Total elapsed time from start to finish | A request takes five days end to end |
| **Touch time** | Actual human effort | Someone spends 25 minutes processing it |
| **Wait time** | Time sitting idle between steps | It waits three days for approval |

A process may take several days but involves only a small amount of actual work.

If the problem is mostly **touch time**, automation may help reduce manual effort.

If the problem is mostly **wait time**, the better response may be:

- workflow routing
- reminders
- clearer approval thresholds
- fewer handoffs
- better intake
- improved visibility

Slow processes are not always effort-heavy processes.

---

## 6. Decide the likely response

Automation is one possible response, but it is not the only one.

Use the evidence to decide what kind of response is most appropriate.

| Pain point | Possible response |
|---|---|
| Missing information | Better form, validation or guidance |
| Manual data entry | Integration or data transfer automation |
| Long approval delay | Workflow routing, reminders or escalation |
| Repeated status chasing | Automated notifications or dashboard |
| Frequent rework | Standardisation, validation or clearer rules |
| Inconsistent decisions | Decision tree, policy clarification or guardrails |
| Too many exceptions | Process redesign before automation |
| Poor visibility | Tracking, reporting or workflow transparency |

Some opportunities may need process improvement before automation. Others may need a technical investigation. Some may be suitable for targeted automation now.

---

## 7. Assess value, feasibility and readiness

Use the `automation-opportunity-assessment.md` template to assess whether the opportunity is worth taking forward.

| Lens | Key question | What to look for |
|---|---|---|
| **Value** | Is this worth solving? | Time saved, risk reduced, rework reduced, better experience |
| **Feasibility** | Can we automate it? | Clear rules, stable data, system access, technical pathway |
| **Readiness** | Is the process ready? | Process owner, agreed steps, stable process, stakeholder support |

A good automation candidate is not just technically possible.

It should be:

- valuable enough to prioritise
- feasible enough to automate
- ready enough to change

A process can be painful, but not ready for automation. That does not mean it is not worth improving.

---

## 8. Categorise the opportunity

After assessing the opportunity, place it into one of four categories.

| Category | Meaning | Typical next action |
|---|---|---|
| **Automate now** | High value, feasible and ready | Move into automation discovery or design |
| **Improve first** | Worth solving, but process needs tidying | Clarify, simplify, standardise or assign ownership |
| **Investigate further** | Potential value, but more evidence is needed | Gather data or assess technical feasibility |
| **Do not automate yet** | Low value, unstable or unclear | Defer or address underlying process issues |

The category can change as new evidence becomes available.

---

## 9. Use the templates

The workshop templates are designed to be used together.

| Template | Use it to |
|---|---|
| `process-mapping-canvas.md` | Validate how the process works today |
| `metrics-checklist.md` | Identify useful metrics and missing evidence |
| `scenario-clinic-capture.md` | Capture discussion from a scenario clinic or follow-up conversation |
| `automation-opportunity-assessment.md` | Assess value, feasibility and readiness |
| `opportunity-backlog.md` | Track opportunities, categories, owners and next actions |

Suggested order:

```text
process-mapping-canvas.md
        ↓
metrics-checklist.md
        ↓
scenario-clinic-capture.md
        ↓
automation-opportunity-assessment.md
        ↓
opportunity-backlog.md
```

Use only the templates that are useful for the level of detail required.

---

## 10. Questions to ask before moving to automation

Before moving an opportunity into automation discovery or design, ask:

1. Do we understand the current process?
2. Have we validated it with people who do the work?
3. Do we know where the pain is?
4. Do we have evidence, or are we relying on assumptions?
5. Is the process stable enough to automate?
6. Are the rules or decisions clear?
7. Are the inputs and outputs stable?
8. Are the systems and data accessible?
9. Do we know what success would look like?
10. Is the next step automation, improvement or further investigation?

If the answer to several of these is unclear, the opportunity may need improvement or investigation before automation.

---

## 11. Suggested 7-day follow-up actions

Within the first week after the workshop:

- [ ] Select 2–3 candidate processes to take forward.
- [ ] Confirm who owns each candidate process.
- [ ] Validate the current-state process with people who do the work.
- [ ] Capture the normal path, key decisions, handoffs and exceptions.
- [ ] Identify which metrics matter most.
- [ ] Mark known evidence and assumptions separately.
- [ ] Add each candidate to the opportunity backlog.
- [ ] Assign owners for missing evidence or validation actions.

The first week is about keeping momentum and avoiding the workshop from becoming a one-off conversation.

---

## 12. Suggested 30-day follow-up actions

Within 30 days of the workshop:

- [ ] Gather missing metrics or evidence.
- [ ] Confirm whether initial assumptions were accurate.
- [ ] Complete the automation opportunity assessment for priority candidates.
- [ ] Categorise each opportunity as automate now, improve first, investigate further or do not automate yet.
- [ ] Identify any quick wins.
- [ ] Identify any process improvements needed before automation.
- [ ] Identify any opportunities that need a technical feasibility assessment.
- [ ] Review and update the opportunity backlog.
- [ ] Decide whether a follow-up session is needed.

The first 30 days should move the strongest candidates from discussion to an evidence-based decision.

---

## 13. Suggested follow-up session

A follow-up session may be useful once 2–3 candidate processes have been mapped and some evidence has been gathered.

A simple follow-up session can run for 45–60 minutes.

| Time | Focus |
|---:|---|
| 0–5 mins | Recap the method |
| 5–35 mins | Review candidate processes |
| 35–50 mins | Assess value, feasibility and readiness |
| 50–60 mins | Confirm categories and next actions |

The purpose of the follow-up session is to test whether the mapped scenarios are clear enough to proceed with automation discovery, process improvement, or further investigation.

---

## 14. Example next best actions

Use these examples when deciding what should happen next.

| Situation | Possible next best action |
|---|---|
| Process is unclear | Validate with people who do the work |
| Metrics are missing | Gather volume, cycle time, touch time or rework data |
| Ownership is unclear | Confirm process owner |
| Rules are unclear | Clarify policy, approval or decision rules |
| Inputs are inconsistent | Standardise forms, templates or required fields |
| Too many exceptions | Separate standard path from exception handling |
| Technical feasibility is unknown | Assess system access, data structure or integration options |
| Opportunity looks strong | Move into deeper automation discovery |
| Opportunity looks low value | Defer or close |

---

## 15. Final reminder

The workshop was the starting point.

The next step is to turn candidate ideas into evidence-based opportunities.

Keep asking:

1. What is the process?
2. Where is the pain?
3. What evidence do we have?
4. What is the right response?
5. Is it valuable, feasible and ready?
6. What is the next best action?

> **Map the work. Measure the pain. Automate with purpose.**
