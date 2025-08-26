# 🎫 Ticketing System Lab: Tickets and Ticket Lifecycle

**About this Project:** This lab demonstrates my ability to use a professional ticketing system (osTicket) to manage the full lifecycle of IT issues. I created, updated, escalated, and resolved tickets while documenting each step with screenshots and reflections. The goal of this project is to showcase both my technical troubleshooting skills and my structured approach to problem-solving and communication—qualities that are directly applicable in real-world IT and system administration roles.

---

## 📝 Lab Setup
- **Admin/Analyst Login Page:** [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)
- **End Users osTicket URL:** [http://localhost/osTicket](http://localhost/osTicket)

### Initial Configuration
- Changed the **SysAdmins Department** to a **Top Level Department**.
- **Deleted** the Maintenance Department (not archived).

📸 *[Insert screenshot of department changes here]*

**Reflection:** Admin setup is just as important as ticket handling. A well-structured department tree ensures escalations and permissions behave the way they should.

---

## 🎟️ Ticket 1: Online Banking Outage
**Scenario:** End user reports the entire mobile/online banking system is down.

### Ticket Creation
- User: *Karen Doe* (Email: karen@lognpacific.com)
- Help Topic: **Report a Problem**
- Summary: *entire mobile/online banking system is down*
- Description: *Employees unable to access online banking; occasional logins fail.*

📸 *[Screenshots: ticket creation and confirmation]*

### John’s Updates
- Updated SLA from *Default* → **Sev-A (Critical, 1 hour, 24/7)**.
- Changed Help Topic to **Business Critical Outage**.
- Assigned ticket to **Online Banking Team** with notes.

📸 *[Screenshots of updates]*

### Jane’s Resolution
- Reassigned the ticket to herself.
- Replied to the end user with initial troubleshooting steps.
- Confirmed root cause (bad update), rolled it back, and notified vendor.
- Marked the ticket **Resolved**.

📸 *[Screenshots of replies and final resolution]*

**Reflection:** This ticket showed the full lifecycle—intake, escalation, reassignment, communication, and resolution. The hand-off between John and Jane mirrors real-world teamwork in critical incidents.

---

## 🎟️ Ticket 2: Adobe Upgrade Request
**Scenario:** Accounting department requests an Adobe software upgrade.

### Ticket Creation
- User: *Ken Doe* (Email: ken@lognpacific.com)
- Help Topic: **General Inquiry / Other**
- Summary: *Accounting department needs Adobe upgrade*
- Description: *Many users can’t use Adobe software.*

📸 *[Screenshots of ticket creation]*

### John’s Updates
- Changed SLA from *Default* → **Sev-C**, with justification: only 2 users impacted.
- Assigned the ticket to himself.

📸 *[Screenshot of SLA change & assignment]*

### Resolution
- Documented troubleshooting via internal notes.
- Restart fixed the issue.
- Ticket marked **Resolved**.

📸 *[Screenshots of resolution]*

⚠️ **Note on Permissions:** John should have had reply permissions, but I overlooked it. Because of this, he only used internal notes. In a real-world setting, I would have corrected the agent role permissions so he could communicate directly with the user.

**Reflection:** Even smaller tickets require proper classification and documentation. I learned that making sure roles are set up correctly is critical for smooth communication.

---

## 🎟️ Ticket 3: CFO’s Laptop Will Not Turn On
**Scenario:** End user reports the CFO’s laptop won’t power on.

### Ticket Creation
- User: *Karen Doe* (Email: karen@lognpacific.com)
- Help Topic: **Personal Computer Issues**
- Summary: *CFO’s laptop will no longer turn on*
- Description: *Laptop won’t turn on despite pressing the power button.*

📸 *[Screenshots of ticket creation]*

### John’s Updates
- Updated priority from *Normal* → **Emergency**.
- Changed SLA from *Default* → **Sev-B**, with note that it may be reclassified.
- Assigned ticket to himself.

📸 *[Screenshots of updates]*

### Resolution
- Diagnosed the issue as a broken charger.
- Replaced the charger, confirmed laptop charging successfully.
- Closed the ticket as **Resolved**, documenting the root cause.

📸 *[Screenshots of resolution]*

⚠️ **Note on Permissions:** Just like in Ticket 2, John should have had reply permissions here too. I only noticed it too late, which limited him to internal notes.

**Reflection:** Severity levels matter. A CFO’s laptop was treated as an Emergency, and I resolved it quickly. This emphasized the need for accurate prioritization and proactive permission checks.

---

## ✅ Reflections and Future Plans
Looking back at this project, I can see how much ground I covered. I went from simply creating tickets to fully managing their lifecycle—updating properties, assigning teams, escalating when necessary, and resolving issues with clear documentation. I also experienced first-hand how permissions and roles can affect communication between agents and end users.

For myself, this project shows that I am capable of using a ticketing system like osTicket in a professional setting. I know how to properly classify, prioritize, and close tickets while keeping user communication in mind.

### Future Learning Goals
- Explore the **email integration** feature more deeply so I can simulate real-world notifications and user responses.
- Practice setting up **automation and SLA rules** to better understand how escalations can be enforced without manual changes.
- Learn more about **reporting and metrics** so I can demonstrate how ticket data translates into performance insights.
- Continue to redo this lab until every step feels natural and repeatable—building my technical intuition further.
- Practice handling **ticket intake through multiple channels** (phone, chat, email, web forms, even in-person requests) to simulate real-world help desk conditions.

**Personal Note**:** This write-up is not just practice; it’s a showcase for future employers and teammates. It reflects both my technical ability and my commitment to documenting work clearly and professionally.

