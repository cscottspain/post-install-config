<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### (COMING SOON!)[YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Roles
- Departments
- Teams
- Ticket configuration
- Agents
- Users
- SLA
- Help Topics

<h2>Configuration Steps</h2>
<ul dir="auto">
    <li>
        <p dir="auto">Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Roles.html" rel="nofollow">Roles</a></p>
        <ol dir="auto">
            <li>
                <p dir="auto">Admin Panel -&gt; Agents -&gt; Roles</p>
            </li>
            <li>
                <p dir="auto">Supreme Admin</p>
            </li>
        </ol>
    </li>
</ul>
<p><img src="https://myfiles.space/user_files/136342_a1cddde58552a220/136342_custom_files/img1668473774.png" width="751" height="304"></p>
<ul dir="auto">
    <li>
        <p dir="auto">Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Departments.html" rel="nofollow">Departments</a></p>
        <ol dir="auto">
            <li>
                <p dir="auto">Admin Panel -&gt; Agents -&gt; Departments</p>
            </li>
            <li>
                <p dir="auto">System Administrators</p>
            </li>
        </ol>
    </li>
</ul>
<p><img src="https://myfiles.space/user_files/136342_a1cddde58552a220/136342_custom_files/img1668473816.png" width="752" height="261"></p>
<ul dir="auto">
    <li>
        <p dir="auto">Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Teams.html" rel="nofollow">Teams</a></p>
        <ul dir="auto">
            <li>
                <p dir="auto">Admin Panel -&gt; Agents -&gt; Teams</p>
            </li>
        </ul>
    </li>
</ul>
<p><img src="https://myfiles.space/user_files/136342_a1cddde58552a220/136342_custom_files/img1668473851.png" width="753" height="241"></p>
<ul dir="auto">
    <li>
        <p dir="auto">Allow anyone to create tickets</p>
        <ol dir="auto">
            <li>
                <p dir="auto">Admin Panel -&gt; Settings -&gt; User Settings</p>
            </li>
            <li>
                <p dir="auto">Registration Required: Require registration and login to create tickets&nbsp;</p>
            </li>
        </ol>
    </li>
</ul>
<p><img src="https://myfiles.space/user_files/136342_a1cddde58552a220/136342_custom_files/img1668473947.png" width="752" height="537"></p>
<ul dir="auto">
    <li>
        <p dir="auto">Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Agents.html" rel="nofollow">Agents (workers)</a></p>
        <ul dir="auto">
            <li>
                <p dir="auto">Admin Panel -&gt; Agents -&gt; Add New</p>
            </li>
        </ul>
    </li>
</ul>
<p><img src="https://myfiles.space/user_files/136342_a1cddde58552a220/136342_custom_files/img1668474031.png" width="753" height="275"></p>
<p><img src="https://myfiles.space/user_files/136342_a1cddde58552a220/136342_custom_files/img1668474132.png" width="749" height="688" style="max-width: 100%; cursor: pointer; color: rgb(0, 0, 0); font-family: Times; font-size: medium; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><br></p>
<ul dir="auto">
    <li>
        <p dir="auto">Configure <a href="https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html" rel="nofollow">Users (customers)</a></p>
        <ul dir="auto">
            <li>
                <p dir="auto">Agent Panel -&gt; Users -&gt; Add New</p>
            </li>
        </ul>
    </li>
</ul>
<p><img src="https://myfiles.space/user_files/136342_a1cddde58552a220/136342_custom_files/img1668474312.png" width="751" height="274"></p>
<p><img src="https://myfiles.space/user_files/136342_a1cddde58552a220/136342_custom_files/img1668474353.png" width="513" height="313"></p>
<ul dir="auto">
    <li>
        <p dir="auto">Configure <a href="https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html" rel="nofollow">SLA</a></p>
        <ul dir="auto">
            <li>
                <p dir="auto">Admin Panel -&gt; Manage -&gt; SLA</p>
            </li>
        </ul>
    </li>
</ul>
<p><img src="https://myfiles.space/user_files/136342_a1cddde58552a220/136342_custom_files/img1668474422.png" width="751" height="245"></p>
<ul dir="auto">
    <li>
        <p dir="auto">Configure Help Topics</p>
        <ul dir="auto">
            <li>
                <p dir="auto">Admin Panel -&gt; Manage -&gt; Help Topics</p>
            </li>
        </ul>
    </li>
</ul>
<p><img src="https://myfiles.space/user_files/136342_a1cddde58552a220/136342_custom_files/img1668474457.png" width="752" height="335"></p>
