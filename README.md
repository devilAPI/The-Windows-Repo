
<h1 class="code-line" data-line-start=0 data-line-end=1><a id="The_Windows_Repo_0"></a>The Windows Repo</h1>
<p class="has-line-data" data-line-start="1" data-line-end="2">The Windows Repo is a huge collection of malware, isos, beta previews and more.</p>
<h2 class="code-line" data-line-start=2 data-line-end=3><a id="New_2"></a>New!</h2>
<p class="has-line-data" data-line-start="3" data-line-end="4">Recently added:</p>
<ul>
<li class="has-line-data" data-line-start="4" data-line-end="5">Windows Whistler B2-2419.iso</li>
</ul>
<h2 class="code-line" data-line-start=5 data-line-end=6><a id="Diclaimer_5"></a>Diclaimer</h2>
<blockquote>
<p class="has-line-data" data-line-start="6" data-line-end="10">Malware in this repository is for private use <strong>ONLY</strong>!<br>
We dont own all of the Software<br>
We are not responsible for any damage<br>
to your system using the software in this repository.</p>
</blockquote>
<h2 class="code-line" data-line-start=10 data-line-end=11><a id="Using_beta_isos_10"></a>Using beta isos</h2>
<h3 class="code-line" data-line-start=11 data-line-end=12><a id="Timebombs_and_Keys_11"></a>Timebombs and Keys</h3>
<p class="has-line-data" data-line-start="12" data-line-end="33">Here is a list of timebombs for betas in this repository.<br>
Timebomb is a point when beta system stops functioning, so it cannot be leaked.<br>
Set the date a month or two before it to ensure it works.<br>
Most of the old beta images are not bootable, so you need to manually prepare the disk space and crap.<br>
We strongly recommend using emulators for anything below Windows Whistler.<br>
Date formatting: YYYY-MM-DD<br>
Look up additional info in the parentheses.<br>
Windows Chicago M4-58s: No timebomb<br>
Windows Nashville Beta-999: No timebomb<br>
Windows Memphis Alpha-1351: 1997-04-01<br>
Windows Millenium DR-2332.2: 1999-12-15 (RBDC9-VTRC8-D7972-J97JY-PRVMG)<br>
Windows Millenium B1-2394: 2000-03-15 (RBDC9-VTRC8-D7972-J97JY-PRVMG)<br>
Windows Neptune M2-5511: 2001-02-26 (W7XTC-2YWFB-K6BPT-GMHMV-B6FDY)<br>
Windows Janus PB-1515.1: No timebomb (Incredibly buggy ACPI! Turn it off in the BIOS)<br>
Windows Whistler PB-2202: 2001-04-22 (Is bootable, but causes BSOD if installed directly from CD)<br>
Windows Whistler B2-2419: 2001-07-13 (RBDC9-VTRC8-D7972-J97JY-PRVMG)<br>
Windows Longhorn M7-4074: 2004-10-23 (TCP8W-T8PQJ-WWRRH-QH76C-99FBW)<br>
Windows Longhorn B2-5308.50: 2007-03-07 (WGDJW-B8DYC-WVKX4-6MKF4-B8PK8)<br>
Windows Vienna PM1-6469: 2008-04-07<br>
Windows Jupiter M1-7850: 2011-02-05 (Use a Windows 7 Retail serial)<br>
Windows Threshold PTP-9780: 2015-07-15 (Use a Windows 8.1 Retail serial)</p>
<h2 class="code-line" data-line-start=33 data-line-end=34><a id="Installing_a_Virtual_Machine_33"></a>Installing a Virtual Machine</h2>
<p class="has-line-data" data-line-start="34" data-line-end="35">We strongly recommend using emulators/VMs for Malware and beta isos listed in this repository.</p>
<details>
    <summary>Click uwu</summary>
<h4 class="code-line" data-line-start=38 data-line-end=39><a id="Using_Virtualbox_on_Windows_38"></a>Using Virtualbox on Windows</h4>
<pre><code class="has-line-data" data-line-start="40" data-line-end="94" class="language-sh">Open the VirtualBox website. Go to https://www.virtualbox.org/ <span class="hljs-keyword">in</span> your computer<span class="hljs-string">'s Internet browser. This is the website from which you'</span>ll download the VirtualBox setup file.

Click <span class="hljs-string">"Download VirtualBox"</span>. It<span class="hljs-string">'s a blue button in the middle of the page. Doing so will open the downloads page.

Click "Windows hosts". You'</span>ll see this link below the <span class="hljs-string">"VirtualBox 5.2.8 platform packages"</span> heading. The VirtualBox EXE file will begin downloading onto your computer.

Open the VirtualBox EXE file. Go to the location to <span class="hljs-built_in">which</span> the EXE file downloaded and double-click the file. Doing so will open the VirtualBox installation window.

Navigate through the installation prompts. Do the following:
Click Next on the first three pages.
Click Yes when prompted.
Click Install
Click Yes when prompted.

Install the Drivers.

Click Finish when prompted. It<span class="hljs-string">'s in the lower-right side of the window. Doing so will close the installation window and open VirtualBox. Now that you'</span>ve installed and opened VirtualBox, you can create a virtual machine <span class="hljs-keyword">in</span> order to run any operating system on your PC.
Make sure that you don<span class="hljs-string">'t uncheck the "Start" box before doing this.


Gather your installation disc(s) or files. When creating a virtual machine, you will need to install the operating system just like you would on a regular computer. This means that you will need the installation disc(s) for the operating system you want to install on the virtual machine.
You can also install an operating system by using its ISO file.

Click "New". This will open the wizard that will guide you through the process to create your first virtual machine.

Identify the operating system. On the first screen of the wizard, you will be asked to give the new virtual machine a name as well as choose what operating system you will be installing. Choose the type of operating system from the "Type" menu, and then choose which version you are installing from the "Version" menu.
For example, if you are installing Windows 7, choose "Microsoft Windows" from the Type menu, and then "Windows 7" from the Version menu.
If you are installing the 64-bit version of the operating system, make sure to choose the 64-bit version from the Version menu.

Click "Next". It'</span>s at the bottom of the window.

Set the amount of RAM. You will need to designate how much of your computer<span class="hljs-string">'s RAM will be allocated to your virtual machine. VirtualBox will automatically choose the recommended minimum amount for the operating system you selected, but you can increase or decrease this if you'</span>d like.
You can only go as high as the amount of RAM physically installed <span class="hljs-keyword">in</span> your system.
It is not recommended that you <span class="hljs-built_in">set</span> it to the max amount, as there won<span class="hljs-string">'t be any left for your regular operating system to use when the virtual machine is running.

Click "Next"

Create a virtual hard drive. Select a virtual hard drive option and click Create, then click through the prompts and click Create again. Your virtual machine will need a virtual hard drive in order to install the operating system and any programs.
Make sure that the virtual hard drive has at least enough space to install the operating system. Check the specifications for your operating system to see how much space you should allocate at minimum.
Remember that any programs you install will also take up space on your virtual hard drive, so plan accordingly.
The most common format for virtual hard drives is VDI (VirtualBox Disk Image).


Start the operating system installation. Once the virtual machine has been configured, the wizard will close and you will be taken back to the VirtualBox main window. Double-click your new machine in the left menu, then do one of the following:
If you are installing from a disc, insert it into your computer, click the "Host drive" drop-down box and click the correct drive letter from the drop-down menu.
If you are installing from an image file, click the folder-shaped icon to browse through your computer for the installation image file.

Click Start. It'</span>s at the bottom of the window. This will prompt VirtualBox to begin reading your disk or file.

Install the operating system.

Boot up your virtual machine. Once the operating system is installed, your virtual machine is ready to go. Simply double-click the name of your virtual machine <span class="hljs-keyword">in</span> the left menu of the VirtualBox main page to start it up. The virtual computer will boot and load into the operating system that you installed.
Your virtual machine will run <span class="hljs-keyword">in</span> a window. Whenever the virtual machine window has focus, any keystrokes or mouse clicks will affect the virtual machine and not your physical computer.
</code></pre>
<h4 class="code-line" data-line-start=96 data-line-end=97><a id="Using_Virtualbox_on_Mac_96"></a>Using Virtualbox on Mac</h4>
<pre><code class="has-line-data" data-line-start="98" data-line-end="153" class="language-sh">Open the VirtualBox website. Go to https://www.virtualbox.org/ <span class="hljs-keyword">in</span> your Mac<span class="hljs-string">'s Internet browser. This is the website from which you'</span>ll download the VirtualBox DMG file.

Click <span class="hljs-string">"Download VirtualBox"</span>. It<span class="hljs-string">'s a blue button in the middle of the page. Doing so will open the downloads page.

Click the OS X hosts link. You'</span>ll find this option <span class="hljs-keyword">in</span> the middle of the downloads page. The VirtualBox DMG file will begin downloading onto your Mac.

Open the <span class="hljs-string">"VirtualBox"</span> DMG file. Once the VirtualBox DMG finishes downloading, double-click the file to open it.


Double-click the <span class="hljs-string">"VirtualBox.pkg"</span> icon. It<span class="hljs-string">'s a brown box-shaped icon in the upper-left corner of the window. Doing so will prompt VirtualBox'</span>s installation window to open.

Navigate through the installation prompts. Click Continue when prompted, <span class="hljs-keyword">then</span> <span class="hljs-keyword">do</span> the following:
Click Continue <span class="hljs-keyword">in</span> the bottom-right corner of the window.
Click Install <span class="hljs-keyword">in</span> the bottom-right corner of the window.
Enter your Mac user password when prompted.
Click Install Software

Wait <span class="hljs-keyword">for</span> the installation to complete. Once you<span class="hljs-string">'re prompted to click Close in the bottom-right corner of the window, you'</span>ve successfully installed VirtualBox on your Mac.

Open VirtualBox. Click Spotlight , <span class="hljs-built_in">type</span> <span class="hljs-keyword">in</span> virtualbox, and double-click VirtualBox <span class="hljs-keyword">in</span> the resulting drop-down menu. Now that you<span class="hljs-string">'ve installed and opened VirtualBox, you can create a virtual machine in order to run any operating system on your Mac.

Gather your installation disc(s) or files. When creating a virtual machine, you will need to install the operating system just like you would on a regular computer. This means that you will need the installation disc(s) for the operating system you want to install on the virtual machine.
You can also install an operating system by using its ISO file.

Click "New". This will open the wizard that will guide you through the process to create your first virtual machine.

Identify the operating system. On the first screen of the wizard, you will be asked to give the new virtual machine a name as well as choose what operating system you will be installing. Choose the type of operating system from the "Type" menu, and then choose which version you are installing from the "Version" menu.
For example, if you are installing Windows 7, choose "Microsoft Windows" from the Type menu, and then "Windows 7" from the Version menu.
If you are installing the 64-bit version of the operating system, make sure to choose the 64-bit version from the Version menu.

Click "Next". It'</span>s at the bottom of the window.

Set the amount of RAM. You will need to designate how much of your computer<span class="hljs-string">'s RAM will be allocated to your virtual machine. VirtualBox will automatically choose the recommended minimum amount for the operating system you selected, but you can increase or decrease this if you'</span>d like.
You can only go as high as the amount of RAM physically installed <span class="hljs-keyword">in</span> your system.
It is not recommended that you <span class="hljs-built_in">set</span> it to the max amount, as there won<span class="hljs-string">'t be any left for your regular operating system to use when the virtual machine is running.

Click "Next"

Create a virtual hard drive. Select a virtual hard drive option and click Create, then click through the prompts and click Create again. Your virtual machine will need a virtual hard drive in order to install the operating system and any programs.
Make sure that the virtual hard drive has at least enough space to install the operating system. Check the specifications for your operating system to see how much space you should allocate at minimum.
Remember that any programs you install will also take up space on your virtual hard drive, so plan accordingly.
The most common format for virtual hard drives is VDI (VirtualBox Disk Image).


Start the operating system installation. Once the virtual machine has been configured, the wizard will close and you will be taken back to the VirtualBox main window. Double-click your new machine in the left menu, then do one of the following:
If you are installing from a disc, insert it into your computer, click the "Host drive" drop-down box and click the correct drive letter from the drop-down menu.
If you are installing from an image file, click the folder-shaped icon to browse through your computer for the installation image file.

Click Start. It'</span>s at the bottom of the window. This will prompt VirtualBox to begin reading your disk or file.

Install the operating system.

Boot up your virtual machine. Once the operating system is installed, your virtual machine is ready to go. Simply double-click the name of your virtual machine <span class="hljs-keyword">in</span> the left menu of the VirtualBox main page to start it up. The virtual computer will boot and load into the operating system that you installed.
Your virtual machine will run <span class="hljs-keyword">in</span> a window. Whenever the virtual machine window has focus, any keystrokes or mouse clicks will affect the virtual machine and not your physical computer.
</code></pre>
<h4 class="code-line" data-line-start=153 data-line-end=154><a id="Using_VMWare_on_Windows_153"></a>Using VMWare on Windows</h4>
<pre><code class="has-line-data" data-line-start="155" data-line-end="199" class="language-sh">Make sure your computer meets the system requirements. Because you will be running an operating system from within your own operating system, VMware Workstation has fairly high system requirements. If you don’t meet these, you may not be able to run VMware effectively.
You must have a <span class="hljs-number">64</span>-bit processor.
VMware supports Windows and Linux operating systems.
You must have enough memory to run your operating system, the virtual operating system, and any programs inside that operating system. <span class="hljs-number">1</span> GB is the minimum, but <span class="hljs-number">3</span> or more is recommended.
You must have a <span class="hljs-number">16</span>-bit or <span class="hljs-number">32</span>-bit display adapter. <span class="hljs-number">3</span>D effects will most likely not work well inside the virtual operating system, so gaming is not always efficient.
You need at least <span class="hljs-number">1.5</span> GB of free space to install VMware Workstation, along with at least <span class="hljs-number">1</span> GB per operating system that you install.

Download the VMware software. You can download the VMware installer from the Download Center on the VMware website. Select the newest version and click the link <span class="hljs-keyword">for</span> the installer. You will need to login with your VMware username.
You will be asked to <span class="hljs-built_in">read</span> and review the license agreement before you can download the file.
You can only have one version of VMware Workstation installed at a time.


Install VMware Workstation. Once you have downloaded the file, right-click on the file and select “Run as administrator”.
You will be asked to review the license again.
Most users can use the Typical installation option.
At the end of the installation, you will be prompted <span class="hljs-keyword">for</span> your license key.
Once the installation is finished, restart the computer.

Open VMware. Installing a virtual operating system is much like installing it on a regular PC. You will need to have the installation disc or ISO image as well as any necessary licenses <span class="hljs-keyword">for</span> the operating system that you want to install.
You can install most distributions of Linux as well as any version of Windows.

Click File. Select New Virtual Machine and <span class="hljs-keyword">then</span> choose Typical. VMware will prompt you <span class="hljs-keyword">for</span> the installation media. If it recognizes the operating system, it will <span class="hljs-built_in">enable</span> Easy Installation:
Physical disc – Insert the installation disc <span class="hljs-keyword">for</span> the operating system you want to install and <span class="hljs-keyword">then</span> select the drive <span class="hljs-keyword">in</span> VMware.
ISO image – Browse to the location of the ISO file on your computer.
Install operating system later. This will create a blank virtual disk. You will need to manually install the operating system later.

Enter <span class="hljs-keyword">in</span> the details <span class="hljs-keyword">for</span> the operating system. For Windows and other licensed operating systems, you will need to enter your product key. You will also need to enter your preferred username and a password <span class="hljs-keyword">if</span> you want one.
If you are not using Easy Install, you will need to browse the list <span class="hljs-keyword">for</span> the operating system you are installing.

Name your virtual machine. The name will <span class="hljs-built_in">help</span> you identify it on your physical computer. It will also <span class="hljs-built_in">help</span> distinguish between multiple virtual computers running different operating systems.

Set the disk size. You can allocate any amount of free space on your computer to the virtual machine to act as the installed operating system’s hard drive. Make sure to <span class="hljs-built_in">set</span> enough to install any programs that you want to run <span class="hljs-keyword">in</span> the virtual machine.

Customize your virtual machine’s virtual hardware. You can <span class="hljs-built_in">set</span> the virtual machine to <span class="hljs-built_in">emulate</span> specific hardware by clicking the “Customize Hardware” button. This can be useful <span class="hljs-keyword">if</span> you are trying to run an older program that only supports certain hardware. Setting this is optional.

Install the selected Software.

Wait <span class="hljs-keyword">for</span> your installation to complete. Once you’ve powered on the virtual machine <span class="hljs-keyword">for</span> the first time, the operating system will begin to install automatically. If you provided all of the correct information during the setup of the virtual machine, <span class="hljs-keyword">then</span> you should not have to <span class="hljs-keyword">do</span> anything.
If you didn’t enter your product key or create a username during the virtual machine setup, you will most likely be prompted during the installation of the operating system.

[WINDOWS]
Check that VMware Tools is installed. Once the operating system is installed, the program VMware Tools should be automatically installed. Check that it appears on the desktop or <span class="hljs-keyword">in</span> the program files <span class="hljs-keyword">for</span> the newly installed operating system.
VMware tools are configuration options <span class="hljs-keyword">for</span> your virtual machine, and keeps your virtual machine up to date with any software changes.
</code></pre></details>
<h2 class="code-line" data-line-start=200 data-line-end=201><a id="Credits_200"></a>Credits</h2>
<p class="has-line-data" data-line-start="201" data-line-end="202">List of Software</p>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th>Plugin</th>
<th>REPO</th>
</tr>
</thead>
<tbody>
<tr>
<td>Coming</td>
<td>[Soon][PlDb]</td>
</tr>
</tbody>
</table>
<h3 class="code-line" data-line-start=205 data-line-end=206><a id="Upcoming_205"></a>Upcoming</h3>
<ul>
<li class="has-line-data" data-line-start="206" data-line-end="207">Looks very empty here…</li>
</ul>
<h3 class="code-line" data-line-start=207 data-line-end=208><a id="Request_207"></a>Request</h3>
<p class="has-line-data" data-line-start="208" data-line-end="210">Please open an issue on the Github issue tracker.<br>
License</p>
<hr>
<p class="has-line-data" data-line-start="211" data-line-end="212">MIT</p>
<p class="has-line-data" data-line-start="213" data-line-end="214"><strong>Free Software, Hell Yeah!</strong></p>
</body></html>
