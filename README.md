# Product Discovery & Feedback Analytics Automation

---

<details>
<summary><h2>The problem</h2></summary>

<br>

Customer feedback arrives in many forms and describes different issues. This feedback needs to be organized consistently in order to spot recurring problems faster and decide what to prioritize.

I designed a workflow that takes customer feedback from a form, organizes it, and saves the results in a spreadsheet for review.

</details>

---

## What the workflow does

![Screenshot 1](screenshots/n8n.png)

<details>
<summary><b>1. Collects feedback</b></summary>

<br>

- It receives submissions through Google Forms.

</details>

<details>
<summary><b>2. Organizes responses</b></summary>

<br>

- The workflow uses JavaScript rules to assign a category, urgency, estimate, and theme to the feedback received.

</details>

<details>
<summary><b>3. Flags uncertain cases</b></summary>

<br>

- In the case of uncertainty, some of the feedback is marked as "Needs Review" for the product owner/manager to carefully investigate.

</details>

<details>
<summary><b>4. Stores the results</b></summary>

<br>

- The results are saved as structured records in Google Sheets.

</details>

<details>
<summary><b>5. Supports prioritization</b></summary>

<br>

- The structured results make recurring themes easier to review using metrics such as frequency, impact, strategic fit, and confidence.

</details>

---

<details>
<summary><h2>Target Audience</h2></summary>

<br>

This and similar processes can be used by Product Managers and Product Owners or other professionals who regularly deal with incoming feedback.

</details>

---

<details>
<summary><h2>Tools & Project Management</h2></summary>

<br>

<details>
<summary><h3>Tools used</h3></summary>

<br>

| Tool | What it does in this project |
|---|---|
| **Google Forms** | Collects feedback |
| **n8n** | Connects and automates the steps |
| **JavaScript rules** | Categorizes feedback and assigns themes |
| **Google Sheets** | Stores and reviews results |

<br>

</details>

<details>
<summary><h3>Project Management</h3></summary>

<br>

Here is the Trello dashboard used to add and track tasks, along with workflow documentation.

![Screenshot 2](screenshots/trello_1.png)

---

![Screenshot 3](screenshots/trello_2.png)

</details>

</details>

---

<details>
<summary><h2>How prioritization works</h2></summary>

<br>

This workflow is rule-based and only organizes the evidence. The decision on the roadmap is left to professionals.

The prioritization framework helps explore four questions:

- **Frequency:** How often does this problem appear?
- **Impact:** How much does it affect users?
- **Strategic fit:** Does solving it support product goals?
- **Confidence:** How strong is the evidence?

The scoring weights are working assumptions for this prototype. A Product Manager still reviews the context and makes the decision.

</details>

---

<details>
<summary><h2>Testing and limitations</h2></summary>

<br>

I improved the matching rules after identifying gaps. Validation is done through a small set of test examples.

![Screenshot 4](screenshots/QA.png)

This is a rule-based prototype, not a fully AI-powered or production-ready system. The rules may miss context, misunderstand wording, or assign the wrong theme. Human review remains important.

</details>

---

<details>
<summary><h2>About this project</h2></summary>

<br>

This project demonstrates how I approach a product problem, build a practical workflow, improve it through testing, and use structured evidence to support product decisions.

</details>
