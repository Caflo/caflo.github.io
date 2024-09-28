---
layout: page
title: About me
permalink: /about/

---
![Safety](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTHsFd-MpI-rxYX7I_nWCa-qL8AhUPrYIYhTA&s)

# Personal information

- Nationality: **Italian** 

# Skills

<table align="center">
  <tr><td><b>Malware analysis</b></td><td><b>Windows internals</b></td><td>Penetration testing</td></tr>
  <tr><td>Low-level programming</td><td>Shell scripting</td><td>Linux system administration</td></tr>
  <tr><td>Mantainable software design</td><td><b>Research-oriented</b></td><td>Team/autonomous worker</td></tr>
</table>

---

# Experience

#### November 2022 ~ *present*: **R&D Security Engineer** @ Leonardo 
- **Security software development**
	- Software development of server-side logic of an EDR system
		- Handling data related to agent telemetry in a centralized manner
		- DevOps & deploying (CI/CD, virtualized environments)
		- Load testing 
	- Developed a minimal plugin-library to flexibly extend server functionalities
	- Used tools: 
		- `CMake`, `Conan` for project & dependencies management
		- `Postman` for testing
		- `Docker` & `Portainer` for deploying & CI/CD
		- Python with `Locust`, `PrometheusDB`, `Kibana` for load tests & simulation of 1000+ clients
- **Malware analysis**
	- x86 reverse engineering using FlareVM, IDA and other malware analysis tools
	- Reverse-engineered a commercial C2 framework
		- Studied exotic injection techniques and evasion capabilities of generated samples
		- Studied immutable characteristics of the file in search of particular data, blocks of instructions and artifacts that could make the file suspicious
	- Output: yara rule that allows the file to be detected by scanning instruments

#### Summer 2020: Full-stack developer @ AFA Systems
- **Project management and development**
	- PHP (frontend, backend)
	- Responsive dashboard to check online active users & access rules

- **SQL Database management**
	- Query time optimization, cutting up to half of the initial query time of the company
	- Linux environment

---

# Education

- **Cybersecurity - master degree** - Oct 2020 - Jan 2023
	- Sapienza Univeristy of Rome 
	- Thesis: *"The Many Facets of Malware Evasion and Cutting-edge Dynamic Binary Instrumentation Tools to Deal With Them"*
		- Researching and applying countermeasures for anti-debug, anti-VM/sandbox and anti-DBI evasions by developing a tool using DynamoRIO framework
		- PoC: a C++ logger “with steroids” reporting activity of "benign look-a-like" evading samples, revealing hidden malicious behavior
		- Scanning area: in-memory, syscalls, APIs, exceptions, asm instructions



- **Computer Engineering - bachelor's degree** - Sep 2016 - Mar 2020
	- Alma Mater Studiorum - Bologna
	- Thesis: A Python software library for dataset generation based on linear models

---

# Certifications
- **Maldevacademy**: *Certificate of Completion*
	- Content: C/C++ malware development, windows internals, C2 development, cutting-edge malware evasion mechanisms, cross-compilation Linux -> Windows

---

# Languages
- *Italian* - **Native speaker**
- *English* - B2 level
