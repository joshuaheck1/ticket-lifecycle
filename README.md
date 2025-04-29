<p align="center">
<img width="900" alt="Screenshot 2025-04-27 at 7 28 04 PM" src="https://github.com/user-attachments/assets/e350f934-ca85-4e5e-9937-6eae6811f8c5" />

</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br/>

<h2>Prerequisites</h2>

- [Creating Virtual Machines in the Cloud](https://github.com/joshuaheck1/VM-creation)
- [osTicket: Prerequisites and Installation](https://github.com/joshuaheck1/osticket-prereqs)
- [osTicket: Post-Installation Configuration](https://github.com/joshuaheck1/post-install-config)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Windows App (macOS)
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- macOS Sequoia
- Windows 10 (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img width="750" alt="TL1" src="https://github.com/user-attachments/assets/f29c9413-e49c-466e-908f-f4db0a209044" />
</p>

<p>- Before we get started with creating and working tickets today, there was an issue discovered within osTicket about 30 mintues ago. We had a couple of clients call and ask for an update concerning some Help Desk Tickets they submitted. After several attempts, our Lead Agent was unable to locate the tickets. Then, the Lead Agent submitted a "Test" ticket via the Support Center portal and was unable to locate the "Test" ticket as well. Tickets are being created successfully but our Agents are not able to see them. The Help Desk Manager has exclated the issue to our Admin Team. Lets go solve this issue.    </p>
<p>- Go to the Admin / Agent Portal for osTicket - http://localhost/osTicket/scp/login.php </p>
<p>- Log in as an Admin. Username: "adminuser" | Password: Password1</p>
<br/>

<table>
  <tr>
    <td>
      <img width="1000" alt="TL2" src="https://github.com/user-attachments/assets/d8c57ea8-dccc-4035-aa1f-a52999a76c45" />
    </td>
    <td>
      <img width="1000" alt="TL3" src="https://github.com/user-attachments/assets/c3158223-20fb-4fc7-a287-3298f01b23c2" />
    </td>
  </tr>
</table>
<p>- Upon further investigation and working with Osticket Support, we discovered that a recent update caused a bug with a preset Department within osTicket. The bug is causing the tickets to be sent to the Maintenance Department regardless of the configurations. We will delete this department to get operations back to normal while osTicket works on a patch. </p>
<p>- From the Agent Panel, click -> Agents -> Departments. </p>
<p>- Check the box by Manitenance -> click the More dropdown -> click Delete.</p>

<table>
  <tr>
    <td>
      <img width="1000" alt="TL4" src="https://github.com/user-attachments/assets/e520d2a9-1a31-4592-9ef8-1024d6406d63" />
    </td>
    <td>
      <img width="1000" alt="TL5" src="https://github.com/user-attachments/assets/28aab28a-25e8-4176-8a90-96aa0430b7c0" />
    </td>
  </tr>
</table>
<p>- Click Yes, Do it! </p>
<p>- The Maintenance Department has successfully been deleted. We had our Agents log out / log back in to osTicket. They are reporting that the tickets are now visible and being routed to the correct Departments. That is a Win!😎 </p>





<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
