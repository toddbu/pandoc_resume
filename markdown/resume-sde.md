Todd Buiten
===========

-------------------     ----------------------------
23909 152nd Ave SE                   todd@buiten.com
Kent, WA  98042                         206.459.6213
-------------------     ----------------------------

Education
---------

Bachelor of Science degree with a major in Computer Science.  
**Calvin College**, Grand Rapids, MI. May 1987.

Work Summary
------------

I have been a professional Software Developer and Architect for over 35 years, primarily working on large scale global web sites with millions of users and billions of transactions per day. My secondary focus is on IoT at both the hardware and data collection tiers. As a developer skilled in both frontend and backend technologies, I am up-to-date in many modern technologies such as React, HTML 5, and CSS3 (frontend) and Node.js, Python, REST APIs, Docker, and Kubernetes (backend). I love designing and building complex software as well as helping my colleagues learn new technologies and processes.

I have worked for a wide range of companies from small mom-and-pops to large multinationals (Microsoft, Starbucks, T-Mobile, GoDaddy). I specialize in web technology, global geo-distribution, and IoT.

Technology Summary
------------------

**Programming Languages**: Node.js/Javascript/JSON, Python, C, C++, C#/.Net Core, Java, VB, Bash, PHP, Assembly

**FrontEnd**: React, Redux, HTML5/CSS3, JWT, SAML, SPA

**BackEnd**: REST, SOAP, Web Services, Microservice Architecture, Apache, Thread synchronization

**Databases**: Postgres, MySQL, MSSQL, Cassandra

**Infrastructure**: Docker, Kubernetes, AWS (EC2, ECS, RDS, CloudWatch, IAM, Batch), Azure, Ansible, CI Build, GitHub, GitLab

**Hardware**: ESP32, nRF52840, Raspberry Pi Pico, Raspberry Pi, ARM, x86, RISC-V, RS-232, RS-485, Modbus, PLC, PCB Design

**Operating Systems**: Ubuntu/Debian, Centos/RedHat, FreeRTOS, MacOS, Windows

**IoT**: LoRa, LoraWAN, MachineQ

**Other**: SSH, Arduino IDE, FFmpeg, Agile, Kanban

Patent Awards
-------------

I have co-authored and been awarded six patents by the US Patent and Trade Office:

[5,126,945](https://patents.google.com/patent/US5126945A/en) - Nonferrous extrusion process control system  
[6,304,857](https://patentimages.storage.googleapis.com/f2/c3/4d/63e608ffc0b253/US6304857.pdf) - Distributed electronic billing system with gateway interfacing biller and service center  
[8,001,002](https://patentimages.storage.googleapis.com/a4/29/90/915460ee3407c7/US8001002.pdf) - Interactively presenting advertising content offline  
[8,156,418](https://patentimages.storage.googleapis.com/e3/0a/bf/ffda7a935540d0/US8156418.pdf) - Image acquisition from dynamic content for delivery to network-enabled static display devices  
[9,071,651](https://patentimages.storage.googleapis.com/9e/01/e8/68cb0bbcaf42c1/US9071651.pdf) - Dynamic content delivery to network-enabled static display device  
[9,112,702 / 9,613,205](https://patentimages.storage.googleapis.com/ae/50/ce/f41fff2f033e1e/US9613205.pdf) - Alternate authentication

Work Experience
---------------

**Principal Software Development Engineer / Architect (Consulting):** Six Dutchmen Corporation (March 2014 - Present)  
**_Technology_**: Node.js, Docker, Kubernetes, Cassandra, React, React Hooks, Redux, Material UI, HTML5/CSS3, Javascript/AJAX, JSON, SAML, JWT, C#, .Net Core, Akamai CDN/DSA/GTM, MySQL, Postgres, TimescaleDB, Logstash, IoT, LoRa, LoRaWAN, MachineQ, ESP32, nRF52840, Raspberry Pi Pico, Raspberry Pi, PCB Design, Arduino IDE, Jenkins, SharePoint

For [Starbucks](https://starbucks.com), I designed and implemented a custom IoT module in conjunction with [Follett Ice](https://www.follettice.com/) and [MachineQ](https://www.machineq.com/) to monitor the operation of the nugget ice machines in their retail stores nationwide. Continuous operation of these ice machines is critical to customer satisfaction and revenue. By combining off-the-shelf LoRaWAN hardware with custom firmware, I was able to build a low-cost, reliable solution with code written in C++. The resulting device is capable of uplinking both event and status information to the MachineQ LoRaWAN network as well as performing edge computing functions.

I also built an integration test frame to help ensure that reliability of any device deployed in-store. To accomplish this, I used sophisticated state machine techniques to monitor log file output to confirm that each operation that was expected did in fact occur and without error.

For [Lithia](https://www.lithia.com/), I designed and built both React frontend components and C# backend APIs to replace an existing, inefficient internal backoffice workflow. We replaced a series of Excel spreadsheets and macros to manage customer vehicle trade-ins with a custom-built user interface designed to improve the speed and accuracy of processing a large volume of such trade-ins. By integrating SharePoint directly into our application (secured by Azure Active Directory), we completely eliminated a cumbersome and error-prone process.

For [Xandr](https://en.wikipedia.org/wiki/Xandr) (the advertising unit of AT&T after the merger of AT&T and Time-Warner, subsequently sold to Microsoft), I designed and implemented both React frontend components and Node backend APIs to integrate the [Snowflake](https://www.snowflake.com/) cloud data analysis tool into a usable package for Xandr employees. Our solution combined Material UI with SAML-based authentication (converted to JWTs) to provide a seamless user experience to queries on adverising inventory and performance. The entire solution is hosted on Amazon Web Service (AWS) and Elastic Kubernetes Service (EKS). Additionally, as an advocate for code quality, I drove shared React and Node libraries across the entire project. I also rallied our development team around unit testing and implemented a Pull Request builder to ensure that unit tests passed all checks before code is merged in GitHub.

For [Intelight](https://www.intelight-its.com/), I designed and implemented a pluggable, scalable event ingestion pipeline capable of processing a trillion traffic signal events per customer per year using Node and several SQL and No-SQL databases (Influx, Casssandra, MySQL, PostGres, TimescaleDB, and Citus). I also designed and implemented long-term storage solution for compressing inbound event traffic by over 97%, thereby reducing each terabyte of event data to a mere 30GB.

For [Carnival Cruise Lines](https://www.carnivalcorp.com/), I designed and implemented portions of the "Ocean Compass Web" (OCW) website. As part of the [Ocean Medallion](http://www.princess.com/ships-and-experience/ocean-medallion-class/) program announced by Carnival in the [keynote address at CES 2017](https://www.youtube.com/watch?v=Im7xJeHrvkM), OCW gives cruise line guests a much simpler and more enjoyable travel experience by using wireless technology to become their personal concierge. OCW manages every aspect of a guest's experience including travel to/from the vessel, stateroom configuration, dietary and dining preferences, shore excursions, and much, much more.

I spent three years modernizing the [GoDaddy.com](http://www.godaddy.com) web site. This includes designing and building Node.js applications for various pages on the site. These applications ran in Docker containers and were deployed across datacenters in the U.S., Europe, and Asia. This work spawned an internal tool called "Expresso Hub" which is used by nearly 20 different internal applications. The standardization of deployment and operations significantly reduced the time to bring new features to market. It also improved the quality of the code by allowing new code to be tested offline using data from the production environment. Finally, we freed up approximately five full-time engineers who would otherwise be committed to operations. Deployments that had typically taken a full day could be done in less that five minutes. The "Expresso Hub" application was built on top of Kubernetes and became the GoDaddy standard platform for deploying both internal and external web sites and RESTful APIs.

----- ----- -----
      * * *
----- ----- -----

**Software Engineer:** [Apkudo, Inc](https://apkudo.com/) (August 2019 - December 2022)  
**_Technology_**: Node.js, Python, Java, Docker, ECS, Postgres, JSON, SAML, JWT, FFmpeg/H.264, AWS, Robotics

Whenever you break your cell phone and bring it back to the store to get a new one, your old phone is sent to a facility that checks its condition and decides if it should be repaired, sold off to a third party, or recycled. As part of the evaluation process, the cell phone is sent through a line of robots that checks it for scratches and dents, after which all of the functions of the device are tested (touch display, cameras, speakers and microphone, etc). Building upon an existing R&D prototype, my team operationalized this equipment, enhanced it to add new testing capabilities, and significantly improved the throughput of the system. In addition to being the lead designer and developer, I led a small team that converted a barely functional collection of robotic "cells" and made them work reliably and efficiently. My personal areas of focus are customer integration and configuration. This is key to our company's success as we move from having just one installation to several. Without a unified system to work across all sites, ongoing integration and maintenance costs make the system unprofitable.

Another area of focus of mine outside of robotics was to receive inbound devices for processing. Even a broken cell phone is often worth hundreds of dollars, so theft of devices is rampant in the industry. To help mitigate this problem, I designed and built two independent systems for device tracking. The first uses overhead video cameras to watch the human operators who open packages of incoming devices with 15-20 devices to a box. From the time that the seal on the box is cut open until the last device is removed for processing, the camera records every activity. The recordings are then uploaded to the cloud for post-processing using FFmpeg and made available for review by management.

The second way that I participated in reducing theft was to design and build a system that uses the weight of the incoming packages to determine if devices have been removed in-transit by the shipper. By using the weight of the package when it left the cell phone store and comparing that with the weight of the package when received at the robotic processing facility, we can easily determine if someone affiliated with the shipper has removed one or more devices from the package and then resealed it. This project required that I obtain the package weight from a high-speed "tunnel" scanner owned by our customer and upload it to AWS for comparison.

----- ----- -----
      * * *
----- ----- -----

**SDE/Architect Contractor:** CIBER, Inc (August 2011 - March 2014)  
**_Technology_**: HTML5/CSS3, Javascript/AJAX, Java, JSON, Sencha Touch, Adobe CQ5

Designed and implemented an extension for T-Mobile's QuikView application on a tablet computer (iPad and Android). QuikView is an internal program used by T-Mobile staff to resolve customer account issues and sell new cell phone service and handsets. For this particular application, portions of the QuikView program were rewritten to support tablet computers for use in the T-Mobile stores so that agents are no longer chained to a desktop computer to help customers on the sales floor.

Led two different initiatives to improve the <http://www.t-mobile.com> web site. In the first, I designed, built, and deployed a new system for code management and deployment to improve code quality, streamline development tasks, and save limited development resources. In the second, I co-designed a complete replacement for key portions of the site to convert it from .Net to Adobe CQ5. I also managed a team of developers and an external vendor to build and deploy the new code base. Both efforts required coordination with many teams inside our organization including testing, operations, and our business.

----- ----- -----
      * * *
----- ----- -----

**Principal Software Design Engineer**: Cloud Directory / Windows Live ID, [Microsoft Corporation](http://www.microsoft.com), Redmond, WA. (March 2009 - August 2011)  
**_Technology_**: C#, ASP.Net/MVC, C++, HTML5/CSS3, Javascript/AJAX, ATL, SOAP, WCF (limited), JSON.

Windows 8 is Microsoft's competitive answer to the iPad and Android tablet systems. As part of the Windows 8 development team, I designed and implemented key components of the contacts application. Built in HTML5 and Javascript, our goals were to rapidly build a robust contacts application for use by other applications and to prove out a new Windows development model where web application development is a first-tier development model for Windows.
The Windows Live Login Management Server (LMS) allows users to recover their Windows Live ID accounts if they have been compromised by an attacker or marked as suspect for spamming activities. The LMS guides the user through a set of questions to determine if they are both “human” and the legitimate owner of the account, then resets the account and helps the user to establish alternate authentication mechanisms to prevent future compromise. My role was to design the application and build the software. Upon delivery of the code, the number of co-owned accounts (those for which the attacker knows the password but the user is unaware) dropped significantly.

The Windows Live ID system is used by hundreds of millions of Internet users to log into Microsoft run properties such as Hotmail, Messenger, and Xbox Live. In an effort to modernize the system and reduce risk from using custom-built software, I spearheaded an investigation to convert core systems of the Windows Live ID login server from C++ to C#. I designed and built proof-of-concept code that allows existing components to be converted incrementally and new components to run in managed code as they are created using standard tools for .asmx files. Where components have been upgraded from native to managed code, the system allows for individual components to be failed back to previous versions in the event that the replacement components experience failure. I also demonstrated that the performance characteristics of the new system are on par with the existing code, which is important for a system that handles more than a billion login requests per day.

Also on the Windows Live ID system, I worked with another engineer to demonstrate how the main Windows Live ID login page could be converted from a POST request handler to an AJAX request to eliminate one of several redundant login paths. This work has led to the design of a system that allows browser clients to make smart decisions about where to route login requests. By making smarter choices, client login performance is improved significantly by servicing login requests geographically closer to the client (reduced latency). Routing to backup servers happens at the client when the primary servers are down, thereby improving service availability.

----- ----- -----
      * * *
----- ----- -----

**Principal Software Design Engineer / Lead SDE**: Windows Live Platform Incubation / Windows Live ID, [Microsoft Corporation](http://www.microsoft.com), Redmond, WA. (November 2007 - March 2009)  
**_Technology_**: C#, ASP.Net/MVC, C++, SQL Server, HTML/CSS, Javascript, Trident, smart card, Silverlight (limited).

The purpose of the Windows Live Platform Incubation team is to demonstrate the value of new services leveraging existing components of Windows Live (Live ID, Messenger, Hotmail, etc.) to drive increased numbers of Windows Live users and make them more "sticky" to the service. My role is as a key player in the development effort for two different products - FrameIt and StartKey.

[FrameIt](https://en.wikipedia.org/wiki/Windows_Live_FrameIt) is a photo aggregation service for wireless digital picture frames that combines photos from online services such as Spaces, Facebook, and SmugMug into a single RSS feed that is displayed on the picture frame. Additionally, the user may include other online content such as news or weather that turns their digital picture frame into a complete view of their online presence. I wrote a significant portion of the initial UI framework as well as much of the code that renders content from other sources.

[StartKey](https://en.wikipedia.org/wiki/StartKey) is a project designed to improve Windows Live ID security through the use of smart card technology and two-factor authentication. Delivered updates to the Windows Live ID service that allows hundreds of millions of users to upload their digital certificate to Windows Live and log in using their associated smart card. My role was to build a prototype with a small team of developers, and once we had a proof of concept ready then incorporate this work into the Live ID service.

----- ----- -----
      * * *
----- ----- -----

**Principal Software Architect / Principal Program Manager**: Display Advertising Platform, [Microsoft Corporation](http://www.microsoft.com), Redmond, WA. (June 2006 - October 2007)  
**_Technology_**: C#, C++, SQL Server, HTML/CSS.

As a member of the Display Advertising Platform team, I had three primary responsibilities. First, I led a small team of engineers, designing and coding prototype applications for new advertising concepts for both the Internet as well as out-of-home advertising. We identified new areas of opportunity, secured management approval to build proof-of-concept software and devices, created prototypes, and presented technology demonstrations. In addition to working within my own workgroup, we built strong working relationships outside of our team which generated additional support for our activities.

In my second role, I performed confirmatory technical due diligence on major acquisitions that are made by Microsoft of other advertising software companies. Leveraging my overall experience in the software industry, I evaluated the technical value of companies that we planned to purchase based on their overall architecture, strength of technical talent, security vulnerabilities, and use of third- party technologies. Based on these evaluations, I created recommendations that were used to justify the final purchase decision and price, including any remediation steps that needed to be taken to protect Microsoft's interests. I participated in the acquisition of [ScreenTonic](https://news.microsoft.com/2007/05/03/microsoft-acquires-mobile-advertising-pioneer-screentonic/#sm.00000hnesumcgkfbjtrnftydwpjwq) (mobile phone advertising) and the [$6.1 billion acquisition of aQuantive, Inc](https://news.microsoft.com/2007/05/18/microsoft-to-acquire-aquantive-inc/#sm.00000hnesumcgkfbjtrnftydwpjwq) (advertising agency), the largest acquisition ever by Microsoft as of that date.

In my third and final role, I evaluated patent pre-disclosures related to new advertising concepts. I made my recommendation of both the business value and novelty of each idea, and negotiated as necessary to push through the best ideas on a limited patent budget.

----- ----- -----
      * * *
----- ----- -----

**Software Developer**: Centelex Corporation, Kent, WA. (June 2003 - December 2015)  
**_Technology_**: PHP, MySQL, Apache, Bash, HTML/CSS, Javascript/AJAX, JSON, XML.

With my business partner, we provide contract programming services in both ASP.Net/Windows and PHP/Linux. I also co-created the TimeSolver staff scheduling service used by businesses throughout the US to automatically schedule their employees to work shifts based on work requirements and employee availability. My contributions included the core design and programming of the web site UI (traditional and AJAX), authentication methods, billing and payment systems, database design, and data replication.

----- ----- -----
      * * *
----- ----- -----

**Visiting Instructor**: [Seattle Pacific University](http://www.spu.edu), Seattle, WA. (September 2002 - June 2003)  
**_Technology_**: C++, C#, ASP.Net.

I filled a vacant teaching position on a temporary, one year appointment. I instructed students in the following topics: CSC1230 - Problem Solving and Programming, CSC2430 - Data Structures I, and CSC4800 - Advanced Topics in Computing. The CSC4800 course introduced students to web programming using Microsoft ASP.NET and the .NET Framework. I was active in the search for a PhD candidate to permanently fill my position.

----- ----- -----
      * * *
----- ----- -----

**Software Development Manager**: [MSN Shopping](https://news.microsoft.com/2000/12/05/msn-eshop-becomes-no-1-shopping-portal-on-the-web/#sm.00000hnesumcgkfbjtrnftydwpjwq), [Microsoft Corporation](http://www.microsoft.com), Redmond, WA. (April 2000 - August 2002)  
**_Technology_**: C#, VB, ASP.Net, SQL Server, HTML/CSS, Javascript, NT services.

My role as development manager was to lead the technology effort on the eShop platform. I evaluated proposals for new features and provided rough cost estimates. I guided the scheduling of new work, and ensured that the tasks undertaken by my team were sufficient for the time allocated. I evaluated new technology for inclusion into our platform, and approved key architectural decisions for the platform. I worked with all the members of my team to improve their professional skills, as well as their understanding of the needs of our business so that they could make the appropriate technology trade-offs. I also worked with other teams both inside and outside of my group to communicate our needs and understand theirs. I contributed code to the platform, built tools to aid in the overall development process, and both triaged and fixed bugs.

----- ----- -----
      * * *
----- ----- -----

**Lead Software Design Engineer**: [Auto PC](https://news.microsoft.com/1998/01/08/microsoft-announces-auto-pc-pc-companion-powered-by-windows-ce-2-0/#sm.00000hnesumcgkfbjtrnftydwpjwq), [Microsoft Corporation](http://www.microsoft.com), Redmond, WA. (April 1999 - March 2000)  
**_Technology_**: C++, devices.

As a lead software developer for the Auto PC team, I led the effort to bring wireless technologies to our platform. I designed and developed a technology for coordinating data and voice connections on a single device such as a cell phone. I also led the development of our POP3 based email solution.

----- ----- -----
      * * *
----- ----- -----

**Lead Software Design Engineer**: Internet Bill Delivery and Payment Team ([Transpoint](http://www.wsj.com/articles/SB95066625630836681)), [Microsoft Corporation](http://www.microsoft.com), Redmond, WA. (October 1996 - April 1999)  
**_Technology_**: C++, SQL Server, ODBC, HTML/CSS, NT services, event logging, perfmon.

I designed and developed software for presenting and paying bills over the Internet. I led the development of the core technology for our service center where all of the billing and payment information was stored. I wrote our database connector (wrapping ODBC) and many of our middle tier objects using C++. I also developed our security object and used it to develop a standardized framework for our web client. I led the development of our ASP-based web client until it could be handed off for cleanup and branding. I built much of our common library code, including code-authoring tools for event logging and perfmon counters. I also developed a technology for caching COM automation objects called from within an ASP page. I designed and developed the core database structures in SQL Server. In addition to my duties as a lead, I also worked with Program Management and Test to manage the schedule for the entire service center. I served as a member of our triage team to ship the final product and as a member of our launch team that was chartered with deploying our service.

----- ----- -----
      * * *
----- ----- -----

**Software Design Engineer**: Commerce Server Group, [Microsoft Corporation](http://www.microsoft.com), Redmond, WA. (June 1995 - October 1996)  
**_Technology_**: C++, SQL Server, ODBC, DCOM, named pipes, HTML/CSS

I designed and developed retail shopping software that allows customers to place retail hard-good orders via the Internet. Using an ISAPI DLL, NT services, and named pipes, I created an infrastructure using VC++ for retrieving data that was posted to a specific URL, passed it to a service that processed the data (using some components which came when we acquired [eShop](https://news.microsoft.com/2000/12/05/msn-eshop-becomes-no-1-shopping-portal-on-the-web/#sm.00000hnesumcgkfbjtrnftydwpjwq)), and returned a newly generated HTML page back to the browser. I also designed and developed retail shopping server components that used MSN mail as a transport. These components connected directly to the MSN mail servers, retrieved mail messages that contained order information, and processed the content. They logged the order request in a SQL Server database and created new messages that were sent to the appropriate merchant with their specific order information.

----- ----- -----
      * * *
----- ----- -----

**Independent Software Consultant**: Kent WA (January 1995 - June 1995)  
**Computer Systems Manager**: [Charlie's Produce](http://www.charliesproduce.com), Seattle, WA. (November 1993 - January 1995)  
**Computer Analyst**: [SYSCO](http://www.sysco.com), Kent, WA. (March 1992 - October 1993)  
**Computer Systems Manager**: Maly's, Grand Rapids, MI. (April 1989 - November 1991)  
**Computer Programmer**: [Granco-Clark](http://www.grancoclark.com), Belding, MI. (April 1988 - April 1989)  
**Programmer/Analyst**: Ann Arbor Computer, Division of [Jervis B. Webb](https://en.wikipedia.org/wiki/Jervis_B._Webb_Company), Ann Arbor, MI. (May 1987 - April 1988)
