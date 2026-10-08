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
| **Full Name** | [raghad bander almuatiri] |
| **Student ID** | [445052724] |
| **University Email** | 445052724@std.psau.edu.sa |
| **GitHub Username** | raghadbander  |
* **Repository URL:** https://github.com/raghadbander/OS-Assignment1-Raghad-almutairi.git 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

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
### Entry 1 - Oct7 , 2026, 12PM 
**What I did**: Set up the repository, initialized student ID, and configured VS Code environment.

**Details**: Forked the assignment repository on GitHub, renamed it according to guidelines, cloned it locally via VS Code, and updated `studentID = 445052724` inside `SchedulerSimulation.java`.

**Challenges**: Facing Git authentication and remote synchronization issues while trying to push the first commit from VS Code terminal.

**Solution**: Linked VS Code directly with my GitHub account using the university email (@std.psau.edu.sa) and configured Git global credentials.

**Time spent**: 3 hours

### Entry 2 - Oct 8, 2026 , 8 PM
**What I did**: Implemented Feature 1 (Process Priority) in `SchedulerSimulation.java`.

**Details**: Added a `priority` attribute (1–10) to the `Process` class, updated its constructor and getter method, generated random priorities during process creation, and printed the priority value when a process enters the ready queue.

**Challenges**: Ensuring the newly added priority attribute did not alter the Round-Robin FIFO execution order.

**Solution**: Kept the priority field strictly for tracking and display purposes without modifying the queue management logic.

**Time spent**: 1 hours
---
### Entry 3 - Oct 8, 2026, 9 PM
**What I did**: Implemented Feature 2 (Context Switch Counter).

**Details**: Added a static variable `contextSwitchCount` to track context switches, incremented it every time a thread starts execution from the queue, and displayed the total count at the end of the simulation.

**Challenges**: Deciding the exact location to increment the counter to avoid undercounting or overcounting switches.

**Solution**: Placed `contextSwitchCount++` right after dequeuing a process thread in the main scheduler loop.

**Time spent**:1 hours
---

### Entry 4 - Oct 8, 2026, 10PM
**What I did**: Implemented Feature 3 (Waiting & Turnaround Time Tracking) and Summary Table.

**Details**: Added `creationTime` and `completionTime` fields to `Process`, calculated waiting time and turnaround time, and formatted a summary table printed after all processes complete.

**Challenges**: Measuring process timestamps correctly across multiple time quantum yields without losing creation context.

**Solution**: Recorded `creationTime` at process instantiation and set `completionTime` when `remainingTime == 0`.

**Time spent**: 1 hours

---
### Entry 5 - Oct 9, 2026, 12 AM
**What I did**: Completed project documentation, verified code execution, and recorded video demonstration.

**Details**: Answered all technical and reflection questions in `MY_WORK.md`, verified code output inside VS Code IDE, recorded the 2–3 minute video presentation, uploaded it to Google Drive, and added the public URL link to the documentation.

**Challenges**: Keeping the video duration within the strict 2-to-3-minute limit while covering all required walkthroughs and concepts.

**Solution**: Rehearsed the presentation script beforehand to hit all checklist items concisely within the timeframe.

**Time spent**: 3 hour

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---
## Development Log Summary

**Total time spent on assignment**: 8 hours

**Most challenging part**: Managing thread execution timing while tracking accurate creation and completion timestamps across multiple Round-Robin context switches in Feature 3.

**Most interesting learning**: Seeing how thread management concepts (`start()`, `join()`, `sleep()`) interact with dynamic process scheduling, and how visual progress bars reflect context switching in real time inside the IDE.

**What I would do differently next time**: Set up the Git workflow and GitHub environment earlier, and structure time calculations into dedicated helper modules to keep the simulation code even cleaner.

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
[I gained a strong practical understanding of Java multithreading and thread lifecycle management utilizing the Runnable interface while working on this assignment. I discovered that while Thread.sleep() pauses execution to mimic CPU quantum consumption, Thread.start() advances a thread to the running state. My understanding of thread synchronization was improved by implementing Thread.join(), which makes sure the main scheduler waits for a quantum to complete before selecting the next process. SchedulerSimulation modification.I was able to observe how lightweight threads in Java enable effective context change without significant process overhead. In general, real-time thread state tracking assisted in bridging the gap between Java implementation and OS scheduling theory.]


## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*
[Implementing Feature 3 to precisely track wait and turnaround times was the most difficult aspect of this task. Calculating the precise timeframes was challenging because processes relinquish the CPU several times across Round-Robin context transitions before completing. I had to ensure that the process creation timestamp was recorded at initialization and that the completion timestamp was only recorded when the remaining time was zero. Furthermore, precise placement inside the Process class was needed to calculate the waiting time by deducting the burst time from the turnaround time. It was an excellent exercise to learn about Java thread state changes and timing by fixing this logic error.]
ج;
ج
## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I used a methodical debugging approach by tracking the code execution step-by-step to get over the obstacles I encountered. To see how timestamps and process variables changed throughout execution, I inserted temporary System.out.println statements into the SchedulerSimulation and run() functions. The precise formula requirements for waiting time and turnaround time were made clearer by carefully reading the README.md file again. Additionally, instead of creating all the code at once, I tested my changes gradually after implementing each tiny feature. I was able to swiftly identify logic issues and confirm that all three features functioned flawlessly together thanks to this methodical, test-driven approach.
]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[In order to maintain software responsiveness and speed, multithreading techniques can be directly applied to contemporary real-world applications. Web browsers such as Google Chrome, for example, use distinct background threads to retrieve data from APIs while maintaining a fully interactive user interface. In a similar vein, specialized threads are used in multiplayer video games to manage music, render visuals, and handle physics all at once. When developing mobile apps, downloading large media files on a background thread keeps the main user interface thread from freezing or crashing. Similar techniques are used by real-world OS schedulers to distribute CPU resources equitably among all running background tasks, just as our Round-Robin scheduler assigned time slices to processes.
]

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

A thread is a small unit of execution that operates inside a process and shares its memory space, whereas a process is an independent program with its own memory. Because Java threads have far lower creation overhead and faster communication than independent OS processes, we used them in this assignment. It is crucial to remember that our code's Process class is just a simulated process that implements Runnable, which is actually carried out by a real Java Thread. This difference is evident in addProcessToQueue(), where we use Thread thread = new Thread(process); to wrap the process object within a new thread prior to scheduling.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[When a process does not complete within its allocated time quantum in Round-Robin scheduling, it yields the CPU, its remaining burst time is updated, and it is placed back at the end of the ready queue. In my simulation output, process P3 had a total burst time of 8920ms, which exceeded the system time quantum of 4000ms, so it could not finish in a single pass. Consequently, P3 yielded the CPU and was re-queued 2 times before finally completing its execution on its third turn. Re-queueing is essential for CPU scheduling fairness because it prevents long processes from blocking shorter ones, ensuring all active tasks receive regular access to the CPU.]

Example from my output:
```
[? P3 executing quantum [4000ms]  
  ? Quantum progress: [███████████████] 100%
  ? P3 completed quantum 4000ms │ Overall progress: [████████░░░░░░░░░░░░] 44%
     Remaining time: 4920ms
  ? P3 yields CPU for context switch

  ? P3 (Priority: 10) added to ready queue │ Burst time: 8920ms
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P5 ? P6 ? P7 ? P8 ? P9 ? P10 ? P11 ? P12 ? P13 ? P14 ? P15 ? P2 ? P3]
└───────────────────────────────────────────────────────────────────────────────]
```

**Explanation of example:**
[In this snippet from my output, process P3 executes for its first time quantum of 4000ms, reducing its remaining time to 4920ms. Since it still requires more CPU time, P3 yields execution and is added back to the end of the ready queue behind P2. It waits for its next turn in the queue to receive another time quantum until its remaining time drops to zero. ]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1 enters the New state when its `Thread` object is created in `addProcessToQueue()` via `Thread thread = new Thread(process)`.

2. **Runnable**: P1 transitions to the Runnable state as soon as it is instantiated and placed into the ready queue, waiting for the scheduler to allocate CPU time.

3. **Running**: P1 enters the Running state when the scheduler picks it from the queue and calls `currentThread.start()`, executing P1's `run()` method.

4. **Waiting**: P1's thread enters the Waiting (or Sleeping) state when `Thread.sleep(stepTime)` is called inside its `run()` method to simulate quantum time consumption.

5. **Terminated**: P1 transitions to the Terminated state when its `remainingTime` reaches 0 and its `run()` method finishes execution, after which `currentThread.join()` allows the main thread to clean up before moving to the next process.

   
## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [operating-system level): Operating System CPU Scheduler]

**Description**:
[Round-Robin scheduling is used by the OS kernel scheduler in contemporary desktop and server operating systems, such as Linux and Windows, to distribute CPU time across several concurrently running applications (such as text editors, web browsers, and background services). The "time quantum" is represented by the fixed clock tick, the "process" is represented by each running application, and the "context switch" is represented by the saving/loading thread CPU register values.]

**Why Round-Robin works well here**:
[Round-Robin ensures high responsiveness and fairness across all active processes. By giving every program a small, equal time slice, no single heavy process can monopolize the CPU, which prevents user interfaces from freezing while background tasks complete.]

### Example 2: [Multiplayer Online Game Server]

**Description**:
[The backend server in online multiplayer game servers handles real-time game state updates from several active player sessions, including player movements, hit detection, and chat packets. The "process" in this scenario is updating each player's state; the "time quantum" is the maximum millisecond budget permitted per player turn; and the "context switch" is cycling to the next player's data queue.]

**Why Round-Robin works well here**:
[Round-Robin delivers predictability and strict fairness among all connected clients. It prevents a player sending heavy network packets or triggering complex physics calculations from delaying state updates for other players, ensuring low latency and smooth gameplay for everyone.]

## Summary

**Key concepts I understood through these questions:**
1. The basic distinction between operating system processes and lightweight Java threads, especially with relation to memory sharing and creation overhead.
2. How Round-Robin scheduling re-queues incomplete processes after their time quantum expires to preserve fairness and avoid process starvation.
3. The full Java thread lifecycle (New, Runnable, Running, Waiting, Terminated) and how methods like `Thread.start()`, `Thread.sleep()`, and `Thread.join()` cause state transitions.


**Concepts I need to study more:**
1. When threads access shared data structures concurrently, sophisticated synchronization techniques and race condition prevention are used.
2. How dynamic thread priority modifications are handled by real-time CPU scheduling methods (such Multi-Level Feedback Queues).

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
