# Example: New Starter Access Request

This example shows how Metrics Based Process Mapping can be applied to a common access request process.

It is intended as a simple worked example for facilitators and participants. The numbers are illustrative only and should be replaced with real data when applying the method in an organisation.

> **Map the work. Measure the pain. Automate with purpose.**

---

## 1. Scenario overview

### Process name

New starter access request

### Short description

When a new employee joins the organisation, their manager requests access to the systems, applications and shared folders the employee needs for their role.

The current process relies on email, manual approval, manual provisioning and follow-up messages between the manager, approver and IT support team.

### Why this process was selected

This process was selected because it is:

* repeated regularly
* time-sensitive
* manual in several places
* dependent on multiple teams
* affected by incomplete information
* visible to new employees and hiring managers
* likely to create poor experience when delayed

---

## 2. Current process summary

### Trigger

A manager needs access provisioned for a new starter before or shortly after their start date.

### Desired outcome

The new starter has the correct access required for their role by their first day, or as soon as practicable after joining.

### Primary users / stakeholders

| Role                      | Involvement                                                        |
| ------------------------- | ------------------------------------------------------------------ |
| Hiring manager            | Submits the access request and confirms what the new starter needs |
| Approver / team lead      | Reviews and approves the request where required                    |
| IT support / service desk | Provisions access or routes the request to the right team          |
| Application owner         | Approves or provisions access for specific systems                 |
| New starter               | Receives access and is able to begin work                          |

### Systems, tools and channels used

* email
* access request form
* service desk ticketing system
* identity / access management system
* application admin consoles
* spreadsheets or shared trackers
* chat or messaging tools for follow-up

---

## 3. Current process map

This is a simplified view of the current process.

```text
Manager identifies access need
        ↓
Manager submits access request
        ↓
Request checked for completeness
        ↓
Is information complete?
        ↓
   ┌───────────────┐
   │               │
  No              Yes
   │               │
   ↓               ↓
Request returned   Approval required?
for clarification        ↓
   │               ┌───────────────┐
   │               │               │
   ↓              Yes              No
Manager updates    │               │
request            ↓               ↓
   │          Approver reviews   IT provisions
   └───────────────┐ request      standard access
                   ↓               ↓
             Approved?             Access confirmed
                   ↓               ↓
             ┌───────────────┐     New starter notified
             │               │
            No              Yes
             │               │
             ↓               ↓
          Request       IT provisions
          declined      access
                         ↓
                  Access confirmed
                         ↓
                  New starter notified
```

---

## 4. Process mapping canvas

| Element             | Notes                                                                                                           |
| ------------------- | --------------------------------------------------------------------------------------------------------------- |
| **Process name**    | New starter access request                                                                                      |
| **Trigger**         | A new employee is due to start and needs access to systems and folders                                          |
| **Outcome**         | New starter has the correct access for their role                                                               |
| **Main steps**      | Manager submits request; request checked; approval obtained; IT provisions access; user notified                |
| **Roles involved**  | Manager, approver, IT support, application owner, new starter                                                   |
| **Systems used**    | Email, access form, service desk, identity system, application consoles, spreadsheets                           |
| **Decision points** | Is information complete? Is approval required? Is access approved?                                              |
| **Handoffs**        | Manager to approver; approver to IT; IT to application owner; IT to new starter                                 |
| **Exceptions**      | Missing information, unclear role requirements, approval delay, application-specific access, duplicate requests |

---

## 5. Pain points and evidence

The table below adds lightweight evidence to the process.

| Step                        | Pain point                               | Example metric / evidence                       | Impact                                            |
| --------------------------- | ---------------------------------------- | ----------------------------------------------- | ------------------------------------------------- |
| Manager submits request     | Requests often miss required information | Estimated 30% of requests require clarification | Rework for manager and IT; delays for new starter |
| Request checked             | Completeness check is manual             | 5–10 minutes per request                        | Repeated low-value effort                         |
| Approval required           | Approval often waits in email            | 1–2 day average approval delay                  | Access not ready on time                          |
| IT provisions access        | Standard access is manually provisioned  | 20 minutes touch time per request               | Manual effort and inconsistent handling           |
| Application-specific access | Different systems have different rules   | Exceptions in 20–25% of requests                | Harder to automate end to end                     |
| User notified               | Notifications are manual or inconsistent | Some users chase status updates                 | Poor visibility and avoidable follow-up           |
| Access reviewed later       | No consistent post-start review          | Review often missed or delayed                  | Risk of over-provisioning or incorrect access     |

---

## 6. Metrics view

### Effort

| Metric            |                   Example estimate | Notes                                            |
| ----------------- | ---------------------------------: | ------------------------------------------------ |
| **Volume**        |              40 requests per month | Includes new starters and internal movers        |
| **Touch time**    | 25–35 minutes per standard request | Includes checking, provisioning and notification |
| **Manual effort** |                     Medium to high | Manual checking, provisioning and chasing        |

### Flow

| Metric           |       Example estimate | Notes                                                                       |
| ---------------- | ---------------------: | --------------------------------------------------------------------------- |
| **Cycle time**   |      2–5 business days | End-to-end from request to access confirmation                              |
| **Wait time**    |      1–3 business days | Mostly waiting for approval or clarification                                |
| **Handoffs**     |           3–5 handoffs | Manager, approver, IT, application owner, user                              |
| **Systems used** | 5–7 systems / channels | Email, form, ticketing, identity system, application consoles, spreadsheets |

### Quality and risk

| Metric              |          Example estimate | Notes                                                   |
| ------------------- | ------------------------: | ------------------------------------------------------- |
| **Rework / errors** | 30% require clarification | Mostly missing or unclear information                   |
| **Exceptions**      |                    20–25% | Application-specific access or non-standard role needs  |
| **Risk impact**     |                    Medium | Incorrect access can create security or compliance risk |
| **User impact**     |                      High | Delays affect new starter experience and productivity   |

---

## 7. What the evidence suggests

The process has several automation opportunities, but not all pain points should be treated the same way.

### Key observations

1. **Missing information is a major cause of rework.**
   This suggests improving the intake form and validation rules before or alongside automation.

2. **A lot of the delay is wait time, not touch time.**
   This suggests workflow routing, reminders and approval visibility may create value.

3. **Standard access may be a good automation candidate.**
   Repetitive, rules-based provisioning for common roles could be automated.

4. **Application-specific access may need further analysis.**
   Exceptions and different approval rules may make full automation harder.

5. **Notifications and status updates are likely quick wins.**
   Automated confirmation, status updates and reminders could reduce chasing.

6. **Access review may need governance clarification.**
   Scheduled review workflows may help, but ownership and policy rules need to be clear.

---

## 8. Pain point to possible response

| Pain point                            | Likely response                     | Notes                                                                 |
| ------------------------------------- | ----------------------------------- | --------------------------------------------------------------------- |
| Missing request information           | Improve first                       | Add mandatory fields, guidance, validation and role-based options     |
| Approval delays                       | Automate / improve                  | Workflow routing, reminders and escalation rules                      |
| Manual standard provisioning          | Automate now or investigate further | Strong candidate if access rules are clear and systems are accessible |
| Application-specific exceptions       | Investigate further                 | Needs deeper analysis of rules, systems and approval paths            |
| Manual status updates                 | Automate now                        | Automated notifications or dashboard likely feasible                  |
| Inconsistent post-start access review | Improve first                       | Clarify ownership, timing and review policy before automating         |

---

## 9. Automation opportunity assessment

### Value

| Question               | Assessment                                                                               |
| ---------------------- | ---------------------------------------------------------------------------------------- |
| Is this worth solving? | Yes                                                                                      |
| Why?                   | Reduces delay, manual effort, rework and poor new starter experience                     |
| Main value drivers     | Faster access, fewer clarification loops, reduced manual provisioning, better visibility |
| Value level            | High                                                                                     |

### Feasibility

| Question                 | Assessment                                                                                 |
| ------------------------ | ------------------------------------------------------------------------------------------ |
| Can this be automated?   | Partially                                                                                  |
| Why?                     | Standard access and notifications appear feasible; exceptions need more analysis           |
| Main feasibility factors | System access, clear rules, identity system integration, form validation, workflow routing |
| Feasibility level        | Medium                                                                                     |

### Readiness

| Question               | Assessment                                                                                            |
| ---------------------- | ----------------------------------------------------------------------------------------------------- |
| Is the process ready?  | Partially                                                                                             |
| Why?                   | Standard path is understood, but request quality, ownership and exception handling need clarification |
| Main readiness factors | Process owner, approval rules, role-based access patterns, access review policy                       |
| Readiness level        | Medium                                                                                                |

---

## 10. Initial category

### Recommended category

**Improve first / Investigate further**

### Why

This process has clear value and several promising automation opportunities, but the full process is not ready to automate end to end.

The strongest near-term opportunities are:

* improve the intake form
* add validation and guidance
* automate approval routing and reminders
* automate status notifications
* investigate standard access provisioning for common roles

The process should not be treated as one large automation initiative without separating the standard path from exceptions.

---

## 11. Candidate automation opportunities

| Opportunity                                             | Type                                     | Category                           | Notes                                          |
| ------------------------------------------------------- | ---------------------------------------- | ---------------------------------- | ---------------------------------------------- |
| Improve request form with mandatory fields and guidance | Process improvement                      | Improve first                      | Reduces missing information and rework         |
| Add role-based access options                           | Process improvement / automation enabler | Improve first                      | Makes standard access easier to automate later |
| Route approvals automatically                           | Workflow automation                      | Automate now / investigate further | Depends on approval rules and tooling          |
| Send approval reminders                                 | Workflow automation                      | Automate now                       | Likely quick win                               |
| Send status notifications                               | Workflow automation                      | Automate now                       | Reduces chasing and improves visibility        |
| Provision standard access for common roles              | System automation                        | Investigate further                | Requires clear rules and system integration    |
| Schedule post-start access review                       | Workflow / governance                    | Improve first                      | Needs clear ownership and review policy        |

---

## 12. Recommended next best action

### Next best action

Map the standard access request path in more detail and validate the metrics with the people who do the work.

### Follow-up actions

| Action                                                               | Owner     | Notes                                      |
| -------------------------------------------------------------------- | --------- | ------------------------------------------ |
| Validate current process map with manager, approver and IT support   | `[OWNER]` | Confirm normal path and common exceptions  |
| Gather actual volume for last 3 months                               | `[OWNER]` | Include new starters and internal movers   |
| Measure average cycle time and wait time                             | `[OWNER]` | Use ticketing or request data if available |
| Review incomplete request rate                                       | `[OWNER]` | Check how often clarification is required  |
| Identify top 5 standard access patterns                              | `[OWNER]` | Helps test role-based automation potential |
| Confirm approval rules and process owner                             | `[OWNER]` | Required before automation design          |
| Identify systems that can support integration or workflow automation | `[OWNER]` | Technical feasibility assessment           |

---

## 13. What this example teaches

This example shows why Metrics Based Process Mapping is useful.

Without mapping and metrics, the opportunity might be described too broadly as:

> “Automate new starter access.”

After mapping the process and adding evidence, the opportunity becomes more specific:

* improve the request intake
* reduce missing information
* automate approval reminders
* improve status visibility
* investigate standard access provisioning
* clarify governance for access reviews

The more useful conclusion is not “automate everything”.

The more useful conclusion is:

> Improve the process first, automate the standard and repetitive parts, and investigate the more complex exceptions separately.

---

## 14. Example summary

| Area                        | Summary                                                                                    |
| --------------------------- | ------------------------------------------------------------------------------------------ |
| **Process**                 | New starter access request                                                                 |
| **Main pain**               | Missing information, approval delay, manual provisioning, poor visibility                  |
| **Main evidence**           | 30% clarification rate, 2–5 day cycle time, 25–35 minutes touch time, 3–5 handoffs         |
| **Strongest opportunities** | Intake improvement, approval reminders, status notifications, standard access provisioning |
| **Primary category**        | Improve first / investigate further                                                        |
| **Next best action**        | Validate the standard process path and gather actual metrics                               |

---

## 15. Reusable lesson

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
