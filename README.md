<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<ul>
    <li>
        <p>Configure&nbsp;<a href="https://docs.osticket.com/en/latest/Admin/Agents/Roles.html">Roles</a></p>
        <ol>
            <li>
                <p>Admin Panel -&gt; Agents -&gt; Roles</p>
            </li>
            <li>
                <p>Supreme Admin</p>
            </li>
        </ol>
    </li>
    <li>
        <p>Configure&nbsp;<a href="https://docs.osticket.com/en/latest/Admin/Agents/Departments.html">Departments</a></p>
        <ol>
            <li>
                <p>Admin Panel -&gt; Agents -&gt; Departments</p>
            </li>
            <li>
                <p>System Administrators</p>
            </li>
        </ol>
    </li>
    <li>
        <p>Configure&nbsp;<a href="https://docs.osticket.com/en/latest/Admin/Agents/Teams.html">Teams</a></p>
        <ol>
            <li>
                <p>Admin Panel -&gt; Agents -&gt; Teams</p>
                <ol>
                    <li>
                        <p>Level I Support</p>
                    </li>
                    <li>
                        <p>Level II Support</p>
                    </li>
                </ol>
            </li>
        </ol>
    </li>
    <li>
        <p>Allow anyone to create tickets</p>
        <ol>
            <li>
                <p>Admin Panel -&gt; Settings -&gt; User Settings</p>
            </li>
            <li>
                <p>Registration Required: Require registration and login to create tickets&nbsp;</p>
            </li>
        </ol>
    </li>
    <li>
        <p>Configure&nbsp;<a href="https://docs.osticket.com/en/latest/Admin/Agents/Agents.html">Agents (workers)</a></p>
        <ol>
            <li>
                <p>Admin Panel -&gt; Agents -&gt; Add New</p>
                <ol>
                    <li>
                        <p>Jane</p>
                    </li>
                    <li>
                        <p>John</p>
                    </li>
                </ol>
            </li>
        </ol>
    </li>
    <li>
        <p>Configure&nbsp;<a href="https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html">Users (customers)</a></p>
        <ol>
            <li>
                <p>Agent Panel -&gt; Users -&gt; Add New</p>
                <ol>
                    <li>
                        <p>Karen</p>
                    </li>
                    <li>
                        <p>Ken</p>
                    </li>
                </ol>
            </li>
        </ol>
    </li>
    <li>
        <p>Configure&nbsp;<a href="https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html">SLA</a></p>
        <ol>
            <li>
                <p>Admin Panel -&gt; Manage -&gt; SLA</p>
                <ol>
                    <li>
                        <p>Sev-A (1 hour, 24/7)</p>
                    </li>
                    <li>
                        <p>Sev-B (4 hours, 24/7)</p>
                    </li>
                    <li>
                        <p>Sev-C (8 hours, business hours)</p>
                    </li>
                </ol>
            </li>
        </ol>
    </li>
    <li>
        <p>Configure Help Topics</p>
        <ol>
            <li>
                <p>Admin Panel -&gt; Manage -&gt; Help Topics</p>
                <ol>
                    <li>
                        <p>Business Critical Outage</p>
                    </li>
                    <li>
                        <p>Personal Computer Issues</p>
                    </li>
                    <li>
                        <p>Equipment Request</p>
                    </li>
                    <li>
                        <p>Password Reset</p>
                    </li>
                </ol>
            </li>
        </ol>
    </li>
</ul>
