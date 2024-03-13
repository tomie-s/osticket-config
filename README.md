<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

<ul>
  <li>Configure Roles</li>
  <li>Configure Departments</li>
  <li>Configure Teams</li>
  <li>Enable anyone to create Tickets</li>
  <li>Configure Agents (workers)</li>
  <li>Configure Users (customers)</li>
  <li>Configure SLA</li>
  <li>Configure Help Topics</li>
</ul>

<h2>Configuration Steps</h2>

<b>Configure Roles</b>
<p>
Login to the osTicket account and go to <b>'Admin Panel -> Agents -> Roles'</b> to create a  new admin role and enable all permissions for this role.
</p>
<p>
<img src="https://github.com/tomie-s/osticket-config/assets/59409588/d1b69af9-c713-4564-8489-4deff1c26199" height="65%" width="65%" alt="Disk Sanitization Steps"/>
</p>
<br />

<b>Configure Departments</b>
<p>
Next, go to <b>'Admin Panel -> Agents -> Departments'</b> to create a new department.
</p>
<p>
<img src="https://github.com/tomie-s/osticket-config/assets/59409588/e9918568-81e4-4dfe-b2e8-0a29b371cb3c" height="65%" width="65%" alt="Disk Sanitization Steps"/>
</p>
<br />

<b>Configure Teams</b>
<p>
Next, go to <b>'Admin Panel -> Agents -> Teams'</b> to create a few teams.
</p>
<p>
<img src="https://github.com/tomie-s/osticket-config/assets/59409588/13f2c335-5b72-44ee-af38-75cf32765654" height="65%" width="65%" alt="Disk Sanitization Steps"/>
</p>
<br />

<b>Enable anyone to create Tickets</b>
<p>
Next, go to <b>'Admin Panel -> Settings -> User Settings'</b> to allow anyone to create tickets. It is important to ensure that the 'require registration and login to create tickets' box is unchecked so users can create tickets anonymously. 
</p>
<p>
<img src="https://github.com/tomie-s/osticket-config/assets/59409588/bde0614d-a4e0-4e7b-b3e2-91c72df8e6be" height="65%" width="65%" alt="Disk Sanitization Steps"/>
</p>
<br />

<b>Configure Agents (workers)</b>
<p>
Next, go to <b>'Admin Panel -> Agents -> Add New'</b> to create a few agents and assign them to a department.
</p>
<p>
<img src="https://github.com/tomie-s/osticket-config/assets/59409588/e15cac9d-d166-45df-a024-e6ce4d5e8bcf" height="65%" width="65%" alt="Disk Sanitization Steps"/>
</p>
<br />

<b>Configure Users (customers)</b>
<p>
Next, go to <b>'Agent Panel -> Users -> Add New'</b> to create a few users.
</p>
<p>
<img src="https://github.com/tomie-s/osticket-config/assets/59409588/3a69195c-e5d7-4748-9c4e-5fdc24e2c416" height="65%" width="65%" alt="Disk Sanitization Steps"/>
</p>
<br />

<b>Configure SLA</b>
<p>
Next, go to <b>'Admin Panel -> Manage -> SLA'</b> to create a couple of SLAs.
</p>
<p>
<img src="https://github.com/tomie-s/osticket-config/assets/59409588/321e49bc-be90-4673-b1c9-994f9620e486" height="65%" width="65%" alt="Disk Sanitization Steps"/>
</p>
<br />

<b>Configure Help Topics</b>
<p>
Lastly, go to <b>'Admin Panel -> Manage -> Help Topics'</b> to create some additional Help Topics that users can choose from when filling out the help desk ticket form.
</p>
<p>
<img src="https://github.com/tomie-s/osticket-config/assets/59409588/678264ca-eadd-4959-9ac0-7f570952712f" height="65%" width="65%" alt="Disk Sanitization Steps"/>
</p>
<br />
