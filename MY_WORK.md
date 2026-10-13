# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [Abdulrhman Mohamed Ahmed Ibrahim Ahmed] |
| **Student ID** | [446052690] |
| **University Email** | 446052690@std.psau.edu.sa |
| **GitHub Username** | [Abdulrhman192006] |
| **Repository Link** | [https://github.com/Abdulrhman192006/OS-Assignment1-Abdulrhman-MohamedAhmed] |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/drive/folders/1Rh9oF9HMVs6VakuH4djfOxijsJfY4Cwn?usp=sharing]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 7, 2026, 4:30 PM]
**What I did**:

Forked the starter repository, configured Git environment, and personalized my student ID.
**Details**:
- Created a GitHub account using my university email 446052690@std.psau.edu.sa
- Forked the repository `makopt/OS-Assignment1-Starter-481` and renamed it to `OS-Assignment1-Abdulrhman-MohamedAhmed`.
- Cloned the repository to VS Code .
- Updated line 150 of `SchedulerSimulation.java` to set `int studentID = 446052690;`.
- Compiled and executed the starter code to confirm random parameter generation based on my ID seed.

**Challenges**:
Configuring global Git username and email credentials inside VS Code terminal.

**Solution**:
Executed `git config --global user.name` and `git config --global user.email` with my university credentials.

**Time spent**:
40 minutes

---

### Entry 2 - [October 8, 2026, 5:25 PM]
**What I did**: Implemented Feature 1 (Process Priority).

**Details**:
- Modified the `Process` class by adding a `private int priority` instance variable.
- Updated the constructor of `Process` to accept `priority` as an argument.
- Added a `getPriority()` getter method to access the process priority.
- Updated `main()` in `SchedulerSimulation.java` to generate a random priority (1–10).
- Updated `addProcessToQueue()` to display the priority level when a process enters the ready queue.

**Challenges**: Ensuring priority values remained between 1 and 10 without affecting the Round-Robin FIFO queue ordering.

**Solution**: Passed priority solely as an informational parameter while keeping the queue management FIFO-based.

**Time spent**:
1 hour

---

### Entry 3 - [October 9, 2026, 9:15 PM]
**What I did**: Implemented Feature 2 (Context Switch Counter).

**Details**:
- Added a static integer field `private static int contextSwitchCount = 0;` to `SchedulerSimulation`.
- Incremented `contextSwitchCount++` inside the scheduler `while` loop each time a process thread is retrieved from the queue to run.
- Added a summary output line at the end of execution displaying total context switches performed during the simulation run.

**Challenges**: Deciding whether to count context switches when re-enqueueing or at the moment of thread execution start.

**Solution**: Placed the counter increment right before `currentThread.start()` so every CPU context assignment is accurately logged.

**Time spent**:
1 hour

---

### Entry 4 - [October 10, 2026, 6:20 PM]
**What I did**: Implemented Feature 3 (Waiting Time and Turnaround Time Tracking).

**Details**:
- Added timestamp fields (`creationTime`, `lastEnqueuedTime`, `totalWaitingTime`) to the `Process` class using `System.currentTimeMillis()`.
- Implemented `markStartedExecution()` to calculate time spent in the queue prior to running, and `markReEnqueued()` to update queue entrance timestamps.
- Added `getWaitingTime()` and `getTurnaroundTime()` getter methods.
- Stored all processes in a master list `List<Process> allProcesses` in `main()`.
- Created a formatted summary table printed at simulation completion showing Process Name, Burst Time, Waiting Time, and Turnaround Time.

**Challenges**: Active execution time in `Thread.sleep()` was initially being miscalculated as waiting time.

**Solution**: Created explicit helper methods (`markStartedExecution()` and `markReEnqueued()`) to isolate active CPU execution from queue residence intervals.

**Time spent**: 1 hour

---

### Entry 5 - [October 11, 2026, 8:30 PM]
**What I did**: Resolved terminal character encoding issues and completed documentation files.

**Details**:
- Tested program execution under PowerShell and noticed scrambled UTF-8 characters (`ΓòÉ`, `Γû╢`).
- Resolved encoding by running `chcp 65001` in the terminal to switch console codepage to UTF-8.
- Filled out development log entries, reflection responses, and technical answers in `MY_WORK.md`.
- Verified code structure, comments, and commit history visibility. 

**Challenges**: PowerShell defaulting to OEM Code Page 437, breaking box-drawing and emoji symbol rendering.

**Solution**: Used `chcp 65001` prior to compilation and wrapped Java execution flags in quotes (`java "-Dfile.encoding=UTF-8" SchedulerSimulation`).

**Time spent**: 30 minutes

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: 5 hours

**Most challenging part**: Accurately calculating cumulative waiting time across multiple Round-Robin quantum preemptions without including active CPU execution time.

**Most interesting learning**: Understanding how thread state coordination (`start()`, `join()`, `sleep()`) translates theoretical CPU scheduling concepts into running code.

**What I would do differently next time**: Set up terminal UTF-8 encoding from day one to avoid console output formatting issues early on.
 
---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

Whil doing this assignment, I gained a practical understanding of thread creation, lifecycle management, and CPU time sharing mechanisms in Java. I learned how method calls like `Thread.start()`, `Thread.join()`, and `Thread.sleep()` coordinate concurrency between a central scheduler thread and individual process tasks. The simulation clearly demonstrated how preemptive scheduling simulates parallel execution by allocating discrete time slices to threads. Additionally, I learned how shared data structures like queues and maps coordinate state tracking without race conditions.


## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*
The most challenging part of the assignment was accurately tracking process waiting time across multiple Round-Robin execution slices. calculating true waiting time required tracking disjoint intervals. Initially active execution time inside `Thread.sleep()` was accidentally included in the wait time calculation. Decoupling CPU execution time from queue residence time required careful placement of timestamp references using `System.currentTimeMillis()`. Designing dedicated helper methods (`markStartedExecution()` and `markReEnqueued()`) inside the `Process` class resolved this issue while maintaining clean code architecture.


## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*
I overcame these challenges by tracing thread execution through console outputs and verifying state transitions step-by-step. I used detailed print statements to compare calculated timestamps against total process burst times, ensuring mathematical consistency ($\text{Turnaround Time} = \text{Waiting Time} + \text{Burst Time}$). To fix terminal formatting issues, I researched console code pages and applied `chcp 65001` to enable UTF-8 support in PowerShell. Furthermore, committing code incrementally after every individual feature helped verify that new additions did not break existing functionality. Consulting Java concurrency documentation also helped clarify thread state behavior during `Thread.join()` operations.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading concepts are essential for developing modern, high-performance software systems that remain responsive under heavy workloads. For example, it there is a task that requires heavy calcultaions done by the CPU , you can use mulithreading to seperate that heavy task into multiple threads to work on it .
web servers like Apache or Tomcat assign worker threads from a pool to process incoming client HTTP requests concurrently. Desktop and mobile applications rely on background threads to perform heavy disk I/O or network calls without freezing the main user interface. Database engines utilize concurrent threads to execute parallel query operations across multiple CPU cores efficiently.

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

A process is an independent program unit of execution environment with its own isolated memory address space allocated by the operating system, whereas a thread is a lightweight execution unit operating within a process that shares memory with sibling threads. In `SchedulerSimulation.java`, we used Java threads because all simulated processes run inside a single Java Virtual Machine process and need direct access to shared data structures like `processQueue` and `processMap`. Two primary differences are memory sharing and creation overhead: threads directly share heap memory without complex Inter-Process Communication (IPC), and creating or switching threads requires significantly less CPU overhead than creating OS-level processes. This relationship is directly represented in `addProcessToQueue()`, where a new Java `Thread` object is instantiated using `Thread thread = new Thread(process);`.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

In Round-Robin scheduling, when a process cannot complete its execution within the assigned time quantum, its remaining burst time is reduced by the quantum slice, it yields the CPU, and it is re-queued at the back of the ready queue. In my simulation run (Student ID: 446052690, Time Quantum: 2000 ms), process `P1` had an initial burst time of 4293 ms. During its first round, `P1` executed for 2000 ms, yielded the CPU with 2293 ms remaining, and was added back to the ready queue behind `P15`. In total, `P1` was re-queued 2 times before completing its execution on its 3rd turn.

Example from my output:
➕ P1(Priority : 6 ) added to ready queue │ Burst time: 4293ms
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P3 → P4 → P5 → P6 → P7 → P8 → P9 → P10 → P11 → P12 → P13 → P14 → P15 → P1]
└───────────────────────────────────────────────────────────────────────────────


  ▶ P1 executing quantum [2000ms] 
  ⚡ Quantum progress: [███████████████] 100%
  ⏸ P1 completed quantum 2000ms │ Overall progress: [█████████░░░░░░░░░░░] 46%
     Remaining time: 2293ms
  ↻ P1 yields CPU for context switch

  ➕ P1(Priority : 6 )  added to ready queue │ Burst time: 4293ms
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P3 → P4 → P5 → P6 → P7 → P8 → P9 → P10 → P11 → P12 → P13 → P14 → P15 → P1]
└───────────────────────────────────────────────────────────────────────────────
**Explanation of example:**
Process `P1` executes for 2000 ms (one full quantum). Because its remaining time (2293 ms) is greater than zero and other processes exist in the queue, `P1` yields the CPU and is placed at the tail of the ready queue behind `P15`. This re-queueing behavior guarantees fairness by preventing long-running tasks from monopolizing the CPU.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: `P1` enters the `New` state when a new thread instance is created via `Thread thread = new Thread(process);` inside the `addProcessToQueue()` helper method.

2. **Runnable**: `P1` transitions to `Runnable` when added to `processQueue` and subsequently selected by the scheduler when `currentThread.start()` is invoked in `main()`.

3. **Running**: `P1` enters the `Running` state when the JVM thread scheduler allocates CPU core execution time to it, executing the code inside its `run()` method.

4. **Waiting**: `P1` enters the `Timed_Waiting` state when `Thread.sleep(runTime)` is called inside `run()` to simulate CPU execution time, while the main scheduler thread enters `Waiting` state when calling `currentThread.join()`.

5. **Terminated**: `P1` transitions to `Terminated` once its `run()` method completes execution, allowing `currentThread.join()` in `main()` to return.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): Operating System CPU Scheduler

**Description**:
Modern operating systems like Linux or Windows use multi-level Round-Robin scheduling variants to share CPU core time slices among multiple running desktop programs (e.g., web browser, music player, code editor).

**Why Round-Robin works well here**:
Round-Robin ensures responsiveness and fairness across user applications. By giving each application a small time quantum for example : 10–100 ms, no single background process can freeze the system, providing a smooth multitasking user experience.

### Example 2: Multi-Client Web / Game Server

**Description**:
A multiplayer game server or web server handling thousands of incoming client socket connections simultaneously, where worker threads process incoming client packets in time-sliced rounds.

**Why Round-Robin works well here**:
Round-Robin scheduling provides equal fairness and predictable latency for all connected players or clients. It prevents heavy request processing for one player from starving other connected users of server response time.

## Summary

**Key concepts I understood through these questions:**
1. The operational distinction between Java threads and OS processes.
2. How Round-Robin queue preemptions enforce fairness in CPU resource sharing.
3. How thread lifecycle states transition across `start()`, `sleep()`, and `join()` calls.

**Concepts I need to study more:**
1. Synchronization primitives (`synchronized`, locks) for thread safety.
2. Non-preemptive vs preemptive priority scheduling algorithms.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
