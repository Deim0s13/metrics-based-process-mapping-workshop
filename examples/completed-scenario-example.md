# Completed Scenario Example: Weekly Operational Status Report

This example shows a completed scenario using the Metrics Based Process Mapping approach.

It is intended to demonstrate how a team might capture a process, add lightweight metrics, assess the automation opportunity, and decide the next best action.

The scenario and numbers are illustrative only. Replace them with real information when using this method in an organisation.

> **Map the work. Measure the pain. Automate with purpose.**

---

## 1. Scenario overview

### Process name

Weekly operational status report

### Short description

Each week, an operations team produces a status report for senior stakeholders. The report summarises current work volumes, open issues, overdue actions, risks, upcoming milestones and commentary from several teams.

The current process relies on manual data collection, spreadsheet updates, copy-and-paste reporting, email follow-ups and manual formatting.

### Why this process was selected

This process was selected because it is:

* repeated every week
* manual and time-consuming
* dependent on multiple contributors
* affected by late or inconsistent input
* spreadsheet-heavy
* difficult to validate quickly
* highly visible to stakeholders
* a regular source of frustration for the report owner

---

## 2. Current process summary

### Trigger

The weekly report cycle begins every Monday morning when the report owner starts collecting inputs for the Friday status report.

### Desired outcome

A complete, accurate and consistent status report is distributed to stakeholders by midday Friday.

### Primary users / stakeholders

| Role                       | Involvement                                                                             |
| -------------------------- | --------------------------------------------------------------------------------------- |
| Report owner               | Coordinates the process, gathers inputs, updates the report and sends the final version |
| Team leads                 | Provide updates, commentary, risks and milestones                                       |
| Operations analysts        | Provide data extracts and status information                                            |
| Senior stakeholders        | Receive and use the final report                                                        |
| Programme / delivery teams | May be asked to clarify actions, risks or milestone status                              |

### Systems, tools and channels used

* email
* shared spreadsheet
* reporting dashboard
* service management system
* project tracking tool
* document template
* presentation or PDF export
* chat messages for follow-up

---

## 3. Current process map

```text
Monday: Report owner starts weekly report cycle
        ↓
Report owner sends reminder to contributors
        ↓
Team leads and analysts gather updates
        ↓
Inputs received by report owner
        ↓
Are inputs complete?
        ↓
   ┌───────────────┐
   │               │
  No              Yes
   │               │
   ↓               ↓
Follow up with     Report owner updates spreadsheet
missing teams             ↓
   │                Pull latest dashboard data
   │                       ↓
   └──────────────→ Compare data with team inputs
                           ↓
                    Are inconsistencies found?
                           ↓
                    ┌───────────────┐
                    │               │
                   Yes              No
                    │               │
                    ↓               ↓
              Clarify with teams     Draft report narrative
                    │               ↓
                    └────────────→ Format final report
                                    ↓
                             Send for review
                                    ↓
                             Final changes made
                                    ↓
                             Report distributed
```

---

## 4. Process mapping canvas

| Element             | Notes                                                                                                                                              |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Process name**    | Weekly operational status report                                                                                                                   |
| **Trigger**         | Weekly reporting cycle starts every Monday morning                                                                                                 |
| **Outcome**         | Accurate report distributed by midday Friday                                                                                                       |
| **Main steps**      | Send reminder; gather updates; update spreadsheet; pull dashboard data; check inconsistencies; draft commentary; format report; review; distribute |
| **Roles involved**  | Report owner, team leads, analysts, senior stakeholders, delivery teams                                                                            |
| **Systems used**    | Email, spreadsheet, dashboard, service management system, project tracking tool, report template, chat                                             |
| **Decision points** | Are inputs complete? Are inconsistencies found? Is report approved for distribution?                                                               |
| **Handoffs**        | Report owner to contributors; contributors to report owner; report owner to reviewers; reviewers back to report owner                              |
| **Exceptions**      | Late inputs, missing commentary, conflicting data, dashboard not updated, urgent issue added late, report owner unavailable                        |

---

## 5. Pain points and evidence

| Step                       | Pain point                                       | Example metric / evidence                | Impact                               |
| -------------------------- | ------------------------------------------------ | ---------------------------------------- | ------------------------------------ |
| Reminder sent              | Contributors rely on manual email reminders      | 1–2 reminder emails per team each week   | Repeated coordination effort         |
| Updates gathered           | Inputs arrive in different formats               | 6–8 contributors, inconsistent templates | Manual consolidation and rework      |
| Missing inputs followed up | Late or missing updates are common               | 30–40% of contributors need follow-up    | Delay and status chasing             |
| Spreadsheet updated        | Report owner manually copies and formats data    | 60–90 minutes each week                  | Repetitive manual effort             |
| Dashboard data pulled      | Data is available but not integrated into report | 3–4 data sources checked manually        | Risk of mismatch or outdated figures |
| Inconsistencies checked    | Conflicting numbers need clarification           | 2–3 inconsistencies per week             | Rework and delay                     |
| Narrative drafted          | Commentary is manually rewritten                 | 45–60 minutes each week                  | Effort and inconsistency in tone     |
| Report reviewed            | Review happens late in the cycle                 | 1–2 day wait time                        | Final report often rushed            |
| Final report distributed   | Distribution list and version control are manual | Occasional wrong version or late send    | Stakeholder confidence risk          |

---

## 6. Metrics view

### Effort

| Metric            |   Example estimate | Notes                                                             |
| ----------------- | -----------------: | ----------------------------------------------------------------- |
| **Volume**        |  1 report per week | 52 reporting cycles per year                                      |
| **Touch time**    | 3–5 hours per week | Mainly coordination, consolidation, checking and formatting       |
| **Manual effort** |               High | Copying data, chasing inputs, formatting and rewriting commentary |

### Flow

| Metric           |       Example estimate | Notes                                                                                    |
| ---------------- | ---------------------: | ---------------------------------------------------------------------------------------- |
| **Cycle time**   |      4–5 business days | Monday start to Friday distribution                                                      |
| **Wait time**    |      1–2 business days | Waiting for updates, clarification and review                                            |
| **Handoffs**     |        10–15 per cycle | Multiple contributors, reviewers and clarification loops                                 |
| **Systems used** | 6–8 systems / channels | Email, spreadsheet, dashboard, service management, project tool, document template, chat |

### Quality and risk

| Metric              |         Example estimate | Notes                                                                        |
| ------------------- | -----------------------: | ---------------------------------------------------------------------------- |
| **Rework / errors** | 2–3 corrections per week | Mostly inconsistent data or missing commentary                               |
| **Exceptions**      |  30–40% of weekly cycles | Late inputs, urgent issues, missing data or dashboard mismatch               |
| **Risk impact**     |                   Medium | Inaccurate reporting may affect stakeholder decisions                        |
| **User impact**     |           Medium to high | Report owner frustration; stakeholders may lose confidence in report quality |

---

## 7. What the evidence suggests

### Key observations

1. **The process is regular and repeated.**
   The weekly cadence creates a strong case for improving the process because effort accumulates over time.

2. **The main pain is not one task.**
   The pain comes from coordination, inconsistent inputs, manual consolidation, checking and review delay.

3. **Some data is already available digitally.**
   Dashboard and system data may not need to be manually copied if reporting integration or export automation is possible.

4. **Input standardisation is needed before full automation.**
   Team updates arrive in inconsistent formats, which increases manual rework and makes automation harder.

5. **There are likely quick wins around reminders and status visibility.**
   Automated reminders, due dates and submission tracking could reduce chasing.

6. **Full report automation may not be ready yet.**
   Commentary, interpretation and risk narrative still require human judgement.

---

## 8. Pain point to possible response

| Pain point          | Likely response                    | Notes                                                          |
| ------------------- | ---------------------------------- | -------------------------------------------------------------- |
| Manual reminders    | Automate now                       | Schedule reminders and due date notifications                  |
| Inconsistent inputs | Improve first                      | Standard input template or form required                       |
| Manual data copying | Investigate further                | Assess whether dashboard or system exports can feed the report |
| Missing updates     | Improve / automate                 | Use workflow tracking and submission status visibility         |
| Conflicting data    | Improve first                      | Clarify source of truth for key metrics                        |
| Manual formatting   | Automate now / investigate further | Template automation or document generation may help            |
| Narrative rewriting | Improve first                      | Standard commentary prompts may reduce rewriting               |
| Late review         | Improve first                      | Agree earlier review checkpoint or escalation path             |

---

## 9. Automation opportunity assessment

### Value

| Question               | Assessment                                                                        |
| ---------------------- | --------------------------------------------------------------------------------- |
| Is this worth solving? | Yes                                                                               |
| Why?                   | The process is repeated weekly and consumes several hours of effort each cycle    |
| Main value drivers     | Reduced coordination effort, fewer errors, faster reporting, improved consistency |
| Value level            | High                                                                              |

### Feasibility

| Question                 | Assessment                                                                                                             |
| ------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| Can this be automated?   | Partially                                                                                                              |
| Why?                     | Reminders, tracking, data exports and formatting may be feasible; narrative and judgement-heavy parts need human input |
| Main feasibility factors | Availability of structured inputs, dashboard access, export options, report template, workflow tooling                 |
| Feasibility level        | Medium                                                                                                                 |

### Readiness

| Question               | Assessment                                                                                      |
| ---------------------- | ----------------------------------------------------------------------------------------------- |
| Is the process ready?  | Partially                                                                                       |
| Why?                   | The cycle is stable, but inputs, ownership of data sources and review timing need clarification |
| Main readiness factors | Standard input format, agreed source of truth, contributor accountability, review deadlines     |
| Readiness level        | Medium                                                                                          |

---

## 10. Initial category

### Recommended category

**Improve first / Automate selected steps**

### Why

The process has clear value because it is repeated weekly and creates regular manual effort. However, the whole process is not ready for end-to-end automation.

Some steps are good candidates for immediate automation or workflow improvement, while others need standardisation or clarification first.

### Summary judgement

| Area                  | Assessment                                             |
| --------------------- | ------------------------------------------------------ |
| Overall value         | High                                                   |
| Technical feasibility | Medium                                                 |
| Process readiness     | Medium                                                 |
| Recommended approach  | Improve first, then automate selected repeatable steps |

---

## 11. Candidate opportunities

| Opportunity                                | Type                  | Category            | Notes                                            |
| ------------------------------------------ | --------------------- | ------------------- | ------------------------------------------------ |
| Automated weekly reminders                 | Workflow automation   | Automate now        | Simple, low-risk, reduces chasing                |
| Standard input form or template            | Process improvement   | Improve first       | Needed before further automation                 |
| Submission tracker                         | Workflow / visibility | Automate now        | Shows who has submitted and who is overdue       |
| Dashboard data export into reporting sheet | Data automation       | Investigate further | Depends on system access and data structure      |
| Automated report formatting                | Document automation   | Investigate further | May reduce repetitive formatting effort          |
| Standard commentary prompts                | Process improvement   | Improve first       | Reduces rewriting and improves consistency       |
| Earlier review checkpoint                  | Process improvement   | Improve first       | Reduces last-minute changes and delay            |
| Final distribution automation              | Workflow automation   | Automate now        | Helps manage version control and delivery timing |

---

## 12. Recommended next best action

### Next best action

Standardise the weekly input process and automate simple workflow steps before attempting broader report automation.

### Follow-up actions

| Action                                         | Owner     | Notes                                                      |
| ---------------------------------------------- | --------- | ---------------------------------------------------------- |
| Confirm report owner and process owner         | `[OWNER]` | Ownership is required before redesigning the process       |
| Define standard input template or form         | `[OWNER]` | Include status, risks, milestones, blockers and commentary |
| Identify source of truth for each metric       | `[OWNER]` | Avoid conflicting data sources                             |
| Measure current report effort over 4 weeks     | `[OWNER]` | Capture actual touch time and wait time                    |
| Track missing or late submissions for 4 cycles | `[OWNER]` | Validate follow-up and rework assumptions                  |
| Assess dashboard export options                | `[OWNER]` | Technical feasibility check                                |
| Create simple submission tracker               | `[OWNER]` | Quick win for visibility                                   |
| Test automated reminders                       | `[OWNER]` | Low-risk automation candidate                              |

---

## 13. Suggested future-state concept

This is not a final design, but a possible direction based on the assessment.

```text
Weekly cycle starts automatically
        ↓
Automated reminder sent to contributors
        ↓
Contributors submit updates through standard form
        ↓
Submission tracker updates automatically
        ↓
Dashboard data imported or linked
        ↓
Report owner reviews exceptions and commentary
        ↓
Draft report generated from template
        ↓
Reviewer approves or requests changes
        ↓
Final report distributed automatically
```

### What remains human-led

* interpreting risks and issues
* writing or approving sensitive commentary
* resolving conflicting information
* deciding escalation actions
* confirming final stakeholder messaging

### What could be automated or improved

* reminders
* input collection
* submission tracking
* data import or export
* formatting
* version control
* distribution

---

## 14. What this example teaches

This example shows that a process can be a strong improvement candidate even when full automation is not the right first step.

Without mapping and metrics, the opportunity might be described too broadly as:

> “Automate the weekly report.”

After mapping the process and adding evidence, the opportunity becomes more specific:

* standardise inputs
* clarify source of truth
* automate reminders
* track submissions
* reduce manual data copying
* investigate report generation
* keep judgement-heavy commentary human-led

The better conclusion is not “automate the whole report”.

The better conclusion is:

> Standardise the process first, automate the repeatable workflow steps, and investigate data integration and report generation separately.

---

## 15. Example summary

| Area                        | Summary                                                                                      |
| --------------------------- | -------------------------------------------------------------------------------------------- |
| **Process**                 | Weekly operational status report                                                             |
| **Main pain**               | Manual coordination, inconsistent inputs, data copying, late review, rework                  |
| **Main evidence**           | 3–5 hours weekly touch time, 4–5 day cycle time, 10–15 handoffs, 2–3 corrections per week    |
| **Strongest opportunities** | Automated reminders, standard input form, submission tracker, data export, report formatting |
| **Primary category**        | Improve first / automate selected steps                                                      |
| **Next best action**        | Standardise inputs and validate effort, delay and rework metrics over four cycles            |

---

## 16. Completed scenario capture

| Question                                                       | Response                                                                                               |
| -------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| What process are we discussing?                                | Weekly operational status report                                                                       |
| Where does it start?                                           | Monday morning report cycle begins                                                                     |
| Where does it end?                                             | Final report distributed to stakeholders by Friday midday                                              |
| Who is involved?                                               | Report owner, team leads, analysts, reviewers, senior stakeholders                                     |
| What systems are used?                                         | Email, spreadsheet, dashboard, service management system, project tool, document template, chat        |
| Where is the pain?                                             | Chasing updates, inconsistent inputs, manual copying, checking, formatting, late review                |
| Is the pain mainly effort, flow, quality, risk or user impact? | Effort and flow, with some quality and stakeholder confidence risk                                     |
| What evidence do we have?                                      | Estimated 3–5 hours weekly effort, 4–5 day cycle, 30–40% late/missing inputs, 2–3 corrections per week |
| What are we assuming?                                          | That reminder automation and standard templates will reduce chasing and rework                         |
| What evidence is missing?                                      | Actual effort over several cycles, late submission rate, source-of-truth gaps, feasibility of exports  |
| Is the likely response automation, improvement or both?        | Both — improve inputs and automate repeatable workflow steps                                           |
| What needs to be clarified?                                    | Process owner, input standard, source of truth, review deadlines, export options                       |
| What is the next best action?                                  | Standardise input collection and validate current metrics over four reporting cycles                   |
| Who needs to be involved next?                                 | Report owner, contributors, data owners, dashboard/reporting support, reviewers                        |

---

## 17. Reusable lesson

When applying this method to other processes, avoid asking only:

> Can this be automated?

Ask instead:

1. What is the process?
2. Where is the pain?
3. What evidence do we have?
4. What is the right response?
5. Is it valuable, feasible and ready?
6. What is the next best action?

> **Map the work. Measure the pain. Automate with purpose.**
