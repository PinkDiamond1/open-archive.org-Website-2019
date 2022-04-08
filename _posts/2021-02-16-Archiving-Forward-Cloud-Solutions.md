---
layout: page
title: Archiving Forward - Demystifying the Cloud
description: Learn about what the benefits or drawbacks of preserving your media in the cloud. 
image: /images/021521_CloudSolutions_Cover.png
permalink: /ArchivingForward1
---

<div style="max-width: 1200px; text-align: center; margin: 0 auto;">
<img style="width: 100%; height: auto; margin: 10px 0px;" src="/images/021521_CloudSolutions_Cover.png"/>
</div>

<div style="text-align: left; display: relative;">
<p>There are countless tools and resources for the creation and capture of digital media. Now we take time to demystify the preservation process for this content. Our “Archiving Forward” blog series will explore and explain how different actors, from individuals, to community organizations, to technology providers, each play critical roles in preserving, amplifying, and securely sending significant and impactful mobile media to their destinations.</p>
  <p>Archiving Forward refers to a framework for bringing autonomy back to the capturer, through user-created collections in an accessible public trust or private server, outside the corporate walled gardens currently dominating the online media ecosystem.</p>
<img class="postLargeInlineImage" style="margin: 10px 20px 10px 0px;" src="/images/021521_CloudSolutions_Quote.png"/>
<p>When we began researching and prototyping our mobile application for ethical preservation (what is now <span class="appName">Save</span>) back in 2013, we discovered four key challenges facing organizations interested in managing mobile media:</p>
<p>
  <ul style="list-style-position: inside;">

 <li>Few initiatives to collective mobile media;</li>
<li>No easy way to preserve or license mobile media;</li>
<li>Pressing privacy considerations; and</li>
<li>A lack of resources.</li>
</ul> 
 </p>
 <p>Looking back, it is astonishing how quickly technological innovation has been able to mitigate these key challenges. In particular, the advent of the cloud, and adjacent <a href="https://opensource.com/resources/what-open-source" target="_blank">open source technologies</a> and documentation, make the task of preservation much more affordable and accessible than it used to be.</p>
<p>For the first entry in our Archiving Forward series, we will demystify the “cloud”: what it is, the benefits and drawbacks of using it to share and store media, and how we are utilizing it within the human rights community. We will also discuss why we chose Nextcloud as our preferred cloud backend.</p>

 
<h2>What is the cloud?</h2>
<p>A cloud is a type of server, so in order to understand the cloud, it is helpful to be familiar with the term “<b>server</b>.” A server is a computer, or a computer program, that manages access to a centralized resource or service in a network. A server’s function is to store, retrieve and send computer files and data to other computers on a network - so the more computers and files you have that are regularly accessing a central body, the more important it becomes to ensure that these interactions are secure and easily accessible.</p>
<p>The following infographic via <a href="https://media.defense.gov/2019/Jul/16/2002158059/-1/-1/0/CSI-CLOUD-SECURITY-BASICS.PDF?mod=article_inline" target="_blank">NSA's cloud security basics</a> illustrates the various forms that the cloud can take:</p>

<div style="max-width: 1200px; text-align: center; margin: 0 auto;">
<img style="width: 100%; height: auto; margin: 10px 0px; " src="/images/021521_CloudSolutions_Forms.png"/>
</div>

<h2>What are the main benefits of storing media in the cloud for the Human Rights Community?</h2>

<p>At OpenArchive our mission is to prioritize usability and privacy in our tools. Cloud-based storage considerably minimizes the cost of securely* storing and sharing digital content, without requiring highly technical expertise and training. This way, public interest organizations, as well as individuals, can easily run, manage, and maintain a server. Additional benefits include:
<br>
  <ul>
<li><b>Improved privacy & security</b>: some cloud services offer multiple layers of encryption and allow managers to set user controls, enabling them to choose who has access to the media on the cloud, as well as their level of access;</li>
<li><b>More affordable than a local server</b>: the cloud is relatively inexpensive over time;</li>
<li><b>Easier to use</b>: the UI (user interface) doesn’t require any coding knowledge and there is ample technical support available; and</li>
<li><b>More accessible</b>: all organizations need in order to access and manage the cloud is an internet connection.</li>
</ul> 
</p>
<p>However, not all cloud services are equal when it comes to security and privacy, there are key privacy risks involved when using the cloud. 
<br>
<p>*<i>While the cloud has benefits for organizations with less sensitive media, those housing media that can put people at risk of prosecution or violence if leaked, should consider only having offline, redundant servers.</i>
<p><div style="max-width: 1200px; text-align: center; margin: 0 auto;">
<img style="width: 100%; height: auto; margin: 10px 0px;" src="/images/021521_CloudSolutions_Benefits vs Risks.png"/>
</div></p>
<h2>What are the key risks when using the cloud?</h2>
<p>The two primary risks people face when using the cloud are malicious adversary activity (i.e. hacking/data breaches) and unintentional configuration flaws. To reiterate, we strongly recommend those with highly sensitive media (i.e. whistleblowers, media organizations, legal advocates, etc.) use local, offline, physical servers.
<br>
 <ul>

<li><b>Data breaches</b>: Large companies are more likely to be targeted by hackers; and</li>
<li><b>Configuration flaws</b>: Large companies with big servers handling multiple tasks are more susceptible to coding errors and other issues that are out of the control of the individuals or organizations that rely on them.</li>
</ul> 
<p>Now that we’ve highlighted some benefits and risks of using the cloud, we recommend taking the following features into consideration when choosing a remote cloud storage solution.
<br>
<div style="max-width: 1200px; text-align: center; margin: 0 auto;">
<img style="width: 100%; height: auto; margin: 10px 0px;" src="/images/021521_CloudSolutions_Recommendations.png"/>
</div>
<p><h2>Why did we choose Nextcloud as a preferred private backend for <span class="appName">Save</span>?</h2>
<p>We chose to include Nextcloud as one of <span class="appName">Save's</span> backends because they offer self-hosting, prioritize encryption, are committed to usability, and have a consistent privacy policy. It is easy to use both remotely and locally, and is the most secure option, especially if people maintain their local own servers. Additionally, <a href="https://nextcloud.com/encryption/" target="_blank">Nextcloud offers three layers of encryption on their servers</a> making it less vulnerable to hackers than other cloud services. These are cornerstones of the <span class="appName">Save</span> project, which ensures media files are accessed, stored and shared securely. 
<br>
<h2>Do any other cloud backends work with <span class="appName">Save</span>?</h2>
<p><span class="appName">Save</span> not only integrates with open source cloud services like Nextcloud, but also features the ability to save media to both the <a href="https://archive.org/" target="_blank">Internet Archive</a> and Dropbox backends, as well.
<br>
<p>By offering 3 different types of backends to use with <span class="appName">Save</span>, our goal is to support people’s varying storage needs. We will be including more as new options for secure, distributed storage emerge. In addition to Nextcloud, an open source cloud and physical server private backend, <span class="appName">Save</span> is also compatible with DropBox because it is more widely-used and accessible as many already have accounts (but offers less security), and the Internet Archive, a public backend committed to interoperability that guarantees your media is accessible online and in the future as formats evolve.
<br>
<p>While the cloud is no silver bullet, we believe Nextcloud is the best option for human rights defenders managing collections of sensitive mobile media who lack the capacity to host and maintain their own servers.</p>





