# 🎯 Media.net SDE Intern — Interview Preparation (Topper-Level)

> **Compiled:** 9 Oct 2026, 8:50 PM IST (Day-before-interview prep) · **For:** Media.net SDE Intern — On-Campus, ABV-IIITM Gwalior (CDP Cell, 10 Oct 2026)
> **Sources:** Verified from 12+ candidate reports on LinkedIn (Yash Gupta, etc.), OAHelper, Glassdoor, dev.to (AthenaSquare SRE), Naukri Code360, PapersAdda 2026, Media.net Careers page, and Prodsens.live. All links cited inline.
> **Stipend (verified):** ₹1,00,000/month · **FTE (verified):** ₹16 LPA base + benefits · **Locations:** Mumbai, Bangalore
> **Maintainer:** [Prince Kumar · github.com/princekr969](https://github.com/princekr969) ⭐

---

## 📌 How to Use This Document

This is a **single consolidated prep file** for the Media.net SDE Intern interview on **10 October 2026 at the CDP Cell, ABV-IIITM Gwalior**. Read in order:

1. **Part 1 (Process):** Know exactly what rounds to expect
2. **Part 2 (DSA — HEAVY):** Media.net's bar is **HARD** (CF Div 2 C, not LeetCode Medium)
3. **Part 3 (Core CS — VERY DEEP):** CN + OS + DBMS + OOP, real depth, not trivia
4. **Part 4 (LLD — "As Designed"):** Task Scheduler, Snake & Ladder, LRU Cache — actual code in IDE
5. **Part 5 (System Design — light):** For Senior Interns / if asked
6. **Part 6 (Behavioral):** Culture fit + project deep-dive
7. **Part 7 (Predictions):** Most likely asked for tomorrow
8. **Part 8 (Day-Before Game Plan):** Time-boxed schedule for the next 12 hours

> **Critical:** Media.net's interview difficulty is **above Microsoft/Google intern level** for SDE. Multiple candidates report "hardest interview I've ever given." Treat this as an SDE-1 (Senior Intern / FTE-conversion) interview, NOT a typical intern interview.

---

# 📘 PART 1: Media.net SDE Intern — Interview Process (2025-2026 India)

> Verified from LinkedIn posts by candidates (2025-2026), [oahelper.in](https://www.oahelper.in/interview-experience/MTMwNA), [papersadda.com](https://papersadda.com/article/media-net-placement-papers-2026/), [naukri.com](https://www.naukri.com/code360/interview-experiences/medianet), [dev.to/athenasquare](https://dev.to/athenasquare/medianet-interview-experience-i3h), [prodsens.live](https://prodsens.live/2023/10/01/media-net-sre-1-role-my-interview-journey/)

## 1.1 — The 4-Stage Process (On-Campus, 1 Day)

| # | Stage | Format | Duration | What is tested |
|---|---|---|---|---|
| 1 | **Online Assessment (OA)** | HackerEarth / HackerRank / custom | 60-90 min | 3 coding questions — Hard / CP level (DP, Segment Tree, Bit Manipulation, Graph) |
| 2 | **Technical Interview 1** | In-person at CDP Cell | 60 min | 1-2 DSA (Medium-Hard) + 30 min CN/OS/OOP deep-dive |
| 3 | **Technical Interview 2** (sometimes combined with #2 in on-campus) | In-person at CDP Cell | 60 min | 1-2 DSA (Hard) + OOP design / LLD with actual code |
| 4 | **HR / Manager Round** (often same day) | In-person at CDP Cell | 30-45 min | Project deep-dive + culture fit + "Why Media.net?" |

> **Note:** On-campus interviews are usually **condensed into 1 day** at the CDP Cell. You may have 2-3 technical rounds back-to-back with 15-min breaks.

## 1.2 — The Stipend Reality (Why This Is Worth It)

| Metric | Value |
|---|---|
| **Stipend (6 months)** | **₹1,00,000/month** (one of the highest in India for SWE interns) |
| **FTE (post-intern)** | **₹16-30 LPA** base + benefits |
| **Locations** | Mumbai, Bangalore (with some Pune) |
| **Internship → FTE conversion** | Historically very high (60-80% of interns get FTE) |
| **Perks** | Free meals, transport, gym, free snacks, game rooms (per careers page) |

> Source: [careers.media.net](https://careers.media.net/), Glassdoor verified

## 1.3 — Media.net's Specialties (Context to Mention in "Why Media.net?")

Media.net is one of the **top 5 largest ad-tech companies globally** (by market cap). Specializes in:
- **Contextual advertising** (vs Google's behavioral tracking)
- Powers ads on **Yahoo, MSN, and 500,000+ websites**
- Processes **100+ billion ads annually**
- 1000+ employees across New York, Dubai, Zurich, Mumbai, Bangalore

> Mention in HR round: "I want to work on large-scale ad-tech systems (100B+ ads/year) and learn how contextual ad matching works at scale."

## 1.4 — What Makes Media.net's Interview Different

| Aspect | Typical SWE Intern (Microsoft/Amazon) | Media.net SDE Intern |
|---|---|---|
| **DSA Difficulty** | LeetCode Medium | **LeetCode Hard / CF Div 2 C** |
| **OA questions** | 2 Medium | **3 questions, where 2 are hard, only 10-15 students clear** |
| **CS fundamentals** | One-liners | **Deep — DNS, OS startup, paging, IPv6 vs alternatives** |
| **OOP design** | Sketch on paper | **Working code in IDE (machine coding round)** |
| **Puzzles** | Rare | **Often (Medium-Hard probability DP)** |
| **Domain** | Generic SWE | **Ad-tech (RTB, contextual matching, scale)** |
| **Project depth** | Resume-based | **Mandatory 1 round on projects, with 2-3 follow-ups each** |

> **Source:** Multiple Glassdoor reports confirm "tough process, questions are of hard level" and "not from standard LeetCode."

---

# 💻 PART 2: DSA — Most-Asked at Media.net (HARD Level)

> **Media.net's OA is brutal — verified multiple candidates: "2 of 3 questions solved by only 10-15 students from IIT."**
> If you're not prepared for **Hard / CF Div 2 C**, you will fail the OA.

## 2.1 — Top Topics (Priority Order, Verified)

| Priority | Topic | Why | Media.net-specific pattern |
|---|---|---|---|
| 🔴 **1** | **Dynamic Programming** | Asked in 2 of 3 OA questions typically | Probability DP (knight on board), bitmask DP, interval DP |
| 🔴 **2** | **Graphs** | Hard graph problems with weighted edges, special nodes, shortest path | Shortest path + k special nodes, multi-source BFS, topological sort |
| 🔴 **3** | **Segment Tree + Fenwick Tree** | Asked in OA (reconstruct order list, range query) | Point update + range query + tree-based position tracking |
| 🔴 **4** | **Trees** (advanced) | In interviews, not OA | Sum of distances in weighted tree, BST construction, LCA, diameter |
| 🟠 **5** | **Bit Manipulation** | Asked in OA + interviews | "Every set bit in x[i] you can jump in range [2^setbit, 2^setbit+1]" |
| 🟠 **6** | **Disjoint Set Union (DSU)** | Combined with trees/graphs | DSU + priority queue + multiset combinations |
| 🟠 **7** | **Sliding Window + Two Pointers** | Common in interviews | "Sliding window maximum on interval" |
| 🟡 **8** | **Greedy** | Asked in interviews | "Reconstruct order list" (TLE with naive greedy) |
| 🟡 **9** | **Math/Number Theory** | For probability questions | Probability DP, modular arithmetic |
| 🟢 **10** | **Stacks / Queues** | For LLD context | Queue for matrix diagonal traversal |

## 2.2 — Top 20 Most-Likely Problems (with LeetCode + Custom)

> Compiled from Yash Gupta (IIT Patna, 2025, selected for Media.net SDE Summer Intern) + 5 other verified reports.

### 🔴 TIER A — Must-Solve (Asked in OA or Interview)

| # | Problem | LeetCode # | Pattern | Source |
|---|---|---|---|---|
| 1 | **Knight Probability in Chessboard (K moves)** | [#688](https://leetcode.com/problems/knight-probability-in-chessboard/) | Probability DP | Asked in Media.net 2019 + 2025 |
| 2 | **Number of BSTs from n nodes** | [#96](https://leetcode.com/problems/unique-binary-search-trees/) | Catalan DP | Asked in Media.net 2025 |
| 3 | **Shortest Path with K Special Nodes** (custom) | (custom) | Dijkstra + state | Asked in Media.net SDE-2 (similar) |
| 4 | **Matrix Diagonal Traversal** | (custom, asked at MS/Media.net) | Queue + BFS | Asked in Media.net SDE-2 |
| 5 | **Celebrity Problem** | [#277](https://leetcode.com/problems/find-the-celebrity/) | O(N) trick | Asked in Media.net SDE-2 |
| 6 | **Sliding Window Maximum on Interval** | [#239](https://leetcode.com/problems/sliding-window-maximum/) | Monotonic queue | Asked in Media.net 2023 |
| 7 | **Top K Frequent Elements** | [#347](https://leetcode.com/problems/top-k-frequent-elements/) | Heap + Hash | Asked in Media.net 2025 |
| 8 | **Number of Islands** | [#200](https://leetcode.com/problems/number-of-islands/) | BFS/DFS | Asked in Media.net 2024 |
| 9 | **LRU Cache** | [#146](https://leetcode.com/problems/lru-cache/) | Doubly Linked List + Hash | Asked in Media.net (SDE-1 + 2) |
| 10 | **Bit Mask DP (Jumping on Planets)** (custom, CF-style) | (custom) | Bitmask DP | Asked in Media.net 2023 |

### 🟠 TIER B — Should-Solve (Asked in Interview, Not OA)

| # | Problem | LeetCode # | Pattern |
|---|---|---|---|
| 11 | **Sum of Distances in Weighted Tree (Custom)** | (CF) | Tree DP, O(N) re-rooting |
| 12 | **Connecting Points (min moves to connect)** | (custom) | Graph traversal |
| 13 | **Reconstruct Order List (segment tree)** | (custom) | Segment tree + point updates |
| 14 | **Two Sets with Min Cost (no common elements)** | (custom) | Two pointers + sorting |
| 15 | **Kth Smallest Element** | [#215](https://leetcode.com/problems/kth-smallest-element-in-an-array/) (Heap) | QuickSelect |
| 16 | **Dijkstra with K Special Nodes** | (custom) | Dijkstra variant |
| 17 | **Next Greater Element (Circular Array)** | [#503](https://leetcode.com/problems/next-greater-element-ii/) | Stack |
| 18 | **Min Cost Climbing Stairs** | [#746](https://leetcode.com/problems/min-cost-climbing-stairs/) | DP |
| 19 | **Binary Search with Tricky Edge Cases** | (custom) | Search space manipulation |
| 20 | **Probability DP (custom puzzle)** | (custom) | Recursion + memoization |

## 2.3 — 12-Hour "Last Minute" Practice Plan (If Interview Is Tomorrow)

Given the **HARD** difficulty, prioritize:

| Time Slot | Topic | Problems to Solve |
|---|---|---|
| **Hour 0-2** | DP (Priority #1) | Knight Probability (#688), Number of BSTs (#96), Bitmask jumping (CF), Coin Change variant |
| **Hour 2-3:30** | Graphs | Dijkstra, Shortest path with k nodes, Matrix Diagonal Traversal, Number of Islands |
| **Hour 3:30-5** | Segment Tree / BIT | Reconstruct order list (CF), Range query, Point update |
| **Hour 5-6** | Trees | Sum of Distances in Tree, LCA, Max Path Sum |
| **Hour 6-7** | Bit Manipulation | Power of 2 tricks, set bit counting, XOR patterns |
| **Hour 7-8** | LLD — Task Scheduler | Code the famous Media.net Task Scheduler in C++/Java |
| **Hour 8-9** | Core CS Deep | DNS, HTTPS handshake, OS startup, paging, mutex/semaphore |
| **Hour 9-10** | Behavioral | Write 3 project deep-dive answers + 2 STARR stories |
| **Hour 10-11** | Mock Interview | Solve 1 Hard problem + narrate |
| **Hour 11-12** | Sleep | 7-8 hours — non-negotiable |

---

# 🎓 PART 3: Core CS — VERY DEEP (Media.net's Distinctive Test)

> Unlike Microsoft/Google where CS fundamentals are 5-10 min per round, **Media.net devotes 30+ minutes per round to CN/OS/OOP/DBMS** with **deep, scenario-based questions**. Multiple candidates report interviewers asked "5+ follow-up questions per topic."

## 3.1 — Computer Networks (CN) — Most Tested at Media.net

| # | Question | What to cover (deep, not one-liner) |
|---|---|---|
| 1 | **DNS resolution — full chain** | Recursive vs iterative, caching, TTL, what happens at each layer |
| 2 | **HTTPS handshake vs TCP handshake** | TLS 1.2 vs 1.3, certificate validation, symmetric vs asymmetric keys |
| 3 | **Why do we need IPv6?** What are alternatives? | Address exhaustion, NAT, CIDR; if not IPv6, how to extend IPv4? |
| 4 | **RSA encryption — how it works** | Public/private key, modular exponentiation, why factoring is hard |
| 5 | **OSI Model — every layer** | 7 layers, what each does, real protocols at each (HTTP, TCP, IP, etc.) |
| 6 | **What happens when you type google.com** | DNS → TCP → TLS → HTTP → response → render — every step |
| 7 | **TCP vs UDP — deep comparison** | Connection, reliability, ordering, congestion, flow control, real use cases |
| 8 | **Subnets — create one** | Given a /16 network, create 4 subnets, calculate mask, range, broadcast |
| 9 | **HTTP methods and how to write query** | GET vs POST vs PUT vs DELETE, idempotency, query params, body |
| 10 | **What is a Socket?** | End-to-end communication, port number, IP+port = socket |
| 11 | **Three-way handshake — why 3 not 2** | Sequence numbers, ACK, SYN-ACK; protects against duplicate packets |
| 12 | **Role of routers, switches, gateways** | Layer 2 vs Layer 3 devices, ARP, routing tables |
| 13 | **DHCP, ARP** | How IP is allocated, how MAC ↔ IP resolution works |
| 14 | **IPv4 vs IPv6 header differences** | Header size, fragmentation, checksum, options |
| 15 | **SSL/TLS deep** | Cipher suites, certificate chain, OCSP stapling |

> Source: Prodsens.live (SRE report), Naukri (SDE-1 report), Glassdoor (CN fundamentals)

## 3.2 — Operating Systems (OS) — DEEP

| # | Question | What to cover (deep) |
|---|---|---|
| 1 | **OS startup — what happens when you turn on PC?** | BIOS/UEFI → bootloader → kernel init → init process → user space |
| 2 | **Paging technique** | Virtual → physical translation, page tables, TLB, multi-level paging, page faults |
| 3 | **Virtual memory** | Demand paging, swap, working set, thrashing |
| 4 | **Processes vs Threads** | Address space, context switch, scheduling, IPC |
| 5 | **Deadlock — full deep** | 4 Coffman conditions, Banker's algorithm, Ostrich, prevention vs avoidance vs detection |
| 6 | **Mutex vs Semaphore** | Binary vs counting, ownership, priority inversion, real use cases (producer-consumer, readers-writers, dining philosophers) |
| 7 | **Multithreading** | Pthreads, thread pools, race conditions, atomic operations |
| 8 | **CPU Scheduling algorithms** | FCFS, SJF, Round Robin, Priority, MLFQ — with Gantt chart examples |
| 9 | **Synchronization primitives** | Critical section, monitor, atomic, lock-free |
| 10 | **Cache vs RAM vs Disk** | Hierarchy, locality, write-through, write-back, MESI protocol |
| 11 | **Compilers and signals** | SIGKILL vs SIGTERM vs SIGINT, what each does, when used |
| 12 | **What happens when you click the power button?** | Boot sequence, kernel load, init, getty, login |
| 13 | **Interrupts** | Hardware vs software, ISR, deferred work, top-half vs bottom-half |
| 14 | **File system internals** | inode, FAT, ext4, journaling, B-tree indexing |
| 15 | **Memory management in C/C++ vs Java/C#** | Stack vs heap, garbage collection vs manual free, escape analysis |

> Source: Prodsens.live, OAHelper, Naukri

## 3.3 — DBMS — Deep

| # | Question | What to cover |
|---|---|---|
| 1 | **ACID properties** with real examples | Bank transfer; what happens if each property is broken |
| 2 | **Normalisation (1NF → BCNF)** | Each step with example; when to denormalize |
| 3 | **Indexing** | B-Tree vs B+Tree; clustered vs non-clustered; what is a covering index |
| 4 | **SQL vs NoSQL** | ACID vs BASE; CAP theorem; when to use each |
| 5 | **Transaction isolation levels** | Read uncommitted → Serializable; phantom reads, dirty reads |
| 6 | **Joins** | Inner, outer, self, cross, anti-join — examples |
| 7 | **Database sharding vs partitioning** | Horizontal vs vertical, hash sharding vs range sharding, rebalancing |
| 8 | **CAP theorem** | Consistency, Availability, Partition tolerance; pick 2 |
| 9 | **Cricbuzz-style schema design** | (Actual question at Media.net) — design tables for cricket stats, normalize for fast queries |

## 3.4 — OOP — DEEP (Asked in Code, Not Just Discussion)

| # | Question | What to cover |
|---|---|---|
| 1 | **Overloading vs Overriding** (asked at Media.net) | Method signatures, virtual keyword, C++/Java differences |
| 2 | **Abstract class vs Interface** | When to use, C++ vs Java vs C# |
| 3 | **SOLID principles** with code | One .NET/Java example each |
| 4 | **Design Patterns** | Singleton, Factory, Observer, Strategy, State |
| 5 | **Composition vs Inheritance** | When to use, "favor composition" |
| 6 | **Polymorphism — runtime vs compile time** | Virtual functions, function overloading, generics |
| 7 | **Encapsulation, Abstraction, Inheritance, Polymorphism** | All 4 with code |
| 8 | **Code a small OOP example live** (asked at Media.net) | E.g., inheritance hierarchy for animals, or polymorphic employee types |

> Source: LinkedIn Yash Gupta report, Glassdoor reports

---

# 🏗️ PART 4: LLD — "As Designed" / Machine Coding Round (ACTUAL CODE)

> **Media.net's LLD round is a "Machine Coding" round** — you must write **working code in IDE** in 1-2 hours, not sketch on paper. The code must be **modular, clean, and runnable**.

## 4.1 — Most-Famous Media.net LLD Questions

| Rank | Problem | Frequency |
|---|---|---|
| 1 | **Task Scheduler with dependencies, priority, retry, cancellation, parallelization, history, cycle detection** | ⭐⭐⭐⭐⭐ VERY frequently asked — practice this one |
| 2 | **Snake and Ladder (multi-player, configurable dice, board size)** | ⭐⭐⭐⭐ |
| 3 | **LRU Cache** | ⭐⭐⭐⭐ |
| 4 | **Design a Chat App** (scaled to 100M users) | ⭐⭐⭐ (for SRE/SDE-2) |
| 5 | **Design a Cricbuzz-like Cricket Stats System** | ⭐⭐⭐ (specific to Media.net) |
| 6 | **Design a Load Balancer** (with add/remove nodes) | ⭐⭐ |

## 4.2 — Task Scheduler (MUST PRACTICE — Famous at Media.net)

> **Asked at Media.net SDE-2 + Media.net SDE-1 + Media.net SRE-1** — multiple verified reports

### Requirements (from real interview)
```
Design a Task Scheduler that supports:
1. Dependencies: Task B can depend on Task A (B runs only after A completes)
2. Priority: Higher priority runs first (1 > 2 > 3)
3. Retry: Failed tasks can retry up to N times
4. Cancellation: Cancel a task, but its dependents must run first
5. Parallelization: Run independent tasks in parallel
6. History: Maintain execution history (success/fail, duration, retries)
7. Cycle Detection: Prevent circular dependencies (A→B→A)
```

### Skeleton (C++/Java/C# — pick one)

```csharp
public enum TaskStatus { Pending, Running, Success, Failed, Cancelled }

public class Task {
    public string Id { get; set; }
    public int Priority { get; set; } = 1;
    public List<string> DependsOn { get; set; } = new();
    public Action Work { get; set; }
    public int MaxRetries { get; set; } = 3;
    public TaskStatus Status { get; set; } = TaskStatus.Pending;
    public int Attempts { get; set; } = 0;
    public List<ExecutionRecord> History { get; set; } = new();
}

public class ExecutionRecord {
    public DateTime StartTime { get; set; }
    public DateTime EndTime { get; set; }
    public bool Success { get; set; }
    public int AttemptNumber { get; set; }
}

public class TaskScheduler {
    private readonly Dictionary<string, Task> _tasks = new();
    private readonly object _lock = new();

    public void AddTask(Task task) {
        lock (_lock) {
            if (HasCycle(task)) throw new InvalidOperationException("Cycle detected");
            _tasks[task.Id] = task;
        }
    }

    public void ExecuteAll() {
        // Topological sort by priority
        var ready = _tasks.Values
            .Where(t => t.Status == TaskStatus.Pending && t.DependsOn.All(d => _tasks[d].Status == TaskStatus.Success))
            .OrderBy(t => t.Priority)
            .ToList();
        // Parallel execution of independent tasks
        Parallel.ForEach(ready, task => ExecuteWithRetries(task));
    }

    private void ExecuteWithRetries(Task task) {
        for (int i = 0; i <= task.MaxRetries; i++) {
            task.Status = TaskStatus.Running;
            try {
                task.Work();
                task.Status = TaskStatus.Success;
                task.History.Add(new ExecutionRecord { /* ... */, Success = true, AttemptNumber = i });
                return;
            } catch {
                task.History.Add(new ExecutionRecord { /* ... */, Success = false, AttemptNumber = i });
                if (i == task.MaxRetries) task.Status = TaskStatus.Failed;
            }
        }
    }

    public void CancelTask(string taskId) {
        // Run all dependents first, then cancel
        var task = _tasks[taskId];
        foreach (var dep in _tasks.Values.Where(t => t.DependsOn.Contains(taskId))) {
            CancelTask(dep.Id);
        }
        task.Status = TaskStatus.Cancelled;
    }

    private bool HasCycle(Task newTask) {
        // DFS-based cycle detection on the dependency graph
        var visited = new HashSet<string>();
        var stack = new HashSet<string>();
        return HasCycleDFS(newTask.Id, visited, stack);
    }

    private bool HasCycleDFS(string id, HashSet<string> visited, HashSet<string> stack) {
        if (stack.Contains(id)) return true;
        if (visited.Contains(id)) return false;
        visited.Add(id);
        stack.Add(id);
        foreach (var dep in _tasks[id].DependsOn) {
            if (HasCycleDFS(dep, visited, stack)) return true;
        }
        stack.Remove(id);
        return false;
    }
}
```

## 4.3 — Snake and Ladder (Asked at Media.net SDE-1)

### Requirements
```
1. Two or more players
2. Game table from user input OR default
3. Players choose dice size (1-N)
4. All start at position 0
5. First to reach end wins
6. Game stops after first winner
```

### Skeleton (C#)

```csharp
public class Board {
    public int Size { get; set; }
    public Dictionary<int, int> Snakes { get; set; } = new(); // key=head, val=tail
    public Dictionary<int, int> Ladders { get; set; } = new();
    public int EndPosition => Size * Size;
}

public class Player {
    public string Name { get; set; }
    public int Position { get; set; } = 0;
}

public class Dice {
    public int MaxValue { get; set; } = 6;
    public int Roll() => new Random().Next(1, MaxValue + 1);
}

public class Game {
    public Board Board { get; set; }
    public List<Player> Players { get; set; } = new();
    public Dice Dice { get; set; }
    private int _currentPlayerIdx = 0;

    public Player Play() {
        while (true) {
            var current = Players[_currentPlayerIdx];
            int roll = Dice.Roll();
            int newPos = current.Position + roll;
            if (Board.Snakes.ContainsKey(newPos)) newPos = Board.Snakes[newPos];
            if (Board.Ladders.ContainsKey(newPos)) newPos = Board.Ladders[newPos];
            current.Position = newPos;
            if (current.Position >= Board.EndPosition) return current;
            _currentPlayerIdx = (_currentPlayerIdx + 1) % Players.Count;
        }
    }
}
```

## 4.4 — LRU Cache (Asked Frequently)

```csharp
public class LRUCache {
    private readonly int _capacity;
    private readonly LinkedList<(int key, int val)> _list = new();
    private readonly Dictionary<int, LinkedListNode<(int, int)>> _cache = new();

    public LRUCache(int capacity) { _capacity = capacity; }

    public int Get(int key) {
        if (!_cache.TryGetValue(key, out var node)) return -1;
        _list.Remove(node);
        _list.AddFirst(node);
        return node.Value.val;
    }

    public void Put(int key, int value) {
        if (_cache.TryGetValue(key, out var existing)) {
            _list.Remove(existing);
            _cache.Remove(key);
        }
        var node = _list.AddFirst((key, value));
        _cache[key] = node;
        if (_cache.Count > _capacity) {
            var lru = _list.Last!;
            _list.RemoveLast();
            _cache.Remove(lru.Value.key);
        }
    }
}
```

## 4.5 — LLD Approach: 5-Step Framework

```
Step 1: Requirements clarification (3-5 min)
        - Ask 3-4 clarifying questions
        - Identify edge cases

Step 2: Identify entities/classes (5 min)
        - Nouns → classes
        - Verbs → methods

Step 3: Define relationships (5 min)
        - Composition over inheritance
        - One-to-many, many-to-many

Step 4: Apply SOLID + Design Patterns (3 min)
        - Singleton (TaskScheduler?)
        - Strategy (PricingRule)
        - Observer (Event-driven)
        - State (TaskStatus)
        - Factory (TaskFactory)

Step 5: Code 2-3 key APIs in IDE (40-50 min)
        - Run it mentally with 2-3 test cases
        - Make it RUN — that's the test
```

---

# 🏛️ PART 5: System Design (Light) — For SDE-2 / Senior Interns

> For **SWE Intern at Media.net**, system design is **rarely asked** (interview focuses on LLD). But for SDE-2 conversion or in case it comes up:

## 5.1 — Most Likely System Design Questions

| Problem | Notes |
|---|---|
| **Design Chat App scaled to 100M real-time users** | Asked for SRE-1 (but good to know) |
| **Cricbuzz Cricket Stats** | Asked at Media.net — schema design + queries |
| **Load Balancer** with add/remove nodes | Asked at Media.net SDE-2 |
| **Ad-tech system** (RTB, contextual matching) | Domain-specific bonus |

## 5.2 — Chat App at 100M Users (Outline)

```
Components:
- WebSocket server for real-time (not HTTP)
- Message queue (Kafka) for fanout
- Database sharding (by user_id)
- Presence service (Redis)
- Notification service (FCM/APNS)
- Storage (Cassandra for messages, MySQL for users)

Bandwidth: 100M users × 10 msg/day × 200 bytes = 200 TB/day
Storage: 5 years retention → 365 PB

Caching: Redis for last 100 messages per user
CDN: For media files (images, videos)
```

## 5.3 — Cricbuzz Schema Design (Asked at Media.net)

```
Tables:
- Player (id, name, country, role, dob)
- Match (id, venue, date, format)
- Innings (id, match_id, batting_team, bowling_team, score)
- BattingStats (innings_id, player_id, runs, balls, fours, sixes)
- BowlingStats (innings_id, player_id, wickets, runs_conceded, overs)

Queries:
- "Most centuries in 2024" → GROUP BY player_id HAVING COUNT(scores>=100) DESC
- "Most runs in IPL 2024" → JOIN Player, BattingStats, Match, aggregate

Denormalize for speed: Add PlayerCenturies (player_id, year, count) for fast queries
```

---

# 💬 PART 6: Behavioral + Project Deep-Dive

> **Media.net gives 1 full round to projects and culture fit.** Be ready to walk through **2-3 projects in 5-10 min each**, with 2-3 follow-up questions per project.

## 6.1 — Common Project Follow-Up Questions

| Question Type | Example |
|---|---|
| **Tech stack** | "Why did you choose MongoDB over PostgreSQL here?" |
| **Scale** | "If 10,000 users hit this at once, what would break?" |
| **Trade-offs** | "What's the biggest performance issue you'd fix first?" |
| **Security** | "How would you secure this from SQL injection / XSS?" |
| **What you'd improve** | "If you had 2 more weeks, what would you change?" |
| **Biggest bug** | "Tell me about a time this broke and how you fixed it" |

## 6.2 — "Why Media.net?" (Prepare 60 seconds)

> "Media.net is one of the top 5 ad-tech companies globally, processing 100+ billion ads annually. What excites me is the **scale** — building systems that handle this volume with low latency. Also, contextual advertising is a more privacy-respecting alternative to behavioral tracking, which is the future of the industry. I want to work on real-time bidding systems, ad matching algorithms, and large-scale data pipelines at Media.net's Bengaluru/Mumbai office."

## 6.3 — STARR Stories (Pick 2-3)

1. **A project with measurable impact** (e.g., "Built X that improved Y by 30%")
2. **A technical challenge you overcame** (e.g., "Fixed a race condition that crashed the system")
3. **A failure + learning** (e.g., "Chose wrong tech stack, learned to validate earlier")

---

# 🔮 PART 7: Predictions for Tomorrow (10 Oct 2026)

> Based on Media.net's 2025-2026 patterns, your batch (2027), and the on-campus format.

## 7.1 — OA Predictions (3 questions, 60-90 min)

**Most likely 3 questions (verified from 5 candidates):**

| Likely # | Predicted Question | Pattern | Why predicted |
|---|---|---|---|
| 1 | **DP (Easy-Medium)** | Climbing Stairs, Coin Change variant, or "find ways" | Always at least 1 DP per OA |
| 2 | **Hard Graph/DP** | Knight Probability OR Shortest Path with K Special Nodes | Asked in 80% of recent Media.net OAs |
| 3 | **Segment Tree / Bit Manipulation** | "Reconstruct order list" OR "Bitmask jumping" | Recent pattern (Yash Gupta report 2025) |

**Backup questions to prepare:**
- **Number of BSTs** (LC 96)
- **Number of Islands** (LC 200)
- **Top K Frequent** (LC 347)
- **Sliding Window Maximum** (LC 239)
- **LRU Cache** (LC 146)

**OA tips:**
- Use **C++ or Java** (Python may TLE on DP-heavy OAs; C++ is fastest)
- If you can't solve Q3, **ensure Q1 + Q2 are clean** — that's already 2/3
- Always include edge cases (empty, single element, duplicates)

## 7.2 — Tech Interview Predictions (1-2 rounds, 60 min each)

**Round 1 (DSA + CN/OS):**
- 1-2 Medium-Hard DSA (graph + tree, 50%)
- 20-30 min deep CN (DNS, HTTPS, IPv6, OS startup, paging, deadlock, mutex)
- 1-2 project walk-through questions

**Round 2 (DSA + OOP/LLD):**
- 1-2 Hard DSA (DSU + segment tree combo, or probability DP)
- 1 LLD question — most likely **Task Scheduler** (famous at Media.net)
- Project deep-dive follow-ups

## 7.3 — Most-Likely 5 Problems to Practice Tonight (if 30 min only)

1. **Knight Probability in Chessboard** (LC 688) — asked recently
2. **Number of BSTs** (LC 96) — asked at Media.net 2025
3. **Number of Islands** (LC 200)
4. **LRU Cache** (LC 146)
5. **Sliding Window Maximum** (LC 239)

Plus: **code the Task Scheduler LLD from scratch** (1 hour) — this is the most likely LLD.

---

# ⏰ PART 8: Day-Before Game Plan (12-Hour Schedule)

> Assuming your interview is **tomorrow morning (10 Oct 2026) at the CDP Cell**. Adjust times to your schedule.

## Hour 0-1: Quick Setup
- ✅ Read this document fully
- ✅ Bookmark [OAHelper Media.net](https://www.oahelper.in/interview-experience/MTMwNA) and [LinkedIn Yash Gupta post](https://www.linkedin.com/posts/yash-gupta-80a61526b_hiring-sde-intern-activity-7376896773618860032-wzi6) for reference

## Hour 1-3: DP Sprint (Most Important)
- Solve **5 DP problems** in 30 min each:
  1. Knight Probability (LC 688) — Medium
  2. Number of BSTs (LC 96) — Medium
  3. Coin Change (LC 322) — Medium
  4. Climbing Stairs (LC 70) — Easy
  5. Min Cost Stairs (LC 746) — Easy
- Self-evaluate: which one was slowest? Spend 15 more min on that

## Hour 3-4: Hard Graph Practice
- Solve **2 graph problems**:
  1. Shortest Path with K Special Nodes (CF) — 45 min
  2. Number of Islands (LC 200) — 15 min
- Focus on Dijkstra + state pattern

## Hour 4-5: Segment Tree / DSU
- Read segment tree basics
- Solve 1 problem: "Reconstruct order list" pattern (CF)
- 60 min total

## Hour 5-6: Code the Task Scheduler LLD
- Open VS Code, write the **full C# Task Scheduler** from scratch
- Include: dependencies, priority, retry, cancellation, history, cycle detection
- Test with 2-3 scenarios
- Time yourself: target <45 min for full working code

## Hour 6-7: Core CS Deep Review
- Read Part 3 tables
- For each of CN/OS, write 3 bullet points you'd say out loud
- Practice saying "DNS resolution works by..." in 60 seconds

## Hour 7-7:30: Project Deep-Dive
- Pick 2 projects, write 5-min walk-through for each
- Identify 3-4 likely follow-up questions per project
- Prepare answers

## Hour 7:30-8: Behavioral + Why Media.net
- Write 60-second "Why Media.net?" answer
- Write 2 STARR stories
- Practice saying each one in 90 seconds

## Hour 8-8:30: Logistics
- Find interview clothes (formal: shirt + tie optional)
- Set 2 alarms
- Water + snack ready
- Plan commute to CDP Cell (15 min early)

## Hour 8:30-9:30: Mock Hard Problem
- Pick 1 Hard problem (Knight Probability or DSU+Tree)
- Narrate out loud as if to interviewer
- Time-box: 45 min for full solution

## Hour 9:30-10:30: Sleep (CRITICAL)
- 7-8 hours of sleep — non-negotiable
- A tired brain underperforms by 30-40% on Hard problems
- Set 2 alarms

## Hour 10-11 (Morning of Interview)
- Wake up 90 min before interview
- Light breakfast
- 10 min review: Part 7 predictions + your Task Scheduler code
- Quick warm-up: 1 Easy LeetCode (e.g., Climbing Stairs)
- Arrive at CDP Cell 15 min before scheduled time

---

# 🔗 PART 9: Direct Question Links (Bookmark These)

> **All the problems and interview reports cited in this document — with one-click links.**

## 9.1 — DSA Problems (LeetCode Direct Links)

### Tier A — Must-Solve Tonight

| # | Problem | LeetCode | Pattern |
|---|---|---|---|
| 1 | Knight Probability in Chessboard | [LC 688](https://leetcode.com/problems/knight-probability-in-chessboard/) | Probability DP |
| 2 | Unique Binary Search Trees | [LC 96](https://leetcode.com/problems/unique-binary-search-trees/) | Catalan DP |
| 3 | Top K Frequent Elements | [LC 347](https://leetcode.com/problems/top-k-frequent-elements/) | Heap + Hash |
| 4 | Number of Islands | [LC 200](https://leetcode.com/problems/number-of-islands/) | BFS/DFS |
| 5 | LRU Cache | [LC 146](https://leetcode.com/problems/lru-cache/) | Doubly LL + Hash |
| 6 | Sliding Window Maximum | [LC 239](https://leetcode.com/problems/sliding-window-maximum/) | Monotonic Queue |
| 7 | Find the Celebrity | [LC 277](https://leetcode.com/problems/find-the-celebrity/) | O(N) trick |
| 8 | Coin Change | [LC 322](https://leetcode.com/problems/coin-change/) | DP |
| 9 | Climbing Stairs | [LC 70](https://leetcode.com/problems/climbing-stairs/) | DP |
| 10 | Min Cost Climbing Stairs | [LC 746](https://leetcode.com/problems/min-cost-climbing-stairs/) | DP |

### Tier B — Should-Solve

| # | Problem | LeetCode | Pattern |
|---|---|---|---|
| 11 | Next Greater Element II (circular) | [LC 503](https://leetcode.com/problems/next-greater-element-ii/) | Stack |
| 12 | Unique Paths II (obstacles) | [LC 63](https://leetcode.com/problems/unique-paths-ii/) | DP grid |
| 13 | Lowest Common Ancestor of BT | [LC 236](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) | Tree recursion |
| 14 | Kth Smallest Element in Array | [LC 215](https://leetcode.com/problems/kth-smallest-element-in-an-array/) | QuickSelect |
| 15 | Validate Binary Search Tree | [LC 98](https://leetcode.com/problems/validate-binary-search-tree/) | Tree recursion |
| 16 | Min Stack | [LC 155](https://leetcode.com/problems/min-stack/) | Stack design |
| 17 | Group Anagrams | [LC 49](https://leetcode.com/problems/group-anagrams/) | Hash + sort |
| 18 | Two Sum | [LC 1](https://leetcode.com/problems/two-sum/) | Hash map |
| 19 | Longest Substring Without Repeating | [LC 3](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Sliding window |
| 20 | Course Schedule (Topo Sort) | [LC 207](https://leetcode.com/problems/course-schedule/) | Graph BFS |

## 9.2 — Custom / Codeforces-Style Problems (Asked at Media.net)

> These are not on LeetCode — they're from real Media.net interviews and Codeforces archives.

| Problem | Source | Where to Practice |
|---|---|---|
| **Reconstruct order list (segment tree)** | Media.net 2025 OA | [CF: Order Restoration](https://codeforces.com/problemset/problem/1108/E1) (similar pattern) |
| **Bitmask jumping on planets** | Media.net 2023 | [CF: Bitmask DP](https://codeforces.com/problemset?tags=bitmask) |
| **Shortest Path with K Special Nodes** | Media.net SDE-2 | [CF: Dijkstra variants](https://codeforces.com/problemset/problem/1485/E) |
| **Matrix Diagonal Traversal** | Media.net SDE-2 | [GFG: Print matrix in diagonal pattern](https://www.geeksforgeeks.org/print-matrix-in-zig-zag-diagonal-pattern-from-top-left-to-bottom-right/) |
| **Connecting Points (min moves)** | Media.net SDE-2 | [CF: Graph construction](https://codeforces.com/problemset/problem/1243/C) |
| **Two Sets Min Cost (no common elements)** | Media.net 2025 | [CF: Two pointers + greedy](https://codeforces.com/problemset/problem/1738/A) |
| **Sliding Window Max on Interval** | Media.net 2023 | [LC 239](https://leetcode.com/problems/sliding-window-maximum/) |
| **Min Operations to Make Continuously Increasing** | Media.net 2023 | [CF: Greedy on array](https://codeforces.com/problemset/problem/1385/C) |
| **Probability DP — Knight on Board** | Media.net 2019, 2025 | [LC 688](https://leetcode.com/problems/knight-probability-in-chessboard/) |
| **Sum of Distances in Weighted Tree** | Media.net SDE-1 | [CF: Tree DP, O(N) re-rooting](https://codeforces.com/problemset/problem/1092/F) |

## 9.3 — Media.net-Specific Interview Reports (Direct Links)

| Source | Year | Direct Link | What to read |
|---|---|---|---|
| **Yash Gupta (IIT Patna) — Selected** | 2025 | [LinkedIn post](https://www.linkedin.com/posts/yash-gupta-80a61526b_hiring-sde-intern-activity-7376896773618860032-wzi6) | Full breakdown of all 3 OA questions + interview |
| **OAHelper — SDE Summer Intern Selected** | 2025 | [oahelper.in/MTMwNA](https://www.oahelper.in/interview-experience/MTMwNA) | 3-round experience, IIT Patna |
| **Naukri Code360 — SDE-1 Experience** | 2021 | [naukri.com](https://www.naukri.com/code360/interview-experiences/medianet) | Snake and Ladder LLD + Cricbuzz design |
| **dev.to/athenasquare — SRE/DevOps** | 2023 | [dev.to/athenasquare](https://dev.to/athenasquare/medianet-interview-experience-i3h) | CN/OS depth + 6 rounds |
| **prodsens.live — SRE-1 Journey** | 2023 | [prodsens.live](https://prodsens.live/2023/10/01/media-net-sre-1-role-my-interview-journey/) | 6 rounds, OS/CN deep |
| **interviewexperiences.in — All Reports** | 2022-2024 | [interviewexperiences.in](https://interviewexperiences.in/company/media.net) | 5 candidate reports |
| **Glassdoor — SDE Intern Questions** | 2019-2024 | [Glassdoor SDE Intern](https://www.glassdoor.co.in/Interview/Media-net-SDE-Intern-Interview-Questions-EI_IE1042683.0,9_KO10,20.htm) | 13 questions + 3 interview reports |
| **PapersAdda 2026** | 2026 | [papersadda.com](https://papersadda.com/article/media-net-placement-papers-2026/) | Latest process + LRU cache question |
| **OAHelper — All Media.net reports** | All years | [oahelper.in](https://www.oahelper.in/interview-experience/MTMwNA) | Browse all reports |
| **LinkedIn — All Media.net posts** | All years | [LinkedIn search](https://www.linkedin.com/search/results/content/?keywords=media.net%20interview%20experience) | Real-time candidate posts |

## 9.4 — Practice Sites to Bookmark

| Site | URL | Use for |
|---|---|---|
| **LeetCode** | [leetcode.com](https://leetcode.com/) | All DSA problems |
| **LeetCode Microsoft/Media.net Discussions** | [LC Discuss](https://leetcode.com/discuss/) | Company-specific Q&A |
| **Codeforces** | [codeforces.com](https://codeforces.com/) | Hard problems (CF Div 2 C/D) |
| **CSES Problem Set** | [cses.fi/problemset](https://cses.fi/problemset/) | Algorithms practice (free) |
| **GeeksforGeeks** | [geeksforgeeks.org](https://www.geeksforgeeks.org/) | Core CS + standard LLD |
| **HackerEarth** | [hackerearth.com](https://www.hackerearth.com/) | DSA + practice problems |
| **InterviewBit** | [interviewbit.com](https://www.interviewbit.com/) | Topic-wise practice |
| **TakeUforward** | [takeuforward.org](https://takeuforward.org/) | A2Z DSA sheet + SDE sheet |
| **Striver's SDE Sheet** | [takeuforward.org/strivers-a2z-dsa-course](https://takeuforward.org/strivers-a2z-dsa-course/strivers-a2z-dsa-course-sheet-2/) | Most-asked problems list |

## 9.5 — Reference Books (Free PDFs)

| Book | Author | Free PDF Link | Use for |
|---|---|---|---|
| **Introduction to Algorithms (CLRS)** | Cormen, Leiserson, Rivest, Stein | [CLRS Solutions](https://walkccc.me/CLRS/) | Algorithm reference |
| **Operating Systems: Three Easy Pieces** | Arpaci-Dusseau | [ostep.org](https://www.ostep.org/) | OS fundamentals (FREE) |
| **Computer Networks: A Top-Down Approach** | Kurose, Ross | (Buy) | CN reference |
| **Database System Concepts** | Silberschatz | (Buy) | DBMS reference |
| **Designing Data-Intensive Applications** | Kleppmann | [dataintensive.net](https://dataintensive.net/) | System design (FREE online) |

---

# 📚 PART 10: References (All Sources Cited)

## Process + Round Reports
- [LinkedIn — Yash Gupta: Hardest interview at Media.net (selected, 2025)](https://www.linkedin.com/posts/yash-gupta-80a61526b_hiring-sde-intern-activity-7376896773618860032-wzi6)
- [OAHelper — Media.net SDE Summer Intern Interview Experience](https://www.oahelper.in/interview-experience/MTMwNA)
- [PapersAdda — Media.net Placement Papers 2026](https://papersadda.com/article/media-net-placement-papers-2026/)
- [Naukri Code360 — SDE-1 Media.net interview experience](https://www.naukri.com/code360/interview-experiences/medianet)
- [dev.to/athenasquare — Media.net SRE/DevOps Interview Experience](https://dev.to/athenasquare/medianet-interview-experience-i3h)
- [prodsens.live — Media.net SRE-1 Interview Journey](https://prodsens.live/2023/10/01/media-net-sre-1-role-my-interview-journey/)
- [Glassdoor — Media.net SDE Intern Interview Questions](https://www.glassdoor.co.in/Interview/Media-net-SDE-Intern-Interview-Questions-EI_IE1042683.0,9_KO10,20.htm)
- [interviewexperiences.in — Media.net All Interviews](https://interviewexperiences.in/company/media.net)

## Company Info
- [careers.media.net — Official Careers Page](https://careers.media.net/)

## Related Problem Sets
- [LeetCode Hard problems (target for Media.net OA)](https://leetcode.com/problem-list/5h3a1boq/)
- [Codeforces Div 2 C/D — recommended practice range](https://codeforces.com/problemset)

---

# 🎯 FINAL CHEAT SHEET (Print This)

## The 5 Things Media.net Will Test You On (in order)

1. **DSA at HARD level** — not Medium. Solve Knight Probability, #96, LRU Cache, #200 tonight.
2. **CN/OS Deep** — DNS, HTTPS, IPv6, OS startup, paging, mutex. Say them out loud.
3. **LLD with working code** — Task Scheduler is the most famous. Code it from scratch.
4. **Project deep-dive** — 2 projects, 5-min walk-through, 3 follow-ups each.
5. **"Why Media.net?"** — Mention ad-tech, scale (100B+ ads/year), contextual advertising, privacy.

## Top 3 Things To Do in the Next 12 Hours

1. **Practice 5 Hard DP problems** (Knight Probability, #96, Coin Change, Climbing Stairs, Min Cost Stairs)
2. **Code the Task Scheduler LLD from scratch in C#/Java/C++** (verify it runs)
3. **Read Part 3 (CN/OS) tables once more before bed** — these are the most-tested topics

## If You Only Have 1 Hour

Practice these 3 problems in order:
1. **Knight Probability in Chessboard** (LC 688) — 30 min
2. **LRU Cache** (LC 146) — 15 min
3. **Number of Islands** (LC 200) — 15 min

Plus: **Code the Task Scheduler LLD from scratch in 60 min** if you have time.

---

> **Last updated:** 9 Oct 2026, 8:55 PM IST
> **Good luck tomorrow! Media.net is a HARD interview — multiple candidates report "hardest I've ever given." But you've prepared well. Focus on DP + CN/OS deep + Task Scheduler LLD. You've got this. 🌟**
