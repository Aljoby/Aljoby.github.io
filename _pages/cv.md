---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Sc in Computer Information Systems, Hashemite University, Jordan (1st Class Honours), 2008
* M.Sc. in Computer Engineering, Jordan University of Science and Technology, Jordan, 2013 
* Ph.D. in Computer Science, National University of Singapore, Singapore, 2020

Work experience
======
* Postdoctoral Research Fellow (Full-time) (Dec. 2020 - Present)
  * National University of Singapore
  * Research focus: Enabling In-Network Detection and Mitigation of Adaptive Link Flooding Attacks (LFA). This kind of attack is TCP-conforming under which the botnet sends a stealthy low-rate traffic regulated by TCP congestion control. We leverage the flexibility of SDN programmable data plane to defend against this attack via traffic engineering techniques.

* Research Intern (Part-time) (Aug. 2019 - Dec. 2019)
  * Advance Digital Sciences Center, University of Illinois at Urbana-Champaign (UIUC)
  * Gained knowledge about the cyber attack scenarios targeting the smart grid power system. Specifically, the attacks that could be launched against infrastructure of an electric power substation during GOOSE-based data transmission between substation’s IEDs.
  
Skills
======
* Languages (P4, Assembly, C, C++, Java, .NET, MATLAB)
* Web & DBMS (XML, HTML, PHP, JavaScript, SQLServer, MySQL)
* Microprocessors Simulators (SESC, WinDLX, XEEMO)
* Network Simulators (Scapy, Mininet, NS2, OMNET++)
* Platforms (Linux, Tofino, OpenDaylight, Brocade, Cisco, Docker, Analytics and ML)
* Microsoft ASP.NET (C#), Cisco CCNA, A+, BA-9111: Data Plane Development, Barefoot Networks Intel

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Student mentor, SIGCOMM 2021
* Student volunteer, ICNP 2016
* Reviewer for networking-related papers in (1) IEEE Transactions on Parallel and Distributed Systems (IEEE TPDS), (2) IEEE Journal on Selected Areas in Communications (IEEE JSAC), and (3) IEEE Transactions on Communications (IEEE TCOM)
