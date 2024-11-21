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

- Step 1: Ticket Creation (Intake)
- Step 2: Viewing the Ticket Properties (Assignment & Communication)
- Step 3: Working the Issue (Resolution)
- Step 4: Confirm the Resolution
- Step 5: Document the Resolution

<h2>Lifecycle Stages</h2>
  
<h3>Step 1: Ticket Creation (Intake)</h4>h3>

<p>
<img src="https://i.imgur.com/leJAf2L.png" height="80%" width="80%" alt=""/>
</p>

The representative logs into the ticketing system and reads through the initial problem reported by the end user:
"Entire mobile/online banking system is down."

They check for related tickets or system alerts to confirm the scope of the issue.
They investigate the root cause by consulting server logs, system health monitoring tools, and team updates.

<h3>Step 2: Viewing the Ticket Properties (Assignment & Communication)</h3>
<p>
After analysis, they determine that the system is down due to a server overload from an unexpectedly high number of users trying to log in simultaneously.
</p>
    
<h3>Step 3: Working the Issue (Resolution)</h3>
 The representative coordinates with the IT team to:

- Increase Server Capacity: Temporarily allocate additional resources to handle the current load.
- Implement Traffic Throttling: Manage the number of users accessing the system to prevent further strain.
- Restart Affected Systems: Restart specific services or servers to restore normal operations.
- Test the System: Conduct internal testing to confirm that users can access online banking without issues.
 
<h3>Step 4: Confirm the Resolution</h3>

Once the issue is resolved, the representative ensures: </br>

- Internal testing is successful across various devices and platforms (e.g., mobile apps and browsers).
- External feedback confirms users can log in and perform transactions without errors.

<h3>Step 5: Document the Resolution</h3>

<p> The representative updates the ticket with a detailed resolution note to keep a record of the issue. For example: </br>

Problem Identified: </br> </br>
The online banking system experienced a server overload due to an unexpectedly high number of concurrent users. This caused intermittent access issues and system downtime for all users. </br> </br>

Action Taken: </br>

- Identified the root cause via server logs and performance monitoring tools.
- Scaled server capacity temporarily to manage the increased load.
- Implemented traffic throttling measures to prevent further overload.
- Conducted tests to confirm system stability.

Resolution Confirmation: </br>

- System functionality restored as of [Time and Date].
- Verified normal operations through internal checks and user feedback.

Next Steps (if applicable): </br>

- Scheduled a review of server capacity and traffic management policies.
- Recommended a permanent server upgrade to prevent recurrence.

Status: </br>
- Ticket marked as Resolved.

</p>

<p>
<img src="https://i.imgur.com/dLaF1ul.png" height="80%" width="80%" alt=""/>
</p>

<br />
