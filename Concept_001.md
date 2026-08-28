# **Lean thinking** in quality management. 

## 1. What is Lean?

**Lean is an approach that focuses on delivering maximum value to the customer while minimizing waste.**

In simple terms:

> **Do more useful work, with less unnecessary work, time, effort, and resources.**

Imagine a process like this:

**Customer request → Development → Testing → Approval → Release**

Lean asks:

> "Which activities actually help deliver value to the customer, and which activities are just wasting time?"

---

## 2. Value-Added vs Non-Value-Added Activities

Let's take a simple example: **Testing a feature**.

### Value-Added Activity

An activity is value-added if it directly contributes to what the customer needs.

Examples:

* Testing whether the login feature works correctly.
* Finding a critical defect before release.
* Developing the requested feature.

These activities contribute to the product's quality or functionality.

### Non-Value-Added Activity

These are activities that consume time or effort but **do not directly add value**.

Examples:

* Waiting 3 days for someone to review a test case.
* Testing the same thing repeatedly because requirements are unclear.
* Manually entering the same data into three different tools.
* Fixing defects caused by incorrect communication.
* Creating unnecessary reports that nobody reads.

Lean tries to **reduce or eliminate these activities**.

---

## 3. What are the "Eight Types of Waste"?

Lean identifies common types of waste in a process. A popular way to remember them is **DOWNTIME**.

| Waste                       | Meaning                                   | QA / Software Example                                                    |
| --------------------------- | ----------------------------------------- | ------------------------------------------------------------------------ |
| **D – Defects**             | Errors that require rework                | Bug found late, requiring development and retesting                      |
| **O – Overproduction**      | Doing more than needed                    | Writing 500 detailed test cases when 100 would be sufficient             |
| **W – Waiting**             | Idle time                                 | Tester waiting for a build or environment                                |
| **N – Non-utilized talent** | Not using people's skills                 | Experienced QA only doing repetitive data entry                          |
| **T – Transportation**      | Unnecessary movement of items/information | Moving the same information between Jira, Excel, email, and another tool |
| **I – Inventory**           | Work waiting to be processed              | 200 untested stories accumulating in the backlog                         |
| **M – Motion**              | Unnecessary movement by people            | Constantly switching between multiple systems to perform one task        |
| **E – Extra-processing**    | Doing unnecessary work                    | Creating documentation or reports nobody uses                            |

---

### A simple way to understand it

Suppose a tester's work looks like this:

> Receive requirement → wait for clarification → write test cases → send Excel → manager asks for different format → rewrite → wait for environment → test → manually copy results into Jira and another report.

Lean would look at this process and ask:

* Why are we waiting for clarification?
* Why are we rewriting information?
* Why are we entering the same information twice?
* Can some of this be automated?
* Can unnecessary approval steps be removed?

The goal is **not to make people work harder or faster**.

The goal is to improve the **process** by removing unnecessary activities.

### In one sentence:

> **Lean = Identify what creates value for the customer and eliminate or reduce everything that doesn't.**

For you as a QA/Test professional, Lean can be very useful because you can start looking at the **testing process itself** and ask: *"Are we doing this activity because it genuinely helps us find important problems, or are we doing it simply because this is how we have always worked?"*
