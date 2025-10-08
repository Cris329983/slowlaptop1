<p align="center">
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/c40a8191-a4ec-4647-833b-ddb06801c15f" />




</p>

<h1>Slow Laptop/PC</h1>
This Simulation tutorial demonstrates how to diagnose and fix a slow laptop by identifying high resource usage in Task Manager, cleaning unnecessary files with Disk Cleanup, and improving performance and security through Windows Update.
Note: This was done from my personal laptop which is not actually slow.<br />



<h2>Environments and Technologies Used</h2>

- Windows
- Task Manager
- Disk Cleanup

<h2>Operating Systems Used </h2>

- Windows 11


<h2> Steps</h2>                      

<p>
<img width="990" height="557" alt="image" src="https://github.com/user-attachments/assets/f3969117-8c13-4f55-b6e1-86f8223c48e1" />



</p>
<pStep 1: Initial Observation


One of the fixes for this issue is to open Task Manager (Ctrl + Shift + Esc) to analyze system performance.

If this was the case for the user then the Processes tab, the CPU, Memory, and Disk usage were all be close to 100%.

Several background processes were consuming a large amount of system resources.

The browser (Microsoft Edge) alone was using several gigabytes of memory, and multiple small processes were running simultaneously.

This indicated that too many apps and services were running at the same time, causing the laptop to slow down.


Step 2: Checking Startup Programs

Next, I reviewed the Startup Apps section in Task Manager.
Here, I noticed that many unnecessary applications were configured to launch automatically when Windows started — including:

Microsoft Teams

OneDrive

Grammarly

ClipClip

Phone Link

Other helper apps and services

These startup programs were consuming memory and CPU power immediately after boot, which explained the slow startup and overall lag.


Step 3: Optimization Performed

Disabled non-essential startup apps (Teams, OneDrive, Grammarly, etc.).

Ended background tasks using excessive CPU or memory.

Cleared temporary files and performed a Disk Cleanup.

Restarted the system and monitored performance again.

</p>
<br />

<p>
<img width="365" height="442" alt="image" src="https://github.com/user-attachments/assets/9f6e9282-257e-45ff-8a0e-22eda0793e60" />



</p>
<p> Another possible fix is to open Disk Cleanup for drive (C:) to remove unnecessary temporary files and cached data.
Selected items like:

Downloaded Program Files

Temporary Internet Files

DirectX Shader Cache

Delivery Optimization Files

Then clicked “Clean up system files” to free up additional space.

Result:

The cleanup removed about 246 MB of unnecessary files, improving available disk space and helping the system run smoother.
<p>
<img width="1123" height="342" alt="image" src="https://github.com/user-attachments/assets/e67e520d-f9de-4212-b91b-12d231eb3b3d" />




</p>
<p>Another fix is to simply update the system, outdated Windows versions can cause performance issues, security vulnerabilities, and driver incompatibility.

Action Taken:

Opened Settings → Windows Update, checked for available updates, and installed all pending security and system updates.
After installation, the system was restarted to apply the changes.

Result:

The latest updates improves performance, improved stability, and ensured the system had the most recent security patches. The laptop now runs smoother and more reliably.
