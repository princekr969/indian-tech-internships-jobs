# IDFC FIRST Bank — Application Engineer (Internship + FTE) Preparation Guide

> Comprehensive placement prep dossier for the **IDFC FIRST Bank – Application Engineer (Internship + Full-Time Employment)** opportunity (On-Campus 2026–27 batch).
>
> Compiled from official IDFC FIRST Bank disclosures, GeeksforGeeks interview experiences, Glassdoor reports, LinkedIn engineer profiles, and Alion tech-stack analytics. Last updated: **07 Oct 2026**.

---

## 1. Company Snapshot

| Field | Detail |
|---|---|
| Legal Name | IDFC FIRST Bank Limited |
| Founded | **18 December 2018** (merger of erstwhile IDFC Bank + Capital First) |
| Headquarters | IDFC FIRST Bank Tower, C-61 G Block, Bandra-Kurla Complex, Bandra (E), Mumbai – 400 051 |
| MD & CEO | Mr. V. Vaidyanathan (ex-ICICI Bank retail head; led the Capital First transformation) |
| Type | Universal Private Bank (Retail + MSME + Rural + Corporate + Wealth + Credit Cards) |
| Tagline / Vision | "Always You First" — Ethical, Digital, Social Good Banking |
| Scale (as of Mar 2026) | ~38 M customers • 1,147 branches • 60,000+ cities/towns/villages • ₹2.94 L Cr deposits • ₹2.90 L Cr advances |
| Listed | BSE & NSE |
| Tech DNA | Cloud-native, microservices, event-driven, AI/ML-heavy. Digital banking, mobile, UPI, payments, lending, wealth, CRM. |

### Origin Story (why it matters in interviews)
- **1997** — IDFC Limited set up to finance Indian infrastructure (post Rakesh Mohan Committee).
- **2014** — RBI in-principle banking licence.
- **2015** — IDFC Bank launched by demerger.
- **2018 (18 Dec)** — Merged with Capital First (an NBFC founded by Vaidyanathan post-Warburg Pincus MBO). **First ever NBFC + Bank merger in India.**
- **Today** — Universal bank with a strong retail franchise.

> **Interview hook:** When asked *"Why IDFC FIRST Bank?"* — anchor on the **retail transformation story** (90% wholesale → 60%+ retail today), NBFC-to-Bank DNA, and the cloud-native tech rebuild that makes it one of the most engineering-driven private banks in India.

---

## 2. The Role You Are Applying For

Pulled directly from the on-campus announcement:

| Parameter | Detail |
|---|---|
| Company | IDFC FIRST Bank |
| Role | **Application Engineer — Internship + Full-Time Employment** |
| Eligible Branches | **Core CSE & IT only** |
| Internship Window | **January – June** (6 months, 8th semester) |
| Internship Stipend | **₹40,000 / month** |
| FTE Start | **July onwards** (subject to successful internship + selection) |
| Fixed Pay | **₹14 LPA** |
| Joining Bonus | **₹2 Lakh (one-time)** |
| Variable Pay | **15% of Fixed** |
| Effective CTC | ~**₹18.1 LPA** (14 + 2 + 2.1) |
| Work Locations | **Chennai / Hyderabad / Bengaluru / Mumbai** (based on org need) |
| Min Academic Score | **60% in 10th, 12th & Graduation** (or 6.0 CGPA) |
| Active Backlogs | **Not allowed at any stage** |

### What "Application Engineer" actually means at IDFC FIRST
A multi-year LinkedIn scan shows the role typically maps to a **Java/Go Backend Developer on the digital banking platform** — building microservices for payments, onboarding, lending, CRM, KYC, fraud, cards, mobile/Internet banking. Recent JD language used by IDFC for similar profiles:

> *"Design and develop scalable, secure, highly available backend systems using Java (Spring Boot) and/or Go. Architect microservices, REST APIs, event-driven systems, and distributed applications."*

So: **expect backend-heavy interviews** with strong emphasis on Java/Spring Boot, DB, SQL, OS/CN, system design and project deep-dive.

---

## 3. Selection Process — End-to-End Map

Different campuses report slightly different round counts. Treat the following as the **canonical 4-round structure**, which is what most recent (2024–25) experiences converge on:

```
┌────────────────────────────────────────────────────────────────────┐
│                     IDFC FIRST BANK – Application Engineer          │
│                         Selection Funnel (On-Campus)                 │
└────────────────────────────────────────────────────────────────────┘

  Pre-Placement Talk (PPT)
         │
         ▼
  ┌──────────────────────────────────────────┐
  │ Round 1: Online Assessment (HirePro)     │  Aptitude + Tech MCQs + 2 Coding
  │   Cut-off: relative ranking, no negative │  ~90 minutes
  │   ~20-25% shortlisted                    │
  └──────────────────┬───────────────────────┘
                     ▼
  ┌──────────────────────────────────────────┐
  │ Round 2: Technical Interview – 1 (TI-1)  │  15–90 min (panel variability)
  │   DSA + Core CS (OOP/DBMS/OS/CN) +      │
  │   Resume projects + on-spot coding      │
  └──────────────────┬───────────────────────┘
                     ▼
  ┌──────────────────────────────────────────┐
  │ Round 3: Technical Interview – 2 (TI-2)  │  60–90 min
  │   System design / LLD + DB schema design │
  │   Resume deep-dive + tech stack choices  │
  └──────────────────┬───────────────────────┘
                     ▼
  ┌──────────────────────────────────────────┐
  │ Round 4: HR / Managerial Round           │  15–45 min
  │   Behavioural, situational, location,   │
  │   salary, joining, motivation            │
  └──────────────────┬───────────────────────┘
                     ▼
              Final Offer (LOI → Offer → Internship → FTE)
```

> *A few campuses run only 3 rounds (merge Tech-2 + HR) or extend to 5 rounds (add an online pre-screen round or a final Tower-Head round). Plan for 4 rounds; budget for 5.*

---

## 4. Online Assessment (Round 1) — Complete Breakdown

**Platform:** HirePro (most common) — same platform used for TCS, Cognizant, Infosys etc., so familiar UI.
**Total Duration:** ~90 minutes (split across sections).
**Negative Marking:** Usually **none** — attempt everything.
**Camera Proctoring:** Yes (webcam + mic). Face must be visible.

### Section-wise Structure (canonical)

| # | Section | Questions | Time | Topics | Difficulty |
|---|---|---|---|---|---|
| 1 | **Aptitude** | 15 MCQs | 20 min | Quantitative Maths, Logical Reasoning, Pattern/Series | Easy–Medium |
| 2 | **Technical MCQs** | 20 MCQs | 25 min | SQL, MS Excel, Programming basics (C/Java/Python output), Pseudo-code / Flowchart output, DBMS fundamentals, OS, CN basics, Statistics | Easy–Medium |
| 3 | **Coding** | 2 problems | 45 min | One DSA (Tree/Array/String), one easy array/matrix/string | Easy–Medium (LeetCode Easy–Medium) |

> *Some batches add a Verbal section (20 MCQs, 15 min) and a separate C/Java specific section. The structure is fluid — expect 3–4 sub-sections.*

### Aptitude — what to expect
- Percentages, profit/loss, ratios, time–work–speed, mixtures, simple & compound interest.
- Number series, coding–decoding, blood relations, seating, syllogisms, Venn diagrams, probability basics.
- ~70% Quant, ~30% Reasoning.

### Technical MCQs — high-frequency topics
- **SQL** — `SELECT`, `WHERE`, `GROUP BY`, `HAVING`, `JOIN` (INNER/LEFT/RIGHT), sub-queries, ORDER BY, LIMIT, DELETE/UPDATE syntax. Expect 5–7 SQL MCQs.
- **Programming output** — predict output of small C / Java / Python snippets (loops, conditionals, recursion, type casting, string ops, exception flow).
- **OOP basics** — pillars, overloading vs overriding, abstract class vs interface.
- **DBMS** — ACID, normalisation (1NF/2NF/3NF), keys, indexing basics.
- **OS** — process vs thread, deadlock conditions, paging, memory.
- **CN** — OSI layers, TCP vs UDP, HTTP vs HTTPS, IP addressing.
- **MS Excel** — VLOOKUP, pivot tables, formulas.
- **Pseudo-code / Flowchart** — given a block of pseudo-code or a flowchart, what does it output?

### Coding — what to expect
- One problem on **trees** (e.g., max level sum, traversal, BFS/DFS) — easy-medium.
- One **array / string / matrix** problem — easy.
- Constraints usually small enough for O(n) / O(n log n). Focus on **clean code + all test cases passing**.

> **Tip (from selected candidates):** *"If you can't solve both, make sure at least one passes all test cases. Partial coding > no coding."*

### Sample Coding Questions (verified from past OA reports)

| # | Problem | Type | Hint |
|---|---|---|---|
| 1 | Maximum Level Sum of Binary Tree | Tree / BFS | Compute sum per level, return max. LeetCode #1161. |
| 2 | Egg-pickup from trays using hash map | Array / Simulation | Track remaining eggs per tray. |
| 3 | Balanced Parentheses (without using stack) | String / Two-pointer | Use a counter trick. |
| 4 | Sort a string without built-in sort | String | Manual sorting (selection/bubble). |
| 5 | First 1 in Sorted Binary Array | Binary Search | Standard BS, then single-pass variant. |
| 6 | Two Sum | Hash Map | Optimal O(n). |
| 7 | Find Missing & Repeating Number | Math / Array | XOR trick. |
| 8 | Reverse Linked List / Detect Cycle | Linked List | Standard LeetCode #206 / #141. |
| 9 | Squares of Sorted Array | Two-pointer | LeetCode #977. |
| 10 | Fibonacci Verification (optimised space) | Math / DP | O(1) space using rolling vars. |

### Shortlisting math
> From **VIT Vellore 2024** — 595 shortlisted for OA out of 3,147 applicants → 131 cleared → 62 from Vellore → 15 to next → 7 final offers.
> **Approximate funnel:** 100 applicants → ~20 in OA → ~7 in TI-1 → ~3 in TI-2 → ~1 offer.
>
> *Funnel varies by campus; CGPA cutoffs are often applied during application screening itself.*

---

## 5. Technical Interview – 1 (Round 2)

**Duration:** 15–90 minutes (huge variance by panel — some panels ask 1 DSA, others go deep for an hour).
**Mode:** Microsoft Teams (virtual) or in-person on campus.
**Composition:** 1 interviewer, occasionally 2 (one asks, one observes).

### Flow

```
Intro (1–2 min) ─▶ Resume Walkthrough (3–5 min) ─▶ DSA / Live Code (10–30 min)
                ─▶ Core CS Theory (10–20 min) ─▶ Project Discussion (5–10 min)
                ─▶ Candidate Questions (2–3 min)
```

### What they typically ask

| Area | Frequency | Example prompts |
|---|---|---|
| **DSA / Live coding** | 🔥 Always | "Solve this on the editor — Two Sum." "Brute force first, then optimise." "What's the time and space complexity?" |
| **Resume / Projects** | 🔥 Always | "Explain your final year project end-to-end." "Why this tech stack? What alternatives did you consider?" "What was your individual contribution?" |
| **OOP** | 🔥 Always | "Explain the 4 pillars of OOP with examples." "Compile-time vs run-time polymorphism — code it." "Abstract class vs Interface — when to use which?" |
| **DBMS / SQL** | 🔥 Always | "Normalise this schema to 3NF." "Write a query to find the top 3 customers by transaction volume using window functions." "ACID — explain with a banking example." |
| **OS** | Frequent | "What is a deadlock? List the 4 conditions." "Paging vs Segmentation." "Process vs Thread with an example." |
| **CN** | Frequent | "TCP vs UDP." "What happens when you type a URL into a browser?" "HTTP vs HTTPS — handshake deep dive." |
| **Light System Design** | Sometimes | "Design the schema for a parking lot / hotel booking / library / Instagram-Lite." |

### DSA questions that have actually been asked
- Two Sum (optimal hash-map approach)
- Find missing & repeating number
- Balanced parentheses (with and without stack)
- Reverse / cycle-detect in linked list (Floyd's algorithm)
- Squares of sorted array (two-pointer)
- Modified coin change (every denomination used at least once)
- Maximum level sum of binary tree
- Merge intervals
- Sort a string without built-in sort
- Find first 1 in sorted binary array (BS, then single-pass variant)
- Lift class — implement a `move()` method
- Highest playing card from `"Rank-Suit"` strings (string parsing)
- Java OOP class implementation (Drink vending, Battleship)

### Pro tips from previous candidates
> *"They care more about your approach and explanation than the exact answer. Always speak your thinking out loud."*
>
> *"If you freeze on a question, ask clarifying questions and propose a brute force — they'll guide you."*
>
> *"Resume projects are not optional — be ready to draw the data flow / schema on a shared screen."*

---

## 6. Technical Interview – 2 (Round 3)

**Duration:** 60–90 minutes (sometimes up to 2 hours for deep panels).
**Composition:** 1–2 interviewers, panel can include a senior engineer / manager / "Tower Head".

### Focus areas

1. **System Design / LLD (Low-Level Design)** — this is the marquee of Round 2.
2. **Database schema design + normalisation** (up to 3NF/BCNF).
3. **Resume deep-dive** — project architecture, design choices, alternatives, trade-offs.
4. **Cloud + DevOps** — if you list AWS/Azure/GCP on resume, be ready.
5. **Tech-stack specific questions** — Spring Boot, Java internals, Microservices, Kafka, Docker/K8s.
6. **Banking domain awareness** — payments, KYC, fraud detection, scalability, concurrency in transactions.
7. **Rapid-fire technical questions** at the end (panels vary).

### System Design prompts that have actually been asked

| # | Prompt | What they want |
|---|---|---|
| 1 | Design a **Hotel Management System** | ER diagram, tables, APIs, normalisation, indexing, room booking flow. |
| 2 | Design **BookMyShow**-like ticket booking | Concurrency control for seat locking, transactions, ACID, locking strategies. |
| 3 | Design a **Parking Lot System** | Classes, design patterns (Strategy, Factory), state transitions. |
| 4 | Design a **University Academic Tracking System** | Students, courses, grades, attendance — schema + APIs. |
| 5 | Design **Instagram Lite** | Feed, posts, likes — client → API → DB → cache (Redis) → CDN. |
| 6 | Design an **SMS Sending Service** | Queue-based, retry, dead-letter, rate-limiting, observability. |
| 7 | Design a **Logging System** that stores logs for 1 year | File rotation, compression, archival, retention jobs, no cloud. |
| 8 | Implement a **Lift class** with `move()` | OOP design — observer pattern, state machine. |

### SQL / DB prompts that have actually been asked
- Write a query to find the **top customer per week** using `RANK()` / `ROW_NUMBER()` window functions.
- How to **prevent simultaneous booking of the same seat** — pessimistic lock vs optimistic lock vs Redis distributed lock.
- Given a `customer`, `orders`, `product` schema — retrieve product name + customer name for orders placed today.
- Paginate a large table 100 rows at a time.
- SQL vs NoSQL — when to use which for a banking system.
- Normalise a sample schema to 3NF, justify each step.

### If you mention Spring Boot / Microservices on resume (very likely to be asked)
- Why Spring Boot over plain Spring?
- `@SpringBootApplication` annotation breakdown.
- What is dependency injection? Types (constructor, setter, field).
- Spring Boot starters — auto-configuration.
- REST controller vs REST repository.
- Actuator endpoints.
- `application.properties` vs `application.yml`.
- How does the embedded Tomcat start?
- Maven vs Gradle — which do you prefer?

### If you mention AWS / Cloud on resume
- EC2, S3, RDS basics.
- IAM, VPC, subnets.
- Lambda vs EC2.
- How would you deploy a Spring Boot app to AWS?
- Beanstalk vs ECS vs EKS — when to use which.

### Banking-domain awareness (subtle but valuable)
- **KYC** (Know Your Customer) — Video KYC, eKYC, Aadhaar/PAN verification.
- **Payments** — UPI, IMPS, NEFT, RTGS, card networks.
- **Lending** — credit underwriting, default prediction, NBFC vs Bank models.
- **Fraud detection** — anomaly detection, velocity checks, ML models.
- **Compliance** — RBI guidelines, PCI-DSS, data localisation.
- **Concurrency in transactions** — ACID, isolation levels, optimistic vs pessimistic locking, deadlocks.

---

## 7. HR / Managerial Round (Round 4)

**Duration:** 15–45 minutes.
**Composition:** 1–2 interviewers — usually an HR rep + a business manager / Tower Head.

### Canonical questions

| Category | Questions |
|---|---|
| **Opening** | "Walk me through your resume." / "Tell me about yourself." (Use **Present–Past–Future** formula.) |
| **Motivation** | "Why IDFC FIRST Bank?" / "Why banking?" / "Why not a pure tech company?" |
| **Strengths & Weaknesses** | "3 strengths and 1 weakness." (Pick a real, non-trivial weakness with mitigation.) |
| **Projects** | "Explain your best project — what was YOUR specific contribution?" |
| **Behavioural / STAR** | "Tell me about a challenge you solved." "A time you worked in a team." "A time you failed." |
| **Scenario** | "How would you handle a missed deadline?" "A disagreement with a teammate?" "A production bug at 3 AM?" |
| **Banking scenario** | "If you had to divide long customer reviews into positive/negative, how would you do it?" (Expected: **sentiment analysis / NLP**.) |
| **Location & Relocation** | "Are you open to Chennai / Hyderabad / Bengaluru / Mumbai?" (Be honest — they will honour your preference but tag you accordingly.) |
| **Compensation** | "Are you aware of the CTC structure? Any questions on the offer?" |
| **Career** | "Where do you see yourself in 3–5 years?" |
| **Closing** | "Any questions for us?" (Always ask **2–3 smart questions** — about the team, the tech stack, training, growth path.) |

### Smart questions to ask the HR / manager
1. "What does the first 6 months of the Application Engineer role look like in terms of projects?"
3. "Which business tower would I likely be placed in — payments, lending, mobile banking, CRM?"
4. "What's the engineering culture like — stack ownership, on-call, code review practices?"
5. "How does the internship → FTE conversion evaluation work?"
6. "Are there cross-location rotations or is the role location-locked?"

---

## 8. Tech Stack at IDFC FIRST Bank — What to Learn

Based on **Alion's analysis of 39 job postings over the last 12 months** and senior engineer LinkedIn profiles, here's the actual tech stack used by IDFC FIRST Bank today:

### Primary Languages (in priority order for this role)

| Language | % of postings | Why it matters |
|---|---|---|
| **Python** | 72% | Data engineering, ML, scripting, FastAPI services. |
| **SQL** | 51% | Every backend role touches DBs — must be fluent. |
| **Java** | 26% | The **core backend** language for digital banking platform. **You should know this.** |
| **JavaScript** | 15% | Node.js for some services, frontend teams. |
| **Go** | 10% | Increasingly used for high-throughput microservices. |

> **Heads-up:** Although Python tops the postings (because of data/ML roles), the **Application Engineer** role is firmly in the **Java/Spring Boot + Microservices** track. Prioritise Java.

### Backend Frameworks
- **Spring Boot / Spring Cloud** — primary
- **Hibernate / JPA**
- **Micronaut** (used in core banking rebuild)
- **FastAPI** (for Python services)
- **Node.js + Express**
- **GraphQL** (used alongside REST)

### Databases
- **MySQL, PostgreSQL** (primary OLTP)
- **Oracle** (legacy + lending)
- **MongoDB** (NoSQL for some services)
- **Redis, Aerospike** (caching)
- **DynamoDB** (on AWS)
- **Snowflake** (data warehouse)
- **HBase, BigQuery**

### Cloud & DevOps
- **AWS** (54% — primary cloud)
- **Azure** (36%), **GCP** (28%)
- **Docker, Kubernetes** (28%+)
- **Jenkins, Git, CI/CD**
- **Terraform** (likely)

### Messaging & Streaming
- **Apache Kafka** — heavily used for event-driven architecture
- **RabbitMQ** — for some async workflows
- **Spark / pySpark** — for data pipelines

### AI / ML
- **PyTorch, TensorFlow** — fraud detection, credit scoring, recommendation
- **LangChain, BERT, LoRA, LLMs** — chatbots, document AI
- **Scikit-learn**

### Observability
- **Grafana, Prometheus, Thanos, Alertmanager** (metrics)
- **Jaeger** (tracing)
- **ELK Stack / Splunk** (logging)

### Architecture Patterns in production at IDFC
- **Microservices** (Java/Spring Boot, Go)
- **Event-Driven Architecture** (Kafka)
- **REST APIs + GraphQL**
- **Cloud-native, containerised (Docker + K8s)**
- **Change Data Capture (Debezium)** for data sync
- **CQRS / Event Sourcing** (in some domains)
- **PCI-DSS** compliance baked into design

### Recommended learning order (if you have ~6 weeks)

```
Week 1-2  │ Java core (OOP, Collections, Generics, Exceptions, Streams, Java 8+ features)
          │ SQL (joins, window functions, CTEs, indexing, query plans)
Week 3    │ Spring Boot (REST APIs, JPA/Hibernate, dependency injection)
          │ DSA patterns (arrays, strings, linked list, stack, tree)
Week 4    │ Microservices basics + Kafka fundamentals
          │ OS + CN theory revision
Week 5    │ System Design (LLD: Parking Lot, Hotel, Lift, BookMyShow; HLD: Instagram, SMS service)
          │ 2 of your resume projects → polish + add schema + tech rationale
Week 6    │ Banking domain basics + behavioural prep + mock interviews
```

---

## 9. Topic-wise Preparation Checklist

### ✅ Must-do (high weightage)
- [ ] **SQL** — Window functions (`RANK`, `ROW_NUMBER`, `DENSE_RANK`, `LAG`, `LEAD`), CTEs, all JOIN types, GROUP BY + HAVING, sub-queries, indexes.
- [ ] **OOP** — 4 pillars + compile-time vs run-time polymorphism + abstract class vs interface + SOLID principles.
- [ ] **DSA** — Two Sum, Reverse LL, Cycle Detection (Floyd), Balanced Parens, Squares of Sorted Array, Tree Level Sum, Merge Intervals, Binary Search variants.
- [ ] **Resume projects** — Be ready to explain architecture diagram, tech stack choices, database schema, and your individual contribution for **every project**.
- [ ] **System Design (LLD)** — Parking Lot, Hotel Management, BookMyShow, Lift, Logger.
- [ ] **HR answers** — Self-intro (Present-Past-Future), Strengths/Weaknesses, Why IDFC FIRST Bank, Where do you see yourself.

### ✅ Should-do
- [ ] **OS** — Process vs Thread, Deadlock (4 conditions + prevention), Paging, Virtual Memory, CPU scheduling.
- [ ] **CN** — OSI/TCP-IP layers, TCP 3-way handshake, HTTP vs HTTPS, DNS, what happens when you type a URL.
- [ ] **DBMS** — ACID, Normalisation (1NF/2NF/3NF/BCNF), Indexing, Transactions, Isolation Levels.
- [ ] **Spring Boot basics** (only if mentioned in resume).
- [ ] **Cloud basics** (only if mentioned in resume).

### ✅ Nice-to-have
- [ ] Kafka fundamentals.
- [ ] Docker / Kubernetes basics.
- [ ] AWS services — EC2, S3, RDS, IAM.
- [ ] Banking domain awareness — KYC, UPI, Payments, Lending, Fraud.
- [ ] Microservices patterns — Circuit Breaker, Saga, Service Discovery.

---

## 10. Likely Interview Question Bank

### Coding / DSA (top 15)
1. Two Sum — optimal hash-map approach + complexity.
2. Find the missing and repeating number in an array.
3. Balanced parentheses — with and without using a stack.
4. Reverse a linked list (iterative + recursive).
5. Detect cycle in a linked list (Floyd's algorithm).
6. Longest substring without repeating characters (sliding window).
7. Squares of a sorted array (two-pointer).
8. Modified coin change — every denomination used at least once.
9. Maximum level sum of a binary tree (BFS).
10. Merge intervals.
11. First occurrence of `1` in sorted binary array (BS → single-pass variant).
12. Fibonacci verification (O(1) space).
13. Sort a string without built-in sort.
14. Highest playing card from `"Rank-Suit"` strings.
15. Implement a Lift class — `move()` method (OOP).

### OOP (top 10)
1. Explain the 4 pillars of OOP with code examples.
2. Abstraction vs Encapsulation vs Polymorphism vs Inheritance.
3. Abstract class vs Interface — when to use which.
4. Compile-time vs Run-time polymorphism — code both.
5. Overloading vs Overriding.
6. Method overloading — can we overload `main()`?
7. Why are Strings immutable in Java?
8. How does garbage collection work in Java/Python?
9. SOLID principles — quick explanation with examples.
10. Design a `Drink` class with quantity management + custom exception — Java code.

### DBMS / SQL (top 10)
1. Explain ACID with a banking transaction.
2. Normalise this schema to 3NF.
3. Write a query with `JOIN + GROUP BY + HAVING`.
4. `INNER JOIN` vs `LEFT JOIN` vs `RIGHT JOIN` vs `FULL OUTER JOIN`.
5. Primary key vs Unique key — differences.
6. What are indexes? When do they hurt performance?
8. Transactions and isolation levels — explain with examples.
9. Write a query to find the **top 3 customers** with highest purchases using a window function.
10. SQL vs NoSQL — when to use which for a banking transaction system.

### OS (top 8)
1. Process vs Thread.
2. 4 conditions of deadlock — how to break each.
3. Paging vs Segmentation.
4. Virtual memory concept.
5. Thrashing — what causes it, how to fix.
6. CPU scheduling algorithms (FCFS, SJF, RR, Priority) — pros/cons.
7. Difference between `fork()` and `exec()`.
8. Mutex vs Semaphore.

### CN (top 8)
1. OSI vs TCP/IP model.
2. TCP vs UDP — when to use which.
3. HTTP vs HTTPS — TLS handshake.
4. What happens when you type a URL into a browser? (full flow)
5. DNS resolution — iterative vs recursive.
6. CDN — how it works.
7. Public vs Private IP.
8. REST vs SOAP.

### System Design (top 8)
1. Design a Hotel Management System.
2. Design BookMyShow seat booking — concurrency control.
3. Design a Parking Lot.
4. Design Instagram Lite (feed + likes).
5. Design an SMS Sending Service.
6. Design a Logging System (1-year retention, no cloud).
7. Design a Lift class — `move()`.
8. Design schema for a Library Management System.

### HR (top 10)
1. Tell me about yourself. *(Use Present-Past-Future formula)*
2. Why IDFC FIRST Bank?
3. 3 strengths and 1 weakness.
4. Where do you see yourself in 3 years?
5. Tell me about a challenge you solved.
6. A time you worked in a team and a time you disagreed with a teammate.
7. How do you handle pressure / missed deadlines?
8. Any questions for us?
9. Are you open to relocation?
10. Why should we hire you?

---

## 11. Preparation Resources

### Coding Practice
- **LeetCode** — focus on Easy + Medium tagged **Amazon, Adobe, Microsoft** for App-Eng level.
- **GeeksforGeeks** — "IDFC FIRST Bank Interview Experience" tag has 11+ verified reports.
- **HackerRank** — IDFC FIRST Bank posts assessments here occasionally.
- **InterviewBit** — Java + SQL topic tracks.

### Core CS
- **GeeksforGeeks** — OOP, DBMS, OS, CN subject-wise pages (gold standard for India).
- **JavaTpoint** — Spring Boot tutorials (free).
- **TutorialsPoint** — DBMS normalisation guide.

### System Design
- **Gaurav Sen (YouTube)** — HLD/LLD playlist, India-context examples.
- **SudoCODE (YouTube)** — beginner-friendly LLD in Java/C++.
- **Workat.tech** — Indian interview-focused LLD/HLD practice.
- **Hello Interview** — premium but excellent for LLD.

### Banking Domain (light read)
- RBI official site — UPI, KYC, digital banking guidelines.
- IDFC FIRST Bank Annual Report — for vision, scale, and tech strategy.

---

## 12. Tips from Previous Selected Candidates

> *"Solve at least one coding problem fully with all test cases. Even partial credit is a big differentiator."* — GeeksforGeeks 2024

> *"They asked about every single project on my resume. Be ready to draw the architecture."* — VIT Vellore 2024

> *"Even if you don't know an answer, explain your approach. They reward communication over correctness."* — LinkedIn, Muthu Pavithra 2026

> *"System design at the LLD level — Parking Lot, Lift, BookMyShow — was asked in Round 3. Practice with classes, not microservices."* — Glassdoor 2024

> *"Spring Boot + Microservices questions only come if you mention them on resume. Don't fake skills."* — NIT 2025

> *"The interviewers were friendly — it's okay to ask clarifying questions and propose a brute force. They'll guide you to optimal."* — NIT 2022

---

## 13. Day-of-Interview Checklist

- [ ] Laptop charged + charger + stable internet (for virtual rounds).
- [ ] Webcam + mic tested. Quiet room, no background noise.
- [ ] HirePro login tested the night before.
- [ ] Resume printed (in-person) or open on a second screen (Teams screen-share).
- [ ] 1–2 projects ready with architecture diagram, schema, and your contribution highlighted.
- [ ] Cheat-sheet of SQL window functions, OOP pillar summary (last-minute glance only).
- [ ] Bottle of water, calm mind.
- [ ] Reach 30 min early for in-person; join 10 min early for Teams.

---

## 14. Quick FAQ

**Q. Is the internship guaranteed, or is it conditional?**
A. The internship is part of the FTE offer. You intern Jan–Jun, and FTE starts in July subject to successful internship completion and selection.

**Q. Can I skip the internship and join directly?**
A. No. The internship is built into the offer and you cannot opt out.

**Q. Will I be bonded?**
A. No separate service bond was disclosed in the announcement. Standard notice period applies once you join FTE.

**Q. Is the CTC ₹14 LPA or ₹18 LPA?**
A. **Fixed ₹14 LPA + ₹2 Lakh Joining Bonus + 15% Variable.** Effective on-paper CTC is ~₹18.1 LPA, but in-hand will be closer to ₹14 LPA + variable depending on rating.

**Q. Can I choose my location?**
A. You can express a preference (Chennai / Hyderabad / Bengaluru / Mumbai). Final allocation depends on org need.

**Q. Is there a Group Discussion (GD) round?**
A. Not for Application Engineer. (Some other IDFC programs like FIRST LEAP have GD; the tech track uses 1-on-1 interviews.)

**Q. Are branches other than CSE/IT eligible?**
A. **No.** Only Core CSE and IT are eligible per the announcement. ECE has been allowed in some past cycles (e.g., NIT), but the 2026 announcement restricts to CSE + IT.

**Q. What if my CGPA is 59.9%?**
A. You won't clear the eligibility screen. No negotiation.

**Q. Will they ask puzzles?**
A. Occasionally in HR round. Standard puzzles — 8 balls + balance scale, 100 doors, etc. Don't over-prepare.

**Q. What if I don't know Spring Boot but know Django/Flask?**
A. They won't downgrade you for using Python in projects — but they will ask Java/Spring Boot questions in the interview if the role is on a Java stack. Brush up on at least Spring Boot basics.

---

## 15. One-page Summary Card

```
┌───────────────────────────────────────────────────────────────────┐
│            IDFC FIRST BANK — Application Engineer                 │
│                  One-Page Cheat Sheet                             │
├───────────────────────────────────────────────────────────────────┤
│ Role         : Application Engineer – Intern + FTE                 │
│ Stipend      : ₹40k/month  (Jan–Jun)                             │
│ CTC (FTE)    : ₹14L Fixed + ₹2L JB + 15% Var ≈ ₹18.1L CTC        │
│ Locations    : Chennai / Hyd / BLR / Mumbai                       │
│ Eligibility  : CSE/IT only • 60% in 10/12/Grad • No backlogs      │
├───────────────────────────────────────────────────────────────────┤
│ Rounds       : (1) OA HirePro  (2) TI-1  (3) TI-2  (4) HR/Mgr    │
│ OA = Apti(15) + Tech MCQ(20) + 2 Coding (45min)                   │
│ Core topics  : SQL/OOP/DBMS/OS/CN/DSA/SysDesign/Projects          │
│ Primary stack: Java + Spring Boot + Kafka + AWS + Microservices   │
├───────────────────────────────────────────────────────────────────┤
│ Top 5 things to revise TONIGHT:                                   │
│  1. Two Sum + Reverse LL + Balanced Parens + Tree Level Sum       │
│  2. SQL window functions (RANK, ROW_NUMBER) + JOINs               │
│  3. OOP 4 pillars + compile vs run-time polymorphism              │
│  4. LLD: Parking Lot / Hotel / Lift (classes, not microservices)   │
│  5. "Why IDFC FIRST Bank?" — retail-banking-DNA + cloud-native    │
└───────────────────────────────────────────────────────────────────┘
```

---

*Sources: GeeksforGeeks IDFC FIRST Bank interview tag (2022–2025), Glassdoor (Application Engineer filter), LinkedIn (engineer profiles + interview posts), Alion IDFC FIRST Bank tech stack report, official IDFC FIRST Bank careers page, IDFC FIRST Bank investor presentations.*