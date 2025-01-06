<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h2>Step 1: Delete Maintenance Agent</h2>

<p>
<img src="https://github.com/user-attachments/assets/b9b43397-dcf9-402e-94f3-0670433780bc" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log in to Admin Panel:

Open the link: http://localhost/osTicket/scp/login.php.
Log in with your admin credentials.
Open End User Portal:

Open a new tab and paste this link: http://localhost/osTicket.
This is the end-user portal where users submit tickets.
Delete Maintenance Agent:

Go back to the Admin Panel (the first link).
In the Admin Panel, navigate to Agents.
Find and select the Maintenance agent from the list.
Click on More and then select Delete.
Confirm by clicking Yes, I do to delete the agent.
Then logout
</p>
<br />

<h2>Step 2: Create a Ticket as an End User</h2>

<p>
<img src="https://github.com/user-attachments/assets/10601970-08fc-4093-a90f-f7b790b2f6e5" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open the second link: http://localhost/osTicket.

Click Open New Ticket on the webpage.

Fill out the ticket details as the web user created previously:

Help Topic: Report a Problem (Note: End users might not always choose the correct topic.)

Issue Summary: Entire online/banking system is down.

Details/Reason for Creating the Ticket: 
My employees are reporting that users are no longer able to access the online banking portal. The ones who can occasionally access it cannot log in.
Click Create Ticket to submit the ticket.
</p>
<br />

<h2>Step 2 - Handling a Critical Support Ticket in the Help Desk System</h2>

<p>
<img src="https://github.com/user-attachments/assets/4cdd2b7d-6212-4216-9a04-b085686d9709" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Navigate to the Support Department:

Log in as the help desk agent assigned to the support department.
2. Access the Ticket:

Locate the ticket that was just created.
Click on the ticket to open it.
3. Update SLA Settings:

Click on Default SLA to expand it.
Select Sev-A from the options.
In the text box, type:
"Wide impact, customers unable to do online banking."
Save or update the changes.
4. Update the Help Topic:

Click on Help Topic and change it to Business Critical Outage.
In the text box, type:
"No customers allowed to access online banking."
Save or update the changes.
5. Assign the Ticket:

Click Assigned To and select Online Banking.
In the text box, type:
"Customers unable to access online banking portal, assigning to online banking team."
Click Assign and Log to complete the assignment.
6. Log Out:

Once all updates are made, log out of the system.
</p>
<br />

<h2>Step 3 - Resolving a Critical Support Ticket</h2>

<p>
<img src="https://github.com/user-attachments/assets/d2e1f71f-6fe0-4a52-9257-6ece82a6a6e5" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Log In as the Assigned User:

Sign in as the user assigned to Online Banking.
2. Access the Ticket:

Locate the ticket and click to open it.
3. Reassign the Ticket:

Click Assigned and change the assignee to the user you are logged in as.
In the text box, type:
"I'll be taking this ticket."
Save the changes.
4. Post an Initial Reply:

Scroll down to Post Reply and in the text box, type:
"I suspect the problems might be related to the recent updates. We tested them sufficiently, but I’m going to look into it further and roll them back if I determine that was the cause."
Click Post Reply to update the ticket.
5. Post a Follow-Up Reply:

In the Post Reply text box, type:
"It was determined that the root cause was the recent update. We rolled it back, notified the vendor, and are waiting for a proper fix. Online banking should be up and running."
Click Post Reply to finalize the update.
6. Resolve the Ticket:

Scroll up and change the Status to Resolved.
Click Close to complete the process.
</p>
<br />

<h2>Step 4 - Creating a General Inquiry Ticket</h2>

<p>
<img src="https://github.com/user-attachments/assets/09d9fd4a-2d1c-4863-b1a0-262f36feb762" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Navigate to the Ticket Creation Page:

Go back to where you created the ticket.
Click Open Ticket to begin.
2. Fill Out Ticket Information:

Assign the ticket to the user previously created.
Select General Inquiry under Help Topic and then choose Other.
3. Add Issue Details:

For Issue Summary, type:
"Accounting department needs Adobe upgrade, broken."
In the text box below, type:
"It looks like many people in the accounting department can’t use their Adobe software."
4. Create the Ticket:

Click Create Ticket to finalize the submission.
</p>
<br />

<h2> Step 5 - Handling a General Inquiry Ticket</h2>

<p>
<img src="https://github.com/user-attachments/assets/fefbd306-54a2-49b0-987e-af7007c3c1b3" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Log In as the Assigned User:

Log in as the user assigned to Support.
2. Open the Ticket:

Locate and click on the ticket to open it.
3. Update SLA Settings:

Click SLA and set it to Sev-C.
In the text box, type:
"Only two people are unable to open Adobe Reader, classifying as Sev-C."
Update the changes.
4. Reassign the Ticket:

Click Assigned To and assign it to the user you are currently logged in as.
5. Post the Initial Reply:

In the Post Reply text box, type:
"CX (customer) states that only 2 people in the accounting department are unable to open and use Adobe Reader. CX testing restart, will call back after lunch."
Click Post Reply to update the ticket.
6. Post a Follow-Up Reply:

In the Post Reply text box, type:
"CX states that restarting fixed the issue, closing out ticket."
Click Post Reply to finalize the update.
7. Close the Ticket:

Next to Status, click Resolved.
In the text box, type:
"Restart fixed the issue for both users."
Click Close to finalize the ticket resolution.
</p>
<br />

<h2>Step 6 - Creating a Ticket for Personal Computer Issue</h2>

<p>
<img src="https://github.com/user-attachments/assets/8d2f902b-29b8-42c0-8b45-a24754064baa" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Navigate to the Ticket Creation Page:

Go back to the tab where you create a ticket.
Click Create New Ticket to begin.
2. Fill Out Ticket Information:

Under Help Topic, select Report an Issue and then choose Personal Computer Issues.
3. Add Issue Details:

For Issue Summary, type:
"CFO is unable to use his laptop."
In the text box below, type:
"Laptop won't power up despite pressing the power button."
4. Create the Ticket:

Click Create Ticket to submit the request.
</p>
<br />

<h2>Step 7 - Resolving a Personal Computer Issue Ticket</h2>

<p>
<img src="https://github.com/user-attachments/assets/6ea3eb0d-a4ab-4f49-ba74-3e5ac4015950" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Log In as the Assigned User:

Log in as the user assigned to Support.
2. Open the Ticket:

Locate and click on the ticket to open it.
3. Update SLA Settings:

Click SLA and classify it as Sev-B.
In the text box, type:
"May reclassify after getting more info."
Click Update to save the changes.
4. Post the Initial Reply:

Scroll down to Post Reply and in the text box, type:
"CFO’s laptop was not charging due to a broken charger. Brought a new charger, now successfully charging."
Click Post Reply to update the ticket.
5. Close the Ticket:

Click Status and select Resolved.
In the text box, type:
"Charger was broken, because of this the battery was dead and unable to turn on."
Click Close to finalize the resolution.
</p>
<br />
