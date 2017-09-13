---
layout: student-project
title: Betaport Project
permalink: /what-we-do/student-projects/Betaport/
---
<h1>The Betaport Project</h1>

<p>
<strong>Students:</strong> The Demigod John Couch<br>
<strong>Past:</strong> Samuel Barton, Christina Costello, Zachary Landry, Alex Weeman
</p>

<p>
The biggest issue in cyber security is the disconnect between physical and virtual. It’s a lot like insurance - you think you don’t need it until you do. We figured the solution to this problem was to build a virtual town in a contained area and conduct cyber attacks against that town, and thus created Betaport. Betaport is a town built in virtual machine software. So far it has about 250 virtual machines that make up various businesses, a bank, a hospital, and a town hall.
</p>

<figure>
<img src="/img/whiteboard1.jpg" alt="Beta Port whiteboarding" width="500" style="display:block;margin:0 auto;">
<figcaption style="text-align:center">
Initial Betaport Whiteboarding
</figcaption>
</figure>

<p>
In its humble beginnings, Betaport was hosted using Virtualbox, which got along fine until the size of the project demanded that an alternative be used. Through careful deliberation, the Red Hat open source software oVirt Hypervisor was chosen. oVirt allows for virtual machines to be hosted across many servers - utilizing those servers CPU and RAM capabilities, and allows those virtual machines to use vLANs to segment their networks. This lets us make the virtual environment as close to the “real thing” as possible.
</p>

<p>
Betaport was built to support 
<a href="{{ site.github.url }}/what-we-do/funded-research/#collaboratory" target="_blank">Cyber Corps</a>
. Cyber Corps takes place across three college campuses, where 15 students work together to bring their assigned business back to a functioning state. The students get real world experience on dealing with various cyber attacks such as distributed denial of service attacks, phishing and social engineering attacks, data exfiltration, and various malicious software.
</p>

<p>
Right now, Betaport is very abstract in nature - it doesn’t have any physical representation. As a result, it is impossible to visualize the cascading effects of a cyber attack in real time. Betaport is only visible in the digital network maps we’ve created. In order to give this project something tangible, we plan to integrate supervisory control and data acquisition 
SCADA <!-- Link? -->
 systems into Betaport. This will allow us to integrate with the 
<a href="{{ site.github.url }}/what-we-do/student-projects/METI/" target="_blank">METI Project</a>
, as a means to give the users who work with Betaport a visual representation of where things are and how they interact with each other. 
</p>

<a href="{{ site.github.url }}/what-we-do/student-projects/">Return to Student Projects</a>