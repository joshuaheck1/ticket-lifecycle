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
<p>- The Maintenance Department has successfully been deleted. We had our Agents log out / log back in to osTicket. They are reporting that the tickets are now visible and being routed to the correct Departments. That is a Win! Now, we can get to creating and working tickets. 😎</p>
<br/>

<table>
  <tr>
    <td>
      <img width="1000" alt="TL6" src="https://github.com/user-attachments/assets/6b35cc6e-519d-4ec3-9f75-20c3f655d173" />
    </td>
    <td>
      <img width="1000" alt="TL7" src="https://github.com/user-attachments/assets/52233b24-a17c-47c3-a143-686a130ac711" />
    </td>
  </tr>
</table>
<p>- Open the Support Center. (User portal - http://localhost/osTicket) </p>
<p>- Click "Open a New Ticket".</p>
<p>- Enter the folllowing - Email Addtrress: karen@lognpacific.com | Full Name: Karen | Help Topic: Report a Problem.</p>
<p>- Fill out Issue Summary as you see in Figure 7. Scroll down and click Create Ticket.</p>

<table>
  <tr>
    <td>
      <img width="1000" alt="TL8" src="https://github.com/user-attachments/assets/15281ad1-cbff-4c2b-8aeb-cc25c23a9acf" />
    </td>
    <td>
      <img width="1000" alt=<"TL9" src="https://github.com/user-attachments/assets/73284ce1-d5dc-4285-a4ca-50c72a8c0f3f" />
    </td>
  </tr>
</table>

<p>- New create is successfully created.
<p>- Now, log in to the Admin / Agent Portal as John Doe. Username: john_doe | Password: Password1 </p>

<p>
<img width="750" alt="TL10" src="https://github.com/user-attachments/assets/49cabd55-cb06-48ba-9f64-3957da5a686a" />
</p>

<p>- Once logged in, click Tickets -> Open.</p>
<p>- This will display all the open tickets. Locate the ticket we just created as Karen and open it.</p>
<br/>

<p>
<img width="750" alt="TL11" src="https://github.com/user-attachments/assets/cea365f7-922e-4e1a-bb9c-8d2edf2af42b" />
</p>

<p>- 
<p>- Most Users and/or Clients may not know SLAs, and correct Help Topics .</p>
<p>- This will display all the open tickets. Locate the ticket we just created as Karen and open it.</p>
<br/>




<table>
  <tr>
    <td>
      <img width="1000" alt="TL11" src="https://github.com/user-attachments/assets/80e2a47e-633c-4fdc-96d2-614a5ad52e08" />
    </td>
    <td>
      <img width="1000" alt=<"TL9" src="https://github.com/user-attachments/assets/73284ce1-d5dc-4285-a4ca-50c72a8c0f3f" />
    </td>
  </tr>
</table>

<p>- New create is successfully created.
<p>- Now, log in to the Admin / Agent Portal as John Doe. Username: john_doe | Password: Password1 </p>
