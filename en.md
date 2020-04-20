<img src="https://avatars3.githubusercontent.com/u/3495089" height="300" alt="[GitHub Avatar]" />

Oleg Strelnikov (43 y.o.)
=========================

Location: Volgograd, Russia  
E-mail: [oleg.strelnikov@gmail.com](mailto:oleg.strelnikov@gmail.com)  
Skype: [olegstrelnikov](skype:olegstrelnikov)  
GitHub: [https://github.com/olegstrelnikov](https://github.com/olegstrelnikov)  
Stackoverflow: [https://stackoverflow.com/users/3879237/oleg](https://stackoverflow.com/users/3879237/oleg)

Languages: Russian (native), English

Looking for remote working at Senior C++/C Engineer position. Expected salary $35/hour. Going to relocate to Montenegro during the further year

---

Professional skills and experience
----------------------------------

**Great skills** in C++03 / STL, C, C++11/14 (move semantics, threading, lambdas, variadic templates; reported [confirmed and fixed C++ standard breaks](https://developercommunity.visualstudio.com/users/145684/d6f204a3-5fcb-6a62-9bd2-25113c0f666a.html?itemsifollow) by Microsoft Visual Studio), OpenSSL (posted bug fix to [openssl request tracker](https://rt.openssl.org/Ticket/Display.html?id=3256&user=guest&pass=guest)), TLS/1.2, HTTP/1.1

**Operating Systems:** Linux/UNIX, Windows

**Development methodologies, technologies and tools:** Object-Oriented technologies, Test Driven Development (TDD), Design Patterns, Git, Jira, Jenkins

**Isolation, Virtualization and Clouds:** docker, VMware vSphere/ESXi, KVM, VirtualBox, AWS, Microsoft Azure

**Environments:** Eclipse (gcc), Microsoft Visual Studio

**Networking:** TCP/IPv4/IPv6, sockets, RFC protocols and algorithms, X.502, Kerberos, XML, REST

**APIs:** POSIX, Windows&nbsp;API

**Gaining skills:** Python, C++17/20, CUDA, OpenCV, AVX

**Other skills:** boost, multithreading, Linear Algebra and Matrix Analysis

**Former skills:**
- Java, Assembler (x86, x86_64, TMS320, i8080, i8051, Analog Device Blackfin (MSA)), C++/CLI, PHP, JavaScript, Fortran
- UML, eXtreme Programming (XP), Subversion (svn), Request Tracker, Review Board, Trac
- HTML, Web Services, UDDI, SOAP, Microsoft CryptoAPI
- .NET API
- Eigenvalue Decomposition (EVD) Algorithms, FPGA design, VLSI Design, Application-specific Processors (ASP) Design, Pseudo-Euclidean/Pseudo-Unitary Transformations, ASIC, SoC, Hardware/Software co-design, JTAG, VHDL/Verilog

---

Experience
----------

May 2011 — until now (9 years)  
[Virtana, Inc](http://virtana.com) (former Virtual Instruments, Inc - former LoadDynamiX, Inc - former SwiftTest, Inc)

The lead of the team developing the following protocols and APIs for the backend firmware:  
HTTP, HTTPS, Amazon S3, CDMI, OpenStack, Hadoop, TCP, IPv6, TLS/SSL

Involved into the following projects:
- [Workload Wisdom](https://www.virtana.com/products/workloadwisdom/) (WW)  
Senior software engineer / team lead (outsourcing)  
WW software is the automated workload acquisition, workload analysis, workload modeling, and workload performance analytics solution. It includes enterprise web-based UI, Windows-based frontend and Workload Generators.
The Workload Generators (appliances) are used to generate traffic based on workload models and access patterns that have been configured by WW enterprise. The appliances are purpose-built devices with a software and hardware architecture that has been specifically engineered to cost-effectively generate massive traffic loads that can test the performance and scalability limits of any storage subsystem, including the highest-end flash storage systems. Physically appliance is a Linux high-end machine with custom memory kernel-space driver, custom TCP/IP stack implementation, custom Ethernet 1/10/25/40/100 Gbps user space drivers, custom event-driven application library and custom application-level protocol implementations: NFS, CIFS, SMB, iSCSI, HTTP, HTTPS, Amazon S3, CDMI, OpenStack.  
My contribution is the development of HTTP, TLS, HTTPS and Amazon S3 protocols, some features of TCP, IPv4/IPv6 and Ethernet user-space driver. Details are provided in the Project Contributions section.

- [Cloud Migration Readiness](https://www.virtana.com/products/cloud-migration-readiness/) (CMR)  
Senior C engineer (outsourcing)  
CMR is the service helping successfully reduce the cloud migration complexity, right-size cloud configurations, and validate cloud performance. CMR defines four distinct phases: 1. *Discover* application workload characteristics and identify dependencies between compute, networking and storage elements. 2. *Profiling* - distillation of hundreds or thousands of workloads into a small set of representative synthetic workloads that accurately characterize performance. 3. Accurate *Playback* of representative synthetic workloads in the cloud to select cost-optimal configurations and placements without compromising workload performance. 4. *Monitor* actual workloads post migration to the cloud to identify any unforeseen performance or capacity issues.  
My contribution is the development of the backend playback (3rd phase) tool named getreal. It's a C multithreading cross-platform (windows and linux) application which generates CPU, RAM, networks and disk IO loads on the base of synthetic workloads passed as the input. Getreal uses low level Windows API and POSIX calls to generate the load and gather the statistics to feedback the generated load and prepare the report. Details are provided in the Project Contributions section.

---

September 2009 — until now (10 years)  
[Open Systems LLC](http://open-sys.org)

Senior software engineer  
C++ development, outsourcing

---

September 2009 — April 2011 (1 year 8 months)  
[Digital Loggers, Inc](http://digital-loggers.com)

Software engineer  
Was involved in 2 projects (software):
1. Power switch based on TI C2000. [US](http://appft.uspto.gov/netacgi/nph-Parser?Sect1=PTO2&Sect2=HITOFF&u=%2Fnetahtml%2FPTO%2Fsearch-adv.html&r=1&p=1&f=G&l=50&d=PG01&S1=13381958&OS=13381958&RS=13381958#top) ([copy at google drive](https://drive.google.com/open?id=0B8bu_Q9mXCC9MU1DYWJweVQtYnM)) and [WIPO](http://patentscope.wipo.int/search/en/WO2010129071) ([copy at google drive](https://drive.google.com/open?id=0B8bu_Q9mXCC9V3JjNHFoT1JMNk0)) patents are obtained (including firmware developed by me)
2. 8xT1 lines USB logger based on Analog Devices Blackfin BF548 DSP processor and DS26519 T1 transceiver. The program includes BF548 firmware and desktop USB driver and frontend (C#/MC++)

---

April 2009 — August 2009 (5 months)  
[SperaSoft](http://sperasoft.com)

Senior software developer  
Developing the mobile cross-platform framework to run platform-independent javascript applications at Windows Mobile, UIQ, S40. Was based on spidermonkey. Project included the eclipse plugin to develop applications called "mobics". Project was named HipLogic: [linkedin](https://www.linkedin.com/company-beta/409117?pathWildcard=409117) [crunchbase](https://www.crunchbase.com/organization/hiplogic)

---

Projects
--------

1. WW Workload Generator
2. Kerberos man-in-the-middle
3. Getreal
4. Advanced Test Runner (ATR)
5. WebMoney Exchanger Robo

---

Links
-----

- PhD Thesis: **Eigenvalue Decomposition (EVD) Algorithms** (in russian, [russian state library](http://dlib.rsl.ru/01002305713) [copy at google drive](https://drive.google.com/open?id=0B8bu_Q9mXCC9Q19KaTlpcWU4aU0))
- Co-Inventor of Russian Federation Patent # 2168760 **Egenvalues Calculation Device** (in russian, [russian patent office](http://www1.fips.ru/fips_servl/fips_servlet?DB=RUPAT&DocNumber=2168760&TypeFile=html%C3%A2%EF%BF%BD%EF%BF%BD) [copy at google drive](https://drive.google.com/open?id=0B8bu_Q9mXCC9QzIxVTdLSG9fc28))
- Registration certificate: Program "Imperia-2012" #2012618753 (in russian, [copy at google drive](https://drive.google.com/open?id=0B8bu_Q9mXCC9SkJ3cEpvbXJSN29YVDhDbjRHWi1oX2gzTElF)) / Database "Imperia-2012" #2012620994 (in russian, [copy at google drive](https://drive.google.com/open?id=0B8bu_Q9mXCC9b2dVY1ZhSWpHazk3MkRUY25nNGRQeVJhQjBR))
- Co-inventor of international (WIPO) patent # WO2010129071 ([WIPO](http://patentscope.wipo.int/search/en/WO2010129071) [Google Patents](http://www.google.ch/patents/WO2010129071A1) [copy at google drive](https://drive.google.com/open?id=0B8bu_Q9mXCC9V3JjNHFoT1JMNk0) / of US (USPTO) patent # US 20120112728 A1 ([USPTO](http://appft.uspto.gov/netacgi/nph-Parser?Sect1=PTO2&Sect2=HITOFF&u=%2Fnetahtml%2FPTO%2Fsearch-adv.html&r=1&p=1&f=G&l=50&d=PG01&S1=13381958&OS=13381958&RS=13381958#top) [Google Patents](http://www.google.com/patents/about?id=r1kOAgAAEBAJ&dq=54+ac+power&num=4&client=internal-uds&source=uds) [copy at google drive](https://drive.google.com/open?id=0B8bu_Q9mXCC9MU1DYWJweVQtYnM) / # US 8975787 B2 ([USPTO](http://patft.uspto.gov/netacgi/nph-Parser?Sect1=PTO1&Sect2=HITOFF&d=PALL&p=1&u=%2Fnetahtml%2FPTO%2Fsrchnum.htm&r=1&f=G&l=50&s1=8975787.PN.&OS=PN/8975787&RS=PN/8975787) [Google Patents](http://www.google.ch/patents/US8975787) [copy at google drive](https://drive.google.com/open?id=0B8bu_Q9mXCC9TEx4aUVNRk4zV28)) **REDUCED PARTS COUNT ISOLATED AC CURRENT SWITCHING AND SENSING**
