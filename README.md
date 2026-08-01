# Anshul Kumar

**Full Stack & Distributed Systems Engineer**

[Email](mailto:anshullakra8@gmail.com) • [LinkedIn](https://www.linkedin.com/in/anshulkumar07/) • [GitHub](https://github.com/anshullakra007) • [Codeforces](https://codeforces.com/profile/anshullakra8) • [LeetCode](https://leetcode.com/u/anshullakra8/)

---

## About

I am an engineer focused on building scalable, high-performance backend systems and infrastructure. I enjoy tackling complex architectural problems, from designing custom database clones to developing robust remote code execution engines.

Currently pursuing my B.Tech in Computer Science Engineering (**CGPA: 9.15/10.0**) at Vellore Institute of Technology (VIT), Bhopal (Expected June 2027). 

* **Core Focus:** Distributed systems, backend architecture, and algorithmic efficiency.
* **Current Goal:** Pushing high-throughput system boundaries and advancing in competitive programming.

## Education

**Vellore Institute of Technology (VIT), Bhopal** — *B.Tech in Computer Science and Engineering* (Sep 2023 - Jun 2027)
* **CGPA:** 9.15/10.0
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

**[TheAlgorithms / Java](https://github.com/TheAlgorithms/Java)** *(200k+ Star Open Source Algorithms Library)* | **[STATUS: OPEN PR #7544](https://github.com/TheAlgorithms/Java/pull/7544)**
* **Pull Request:** `Add Concurrent Merge Sort Implementation`
* Engineered a high-performance multi-threaded Concurrent Merge Sort algorithm using Java's `ForkJoinPool` and recursive task splitting to maximize CPU utilization on multi-core architectures.

## Featured & Technical Projects

**1. [Distributed Code Engine](https://github.com/anshullakra007/Distributed-Code-Execution-Engine)** | [Live Demo](https://distributed-code-execution-engine.vercel.app/) — *Java, Spring Boot, Docker, React*
* Architected a remote code evaluation API capable of compiling and running Python, C++, and Java concurrently in isolated Docker containers with a **100% execution success rate** under parallel load testing.
* Accelerated Python runtime pipelines to achieve a peak processing capacity of **130+ req/sec** with under **70 ms** mean response time.
* Implemented asynchronous process management using Java `ProcessBuilder` to handle heavy multi-threaded compilation workloads for C++ (g++ 17) and Java (JDK 21).

**2. [MiniRedis (Multi-threaded TCP Store)](https://github.com/anshullakra007/MiniRedis)** | [Live TCP Server](https://miniredis.onrender.com) — *Java (JDK 21), Raw Sockets, Concurrency*
* Engineered a concurrent in-memory key-value storage engine entirely from scratch, benchmarking at a peak throughput of **94,600+ ops/sec** over raw TCP sockets.
* Orchestrated thread-safe data consistency across **500 concurrent client connections** using `ConcurrentHashMap` and fine-grained locking, sustaining a **0.00% error rate**.
* Designed a custom TCP protocol with sub-millisecond mean execution delays (**0.6 ms**) and minimized context-switching overhead, stabilizing P99 latencies at **3.2 ms**.

**3. [Sentinel AI](https://github.com/anshullakra007/sentinel-ai)** | [Live Demo](https://huggingface.co/spaces/anshullakra8/sentinel-ai) — *Python, FastAPI, ChromaDB, Google Gemini LLM, Docker*
* Built an AI-powered observability platform that ingests production crash logs, performs semantic code retrieval using ChromaDB, and generates structured root cause analyses and patch recommendations with Gemini.
* Designed an asynchronous FastAPI telemetry pipeline with crash deduplication and vector search to reduce diagnosis latency for repeated incidents.

**4. [ReconAI (FinTech Operations Dashboard)](https://github.com/anshullakra007/ReconAI)** | [Live Demo](https://frontend-fawn-five-21.vercel.app/) — *Python, FastAPI, React, Pandas, Gemini*
* Designed an automated data reconciliation pipeline processing **5,000+ synthetic payment gateway transactions**.
* Benchmarked backend resolution logic using asyncio, achieving a peak throughput of **420.16 req/sec** and a P99 latency of **38.63 ms**.
* Automated root-cause analysis (RCA) on failed transaction batches by integrating the Gemini LLM, guaranteeing a **100% success rate** under concurrent load testing.

**5. [FinTech Churn & Impact Analyzer](https://github.com/anshullakra007/fintech-churn-analyzer)** | [Live Demo](https://fintech-churn-analyzer.onrender.com) — *Python, Streamlit, Random Forest, Gemini API*
* Engineered an AI-powered operational CRM and analytics dashboard designed to quantify and mitigate the cost of technical debt and payment gateway failures.
* Implemented a Random Forest classifier to predict customer churn probability and utilized Gemini LLM to draft personalized retention outreach campaigns.

**6. [SyncDraw](https://github.com/anshullakra007/SyncDraw)** | [Live Demo](https://sync-draw-eight.vercel.app/) — *React.js, Node.js, Socket.io, WebSockets*
* Built a collaborative whiteboard web application featuring zero-latency multi-user synchronization.
* Engineered a Pub/Sub WebSocket architecture using Socket.io to broadcast drawing coordinates instantly across connected clients.

**7. [L7 Load Balancer](https://github.com/anshullakra007/LoadBalancer)** | [Live Demo](https://loadbalancer-sgfp.onrender.com) — *C++, Multi-threading, TCP/IP, HTTP Server, Lock-free Atomics*
* Engineered a custom Reverse Proxy that distributes traffic across backend servers using Round Robin and Least Connections routing algorithms.
* Utilized lock-free Atomic counters and thread pooling to minimize synchronization overhead under concurrent connection spikes.

**8. [System Design Learning Platform](https://github.com/anshullakra007/system-design-learning-platform)** | [Live Demo](https://system-design-learning-platform.vercel.app/) — *React.js, Node.js, Express, Tailwind CSS*
* Developed a comprehensive interactive platform for engineering students to master scalable System Design architectures and distributed systems patterns.

**9. [CodeLens AI](https://github.com/anshullakra007/codelens-ai)** | [Live Demo](https://codelens-ai-ixqc.onrender.com/) — *Python, FastAPI, React.js, Google Gemini Flash, Docker*
* Built an automated, hyper-optimized code review agent that audits code snippets for time and space complexity bottlenecks, catches bugs, and generates refactored solutions.

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
