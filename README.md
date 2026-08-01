# Anshul Kumar

**Full Stack & Distributed Systems Engineer**

[Email](mailto:anshullakra8@gmail.com) • [LinkedIn](https://www.linkedin.com/in/anshulkumar07/) • [GitHub](https://github.com/anshullakra007) • [Codeforces](https://codeforces.com/profile/anshullakra8) • [LeetCode](https://leetcode.com/u/anshullakra8/)

---

## About

I am an engineer focused on building scalable, high-performance backend systems and infrastructure. I enjoy tackling complex architectural problems, from designing custom database clones to developing robust remote code execution engines.

Currently pursuing my B.Tech in Computer Science Engineering (**CGPA: 9.11/10.0**) at Vellore Institute of Technology (VIT), Bhopal (Expected June 2027). 

* **Core Focus:** Distributed systems, backend architecture, and algorithmic efficiency.
* **Current Goal:** Pushing high-throughput system boundaries and advancing in competitive programming.

## Education

**Vellore Institute of Technology (VIT), Bhopal** — *B.Tech in Computer Science and Engineering* (Sep 2023 - Jun 2027)
* **CGPA:** 9.11/10.0
* **Coursework:** Object-Oriented Programming, Data Structures & Algorithms, Operating Systems, Computer Networks, DBMS, Distributed Systems, System Design.

## Technical Expertise

* **Languages:** Java (JDK 21), C++ (STL), JavaScript (ES6+), Python, SQL, C
* **Backend & Systems:** Spring Boot 3, FastAPI, Node.js, Express, Docker, Microservices, Raw Sockets, Multithreading, TCP/IP, Concurrency (`ConcurrentHashMap`, `ThreadPoolExecutor`)
* **Frontend & Web:** React.js, Next.js, Node.js, Socket.io, Tailwind CSS, WebSockets, REST APIs
* **Data Analytics & AI:** Python (Pandas), Google Gemini API, ChromaDB (Vector DB), Recharts
* **Tools:** Git, GitHub, Linux, Postman, VS Code

## Open Source Contributions

**[redis / jedis](https://github.com/redis/jedis)** *(Official Redis Java Client)* | **[STATUS: OPEN PR #4645](https://github.com/redis/jedis/pull/4645)**
* **Pull Request:** `fix(cluster): prevent lock-inversion deadlock in MultiNodePipelineBase (#4557)`
* Implemented a thread-safe fix in `MultiNodePipelineBase` to resolve a critical multi-threading lock-inversion deadlock ([Issue #4557](https://github.com/redis/jedis/issues/4557)).
* Eliminated eager connection borrowing during command appending to break hold-and-wait conditions under high-concurrency multi-node environments.
* Authored a deterministic concurrency integration test using `CyclicBarrier` and strict connection mocks.

**[TheAlgorithms / Java](https://github.com/TheAlgorithms/Java)** *(200k+ Star Open Source Algorithms Library)* | **[STATUS: MERGED PR #7544](https://github.com/TheAlgorithms/Java/pull/7544)**
* **Pull Request:** `Add Concurrent Merge Sort Implementation`
* Engineered a high-performance multi-threaded Concurrent Merge Sort algorithm using Java's `ForkJoinPool` and recursive task splitting to maximize CPU utilization on multi-core architectures.

## Featured & Technical Projects

**1. [Distributed Code Engine](https://github.com/anshullakra007/Distributed-Code-Execution-Engine)** | [Live Demo](https://distributed-code-execution-engine.vercel.app/) — *Java, Spring Boot, Docker, React*
* Architected a remote code evaluation API running Python, C++, and Java concurrently in isolated Docker containers with a **100% execution success rate** under parallel load testing.
* Engineered asynchronous process management with Java `ProcessBuilder`, accelerating runtime pipelines to **130+ req/sec** with sub-**70 ms** mean response latency.

**2. [MiniRedis (Multi-threaded TCP Store)](https://github.com/anshullakra007/MiniRedis)** | [Live TCP Server](https://miniredis.onrender.com) — *Java (JDK 21), Raw Sockets, Concurrency*
* Engineered a concurrent in-memory key-value storage engine from scratch over raw TCP sockets, benchmarking at a peak throughput of **94,600+ ops/sec**.
* Orchestrated thread-safe data consistency across **500 concurrent client connections** using `ConcurrentHashMap` and fine-grained locking, stabilizing P99 latencies at **3.2 ms** with a **0.00% error rate**.

**3. [Sentinel AI](https://github.com/anshullakra007/sentinel-ai)** | [Live Demo](https://huggingface.co/spaces/anshullakra8/sentinel-ai) — *Python, FastAPI, ChromaDB, Google Gemini LLM, Docker*
* Built an AI-powered observability platform that ingests production crash logs, performs semantic code retrieval via ChromaDB, and generates structured root-cause analyses and patch diffs with Gemini.
* Designed an asynchronous FastAPI telemetry pipeline with crash deduplication and vector search to reduce diagnosis latency for recurring production incidents.

**4. [ReconAI (FinTech Operations Dashboard)](https://github.com/anshullakra007/ReconAI)** | [Live Demo](https://frontend-fawn-five-21.vercel.app/) — *Python, FastAPI, React, Pandas, Gemini*
* Designed an automated data reconciliation pipeline processing **5,000+ synthetic payment gateway transactions** with a peak throughput of **420.16 req/sec** and P99 latency of **38.63 ms**.
* Automated root-cause analysis (RCA) on failed transaction batches by integrating the Gemini LLM, guaranteeing a **100% resolution success rate** under concurrent load testing.

**5. [FinTech Churn & Impact Analyzer](https://github.com/anshullakra007/fintech-churn-analyzer)** | [Live Demo](https://fintech-churn-analyzer.onrender.com) — *Python, Streamlit, Random Forest, Gemini API*
* Engineered an AI operational CRM and analytics dashboard to quantify and mitigate revenue at risk from payment gateway failures and technical debt.
* Implemented a Random Forest classifier to predict customer churn probability and utilized Gemini LLM to automatically draft personalized retention outreach campaigns.

**6. [SyncDraw](https://github.com/anshullakra007/SyncDraw)** | [Live Demo](https://sync-draw-eight.vercel.app/) — *React.js, Node.js, Socket.io, WebSockets*
* Built a collaborative whiteboard web application featuring zero-latency multi-user synchronization over a Pub/Sub WebSocket architecture.
* Engineered optimized Socket.io event broadcasting to transmit canvas coordinates instantly with minimal network payload overhead across connected clients.

**7. [L7 Load Balancer](https://github.com/anshullakra007/LoadBalancer)** | [Live Demo](https://loadbalancer-sgfp.onrender.com) — *C++, Multi-threading, TCP/IP, HTTP Server, Lock-free Atomics*
* Engineered a custom L7 Reverse Proxy distributing traffic across backend servers using Round Robin and Least Connections routing algorithms.
* Utilized lock-free Atomic counters and multi-threaded worker pools to eliminate synchronization bottlenecks under concurrent connection spikes.

**8. [System Design Learning Platform](https://github.com/anshullakra007/system-design-learning-platform)** | [Live Demo](https://system-design-learning-platform.vercel.app/) — *React.js, Node.js, Express, Tailwind CSS*
* Developed a comprehensive interactive platform for engineering students to master scalable System Design architectures and distributed systems patterns.
* Structured real-world architectural blueprints, caching strategies, and database sharding paradigms into interactive visual study modules.

**9. [CodeLens AI](https://github.com/anshullakra007/codelens-ai)** | [Live Demo](https://codelens-ai-ixqc.onrender.com/) — *Python, FastAPI, React.js, Google Gemini Flash, Docker*
* Built an automated code review agent that audits code snippets for time and space complexity bottlenecks, catches bugs, and generates refactored solutions.
* Designed an asynchronous inspection pipeline powered by Gemini Flash that delivers sub-second refactor recommendations and complexity breakdowns.

## Achievements & Competitive Programming

<table align="center" border="0" width="100%">
  <tr>
    <td width="50%" align="center">
      <a href="https://codeforces.com/profile/anshullakra8">
        <img src="https://codeforces-readme-stats.vercel.app/api/card?username=anshullakra8&theme=dark" alt="Codeforces Stats" />
      </a>
    </td>
    <td width="50%" align="center">
      <a href="https://leetcode.com/u/anshullakra8/">
        <img src="https://leetcard.jacoblin.cool/anshullakra8?theme=dark&font=Inter&ext=activity" alt="LeetCode Stats" />
      </a>
    </td>
  </tr>
</table>

* **Codeforces:** Attained **Pupil** rank (Peak Rating: **1289**). Secured global rank **2185** in Educational CF Round 190.
* **LeetCode:** **1450** contest rating.
* Mastered **360+ DSA problems** across both platforms using C++ (STL), resolving **118 Medium and Hard** challenges.

## Certifications

* **AWS Certified Solutions Architect – Associate** (Amazon Web Services)
* **Networking Basics** (Cisco)
* **Cyber Security Analyst** (IBM Career Education Program)
* **Blockchain and its Applications** (NPTEL / IIT Madras)
