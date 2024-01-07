# Fauzaan
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&duration=2000&pause=1000&color=025EF7&multiline=true&width=435&height=95&lines=Software+and+Data+Engineer;Engineering+Backend+Systems)](https://git.io/typing-svg)

<p align="center">
  <!--<img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=fauzxan&layout=donut&theme=transparent&show_icons=true"/>-->
  <img align="center" src="https://api.githubtrends.io/user/svg/fauzxan/langs?time_range=one_year&loc_metric=changed&theme=classic"/>
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
📑[Lamport's original paper](https://lamport.azurewebsites.net/pubs/time-clocks.pdf)

Different systems may communicate at different times, and when this happens, there might be some inconsistency in the ordering of events at the two remote machines. 
The repository above discusses some key protocols to address this issue using Lamport's scalar and vector clocks. 

Additionally, many tasks done in a distributed system require a central-server-like capability to coordinate the events between multiple machines. The above repository also has an implementation of bully algorithm, which is a leader election algorithm based on some consensus among the peers. 

### [Distributed Mutual Exclusion Protocols](https://github.com/fauzxan/distributed_mutual_exclusion) 
📑[Distributed Mutual Exclusion protocols](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=448903fa04b096e85ef272acca9c768b9a8a26f2)

Distributed systems sometimes access a part of the memory/ some resource that can only be accessed by atmost one computer at a time. Examples of such sensitive information includes distributed ledgers, shared documents, bank accounts, etc. 

The repository above implements three such protocols that are able to manage and grant access to locks to a machine on the network. We also go over an analysis of each of their performance, which has been outlined in the PDF attached. 

### [DNS over Chord](https://github.com/fauzxan/dns-chord)
📑[Original Chord paper](https://pdos.csail.mit.edu/papers/chord:sigcomm01/chord_sigcomm.pdf)

📑[Findings report](https://github.com/fauzxan/dns-chord/blob/main/documentation/50_041_Distributed_Systems_Project.pdf)

Traditional DNS systems rely on a hierarchical system of servers which are queries recursively or iteratively. With chord, the DNS system can be implemented over a P2P network, where the nodes in the network themselves can store the data. Moreover, the authoritative server can be found within 1 hop at best, and at worst within 3 hops - offering a significant advantage over legacy DNS systems. The implementation above presents a study of a DNS-Chord implementation in terms of performance, and fault tolerance. 

### [IVY (Integrated shared Virtual memory at Yale)](https://github.com/fauzxan/ivy)
📑[IVY original paper](https://systems.cs.columbia.edu/ds2-class/papers/li-ivy.pdf)

Given above is an implementation of IVY - which is a shared memory system used by researchers at Yale. IVY is an excellent example of how the sequential consistency is implemented in real life, and this repository seeks to analyze it's performance over multiple scenarios described there. 

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

### [DaoNet](https://github.com/fauzxan/DaoNet)
DaoNet is inspired by [Riot Game's frame sync](https://technology.riotgames.com/news/determinism-league-legends-unified-clock) mechanism through a unified game clock. DaoNet seeks to extend these capabilities to a P2P network, where there is no central server to coordinate the interaction of the peers in the network. It navigates the presence of non-Byzantine faults in a P2P system and accounts for liveness constraint in multiplayer games.  

 ## ⚡ Technologies


<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=go,js,java,cpp,python,nodejs,aws,github,grafana,docker,mongodb,mysql,redis,postgres,postman" />
  </a>
</p>
<p align="center">
  <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=linux,jenkins,flask,fastapi" />
  </a>
</p>

<!--
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
-->
# 2023, wrapped 🚀
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://github.com/fauzxan/fauzxan/assets/92146562/850c399a-471b-4c11-8234-dbd25bd5c015" />
  </a>
</p>
