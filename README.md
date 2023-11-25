# Fauzaan
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&duration=2000&pause=1000&color=025EF7&multiline=true&width=435&height=95&lines=Software+and+Data+Engineer;Engineering+Backend+Systems)](https://git.io/typing-svg)

<br/>
<br/>

<p align="center">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=fauzxan&layout=donut&theme=transparent&show_icons=true"/>
</p>

<!--
<details>
  <image align="center" src="https://github-readme-stats.vercel.app/api/wakatime/?username=fauzxan" />
</details>
-->

<br/>

# Highlights

## Distributed Systems 🌐
Distributed Systems- like Blockchain, Cloud Services, P2P applications, etc. all function on a middleware that is built to be resilient and meet the requirements of a robust system, that appears singular to the user. 

Given below is a view of the distributed system middleware that is required to make a functional service like Amazon Web Services, Ethereum, Azure, etc. 

<p align="center">
  <img src="https://github.com/fauzxan/fauzxan/assets/92146562/9ad64859-fb05-43c0-b69a-e256291800f9" width="500">
</p>
The projects listed below target to implement a different section of the above middleware stack. 

### [Clocks, Causality and Leader Elections](https://github.com/fauzxan/distributed_systems)
Different systems may communicate at different times, and when this happens, there might be some inconsistency in the ordering of events at the two remote machines. 
The repository above discusses some key protocols to address this issue using Lamport's scalar and vector clocks. 

Additionally, many tasks done in a distributed system require a central-server-like capability to coordinate the events between multiple machines. The above repository also has an implementation of bully algorithm, which is a leader election algorithm based on some consensus among the peers. 

### [Distributed Mutual Exclusion Protocols](https://github.com/fauzxan/distributed_mutual_exclusion) 
Distributed systems sometimes access a part of the memory/ some resource that can only be accessed by atmost one computer at a time. Examples of such sensitive information includes distributed ledgers, shared documents, bank accounts, etc. 

The repository above implements three such protocols that are able to manage and grant access to locks to a machine on the network.

## Networking systems 🖥️

Networks, like most other communication critical systems operate based on a set of rules that are critical to ensuring 
1. Reliability
2. Scalability
3. Time sensitivity

The repositories below explore some of the protocols on the network application stack that are able to ensure the above properties.

### [Reliable Data Transfer Protocols](https://github.com/fauzxan/Reliable-Data-Transfer)
Messages sent over the _internet_ are divided into packets of information with a fixed number of bytes each. The protocols discussed in the above repository deal with how we can send these packets to ensure that 
1. whatever is sent is _actually_ received 
2. an appropriate labelled buffer is maintained so that missing packets are flagged
3. resend mechanisms in place at the transport layer to ensure reliable _blackbox_ protocol, to which you send a message, and you can rest easy knowing it has gone through 🙃

### [Application layer protocol - HTTP](https://github.com/fauzxan/Network-labs)
_The vanilla, the classic, the HTTP protocol itself 🚀_
Implementation of a simple application that uses the HTTP protocol, using REST API.

 ## ⚡ Technologies


<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=go,js,java,cpp,python,nodejs,aws,github,grafana,docker,mongodb,mysql,redis,postgres,postman,linux,jenkins,flask,fastapi)" />
  </a>
</p>

![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript)
![Nodejs](https://img.shields.io/badge/-Nodejs-black?style=flat-square&logo=Node.js)
![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=Python)
![React](https://img.shields.io/badge/-React-black?style=flat-square&logo=react)
![Java](https://img.shields.io/badge/-java-E34A86?style=flat-square&logo=java)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3)
![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript)
![MongoDB](https://img.shields.io/badge/-MongoDB-black?style=flat-square&logo=mongodb)
![Redis](https://img.shields.io/badge/-Redis-black?style=flat-square&logo=Redis)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql)
![MySQL](https://img.shields.io/badge/-MySQL-black?style=flat-square&logo=mysql)
![Docker](https://img.shields.io/badge/-Docker-black?style=flat-square&logo=docker)
![Amazon AWS](https://img.shields.io/badge/Amazon%20AWS-232F3E?style=flat-square&logo=amazon-aws)
![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github)

# 2023, wrapped 🚀
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://github.com/fauzxan/fauzxan/assets/92146562/106a3c3c-1623-431e-a560-596f4b85bf71" />
  </a>
</p>
