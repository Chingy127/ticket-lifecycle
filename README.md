<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket – Ticket Lifecycle Demonstration</h1>

This section demonstrates how a support request moves through the **complete lifecycle of a help desk ticket inside osTicket**.

In real IT environments, help desk systems are used to organize, prioritize, and track technical issues reported by users.  
Each ticket follows a structured workflow that ensures problems are investigated, assigned to the appropriate team, and resolved efficiently.

This lab demonstrates how tickets move through that workflow by simulating **two real-world IT support scenarios**.

---

<h2>Scenario Overview</h2>

Two different support scenarios are demonstrated in this section:

<b>Scenario 1 – Critical System Outage</b>  
A banking system outage is reported. Because the issue affects an entire service, the ticket requires escalation to system administrators and is treated as a high-priority emergency.

<b>Scenario 2 – Software Issue</b>  
Employees report that Adobe Reader is not working in the accounting department. This issue can be resolved by a support agent without requiring escalation.

Both scenarios demonstrate how tickets move through the following lifecycle stages:

- Ticket Submission
- Ticket Creation
- Ticket Assignment
- Investigation and Troubleshooting
- Escalation (if necessary)
- Resolution
- Ticket Closure

---

<h2>Scenario 1 – Critical System Outage (Banking System Down)</h2>

<h3>Step 1 – User Submits a Support Ticket</h3>

<p>
<img width="1399" height="756" alt="Screenshot 2026-03-07 at 3 37 37 PM" src="https://github.com/user-attachments/assets/10181315-3451-4310-8448-b5fde20d4ad0" />
</p>

The ticket lifecycle begins when a user submits a support request through the **osTicket help desk portal**.

To simulate this scenario:

1. Log in to the **osTicket user portal**
2. Select **Open a New Ticket**
3. Enter a description of the issue.

Example issue submitted:

"The entire mobile and online banking system is currently down and customers cannot access their accounts."

Because this issue affects an entire financial service, it must be treated as a **critical system outage**.

---

<h3>Step 2 – Ticket is Created in the System</h3>

<p>
<img width="1440" height="819" alt="Screenshot 2026-03-07 at 3 46 17 PM" src="https://github.com/user-attachments/assets/917f6dc1-27e7-4d29-90d4-b2cb5c600ce7" />
</p>

After the request is submitted, osTicket automatically generates a ticket in the help desk system.

The ticket now includes important information such as:

- The issue description
- The user who submitted the request
- The time the ticket was created
- The current ticket status

Support staff can now begin reviewing the issue.

---

<h3>Step 3 – Ticket is Assigned to a Support Agent</h3>

<p>
<img width="1440" height="820" alt="Screenshot 2026-03-07 at 3 56 52 PM" src="https://github.com/user-attachments/assets/394a58fe-7040-428d-a205-bbc45755a913" />
</p>

Next, a support manager assigns the ticket to a support agent.

To assign the ticket:

1. Open the ticket inside the **Agent Panel**
2. Select **Assign**
3. Choose the appropriate support agent.

This agent will now begin investigating the issue.

---

<h3>Step 4 – Update Agent Permissions if Necessary</h3>

<p>
<img width="1440" height="827" alt="Screenshot 2026-03-07 at 3 58 39 PM" src="https://github.com/user-attachments/assets/0fb5f197-0024-44bd-9ba1-d8b2adbe5aac" />
</p>

If the assigned support agent requires additional system access, their permissions may be adjusted.

Examples include:

- Administrative privileges
- Access to server logs
- Access to monitoring tools

Providing the correct access ensures the agent can properly investigate the issue.

---

<h3>Step 5 – Set Ticket Priority and SLA</h3>

<p>
<img width="1440" height="577" alt="Screenshot 2026-03-07 at 4 04 14 PM" src="https://github.com/user-attachments/assets/afa58109-12d2-4b0f-9dd5-bace3c5aa83a" />
</p>

Because the banking system is down, the ticket must be marked as **high priority**.

To update the priority:

1. Open the ticket settings
2. Select the **Priority level**
3. Assign a **high severity SLA plan (Sev-A)**

This ensures the issue receives immediate attention from the support team.

---

<h3>Step 6 – Agents Document Troubleshooting Steps</h3>

<p>
<img width="1438" height="774" alt="Screenshot 2026-03-07 at 4 04 55 PM" src="https://github.com/user-attachments/assets/bf5ee028-b56b-4808-a7a4-0ff044f39a72" />
</p>

Agents communicate and document their actions inside the ticket thread.

Examples of notes added to the ticket include:

- Initial troubleshooting performed
- Possible causes of the outage
- Updates for other support staff

Maintaining documentation helps keep all team members informed.

---

<h3>Step 7 – Escalate the Ticket to System Administrators</h3>

<p>
<img width="1440" height="758" alt="Screenshot 2026-03-07 at 4 09 35 PM" src="https://github.com/user-attachments/assets/ecc65174-d7fd-4980-9006-e55d445cd94b" />
</p>

If the support agent cannot resolve the issue, the ticket is escalated.

To escalate the ticket:

1. Change the **department assignment**
2. Assign the ticket to the **System Administrators department**

Escalation ensures that higher-level specialists investigate the issue.

---

<h3>Step 8 – System Administrator Investigates the Issue</h3>

<p>
<img width="1440" height="492" alt="Screenshot 2026-03-07 at 4 17 40 PM" src="https://github.com/user-attachments/assets/d21d2d70-b993-4fe7-ae99-083ab2ebccd6" />
</p>

A system administrator reviews the ticket and begins diagnosing the problem.

In this scenario, the administrator discovers that the **online banking backend server has a configuration issue**.

---

<h3>Step 9 – Administrator Resolves the Issue</h3>

<p>
<img width="1440" height="501" alt="Screenshot 2026-03-07 at 4 19 25 PM" src="https://github.com/user-attachments/assets/94987e15-a4fd-4590-a37c-3a3418823aea" />
</p>

The system administrator restarts the backend server and verifies that the banking system is operational again.

The resolution steps are documented inside the ticket.

---

<h3>Step 10 – Ticket is Closed</h3>

<p>
<img width="1440" height="438" alt="Screenshot 2026-03-07 at 4 20 57 PM" src="https://github.com/user-attachments/assets/aad2bcde-4027-489d-954f-31f11f7f655f" />
</p>

After confirming that the system is working correctly:

1. The support agent verifies the fix
2. The user confirms service restoration
3. The ticket status is changed to **Closed**

This marks the issue as resolved.

---

<h2>Scenario 2 – Software Issue (Adobe Reader Not Working)</h2>

<h3>Step 1 – A New Ticket is Submitted</h3>

<p>
<img width="1397" height="725" alt="Screenshot 2026-03-08 at 8 13 35 PM" src="https://github.com/user-attachments/assets/75314a54-ce4d-468e-aff8-1a73e4a46554" />
</p>

A second ticket is created to demonstrate a different support scenario.

In this example, employees report that **Adobe Reader is not working properly in the accounting department**.

---

<h3>Step 2 – Support Agent Investigates the Issue</h3>

<p>
<img width="1440" height="729" alt="Screenshot 2026-03-08 at 8 25 23 PM" src="https://github.com/user-attachments/assets/71dfd77e-779e-40a5-9812-4804c1cb8155" />
</p>

The support agent investigates the issue and determines that the problem is related to a **recent Adobe software update**.

Possible solutions include:

- Manually installing the updated software package
- Waiting for the automatic update deployment.

---

<h3>Step 3 – Software is Updated and the Issue is Resolved</h3>

<p>
<img width="1440" height="489" alt="Screenshot 2026-03-08 at 8 26 02 PM" src="https://github.com/user-attachments/assets/a721793f-d197-4006-b7a9-9ebc102789f9" />
</p>

The support agent installs the updated Adobe Reader package and confirms the software is working correctly.

After verifying the fix, the ticket is closed to complete the support process.

---

<h2>Lifecycle Summary</h2>

These scenarios demonstrate the **complete lifecycle of a help desk ticket**:

1. Ticket submission
2. Ticket creation
3. Assignment to support staff
4. Investigation and troubleshooting
5. Escalation when necessary
6. Resolution of the issue
7. Ticket closure

This workflow mirrors how **real enterprise IT support teams manage and resolve technical issues**.
