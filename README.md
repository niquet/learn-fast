# Learn Fast

A neurodivergent-friendly framework for learning new concepts while staying productive.

<img src="assets/images/learn-fast.png" width="100.00%" height="auto">

## TL;DR

1. **Clarify Your Purpose:** What problem are you solving? What’s the smallest thing you can build to make progress?
2. **Isolate and Break It Down:** Focus on one concept or problem at a time. Identify 3–5 key components or tasks.
3. **Create Proof of Concept(s):** Build small, quick experiments to test your understanding.
4. **Timebox Your Learning:** Work in 25-minute sprints with short breaks.
5. **Build First, Research Second:** Start getting hands-on immediately; research only when stuck.
6. **Document & Reflect:** Write down what you learned and any gaps to revisit later.
7. **Teach It Back:** Share your learnings through PR reviews, blog posts, or open-source contributions.

Key Takeaways:

- Isolate the problem first, then create proof of concepts.
- Use forums like StackOverflow before turning to AI tools, and only after clarifying your question.
- Build something concrete—action beats abstraction every time!

## Table of Contents

- [Description](#description)
- [Motivation](#motivation)
- [Context](#context)
  - [Minimum Viable Knowledge](#minimum-viable-knowledge)
  - [Project-Based Learning](#project-based-learning)
  - [Why Focus on Action?](#why-focus-on-action)
- [Usage](#usage)
  - [Step 0: Clarify Your Purpose](#step-0-clarify-your-purpose)
  - [Step 1: Isolate and Break Down the Topic](#step-1-isolate-and-break-down-the-topic)
  - [Step 2: Create Proof of Concept(s)](#step-2-create-proof-of-concepts)
  - [Step 3: Timebox Your Learning](#step-3-timebox-your-learning)
  - [Step 4: Build First, Research Second](#step-4-build-first-research-second)
  - [Step 5: Document & Reflect](#step-5-document--reflect)
  - [Step 6: Teach It Back](#step-6-teach-it-back)
- [Tips](#tips)

## Description

Imagine these two scenarios:

1. You encounter a problem and keep spiraling down a rabbit hole, chasing one concept after another, only to end up overwhelmed and stuck.
2. You try to learn something new, but after 5 minutes and 491 browser tabs, you feel lost, frustrated—and no closer to solving anything.

Sound familiar? If so, this README is for you.

This repository introduces an actionable framework that helps you **learn fast** while solving real-world problems. It’s designed for software engineers (and anyone else) who want to focus on **project-based learning** and **minimum viable knowledge** without getting sidetracked or overwhelmed.

Why a README instead of a blog post? Because I’m a software engineer—and I’ve included Pull Request and Issue templates that you can integrate directly into your projects to achieve better learning outcomes while actually getting work done.

Ready to take control of your learning, avoid AI shortcuts, and build lasting competence? Let’s dive in! 🎉

## Motivation

Learning is hard. Staying focused while learning something new? Harder. Churning out tasks at work while trying to pick up the concepts you need to hit deadlines? Even harder. And avoiding over-reliance on AI tools while still learning on the job? That can feel impossible.

As software engineers, we’re constantly faced with situations where we need to pick up new skills or solve unfamiliar problems—fast. But here’s the catch:

- You start researching, and before you know it, you’ve opened 20 tabs and gone down a rabbit hole of unrelated topics.
- Or you try to learn systematically, but the sheer volume of information leaves you overwhelmed and stuck.
- Or worse—you give in to time pressure, ask your favorite AI tool for help, solve the problem...and realize later that you didn’t actually learn anything from it.

Sound familiar? You’re not alone. And either way, real learning doesn't happen anymore.

Sound familiar? You’re not alone—and it’s not your fault. The traditional ways we’re taught to learn don’t always work for everyone—especially neurodivergent thinkers who thrive on structure, momentum, and tangible results. And now, with AI tools making it easier than ever to bypass deep understanding, real learning often takes a backseat to quick fixes.

This repository was born out of frustration with those challenges. Learn Fast is designed to help you:

- **Learn effectively** without getting sidetracked by unnecessary details or endless research spirals.
- **Stay productive** by focusing on real-world applications instead of abstract theory or passive study.
- **Build confidence** through small wins and incremental progress that reinforce what you’ve learned.
- **Develop lasting competence** by prioritizing understanding over AI-first problem-solving shortcuts.

Whether you’re debugging a tricky issue, exploring a new technology, or mastering software design principles, this approach will help you learn fast while actually getting things done—without sacrificing depth or clarity along the way.

Let’s turn confusion into clarity and frustration into progress! 🎉

## Context

The Learn Fast framework is built on two key principles: Minimum Viable Knowledge and Project-Based Learning.

1. Minimum Viable Knowledge

Focus on _the smallest amount of knowledge you need to solve a problem or build something useful_. Forget about mastering everything upfront—learn just enough to take action.

Example: If you’re learning "observability," start with:

- Collecting metrics for one service
- Visualizing those metrics in a dashboard
- Adding basic alerts

Once that’s working, expand incrementally (e.g., distributed tracing, log aggregation).

2. Project-Based Learning

_Learn by doing._ Build small, focused projects that apply the concept you’re trying to learn. This approach turns abstract ideas into tangible skills while keeping you productive.

Example: Instead of reading endless articles about "design patterns," refactor one class in your codebase using the Observer Pattern. Then try another pattern like Factory in a separate module.

3. Why Focus on Action?

Avoid getting stuck in endless research or theory—it kills momentum and leaves you overwhelmed. Action-based learning helps you:

- Retain concepts better by applying them immediately.
- Identify gaps in understanding naturally as you build.
- Stay motivated by creating something tangible.

## Usage

Here’s the actionable framework for learning fast:

### Step 0: Clarify Your Purpose

Start by grounding yourself in **why** you’re learning this concept.

- [ ] What problem am I trying to solve?
- [ ] What outcome do I need?
- [ ] What’s the smallest thing I can build to make progress?

Identify the smallest unit of knowledge that would allow you to do something useful.

**Example:**

"I need to debug latency issues in my microservices using distributed tracing. I don’t know how distributed tracing works. Maybe I can find an introduction for the OTEL SDK in the language I’m using."

### Step 1: Isolate and Break Down the Topic

Before diving in, isolate what you’re trying to learn or solve. Focus on one concept or problem at a time. Then break it down into manageable chunks or use cases that take just a few minutes to understand.

**Checklist:**

- [ ] What are the key building blocks of this concept?
- [ ] What’s essential vs. optional for my current goal?
- [ ] Can I align these components with small, actionable tasks?

**Example for "distributed tracing":**

1. Spans and trace IDs
2. Context propagation between services
3. Visualizing traces in a dashboard (e.g., Jaeger)

If you’re unsure where to start, **try ADEPT** to get a sense of the topic:

- **Analogy:** Find a familiar concept to compare with the new topic.
- **Diagram:** Sketch the concept visually (even if it’s rough).
- **Example:** Look for concrete examples or code snippets online.
- **Plain English:** Try explaining it in simple terms.
- **Technical Definition:** Only then dive into formal terminology.

Tip: Don’t spend more than 10–15 minutes on this step—analysis paralysis is your enemy! Get the gist by reading introductions. Create a "read later" list for anything non-essential to avoid rabbit holes.

### Step 2: Create Proof of Concept(s)

Once you’ve isolated the problem or concept, start building small proof-of-concept implementations. These should be quick and focused experiments designed to test your understanding or solve part of the problem.

**Checklist:**

- [ ] Have I defined a single task that can be completed in <= 25 minutes?
- [ ] Am I focusing on making it work before making it perfect?

**Example:**

"Add spans to one service and visualize them—don’t worry about connecting multiple services yet."

Intermediate Step: Before turning to AI tools, rely on forums like StackOverflow, GitHub discussions, or even rubber duck debugging (explaining your problem out loud). These steps help you clarify your thinking and expose gaps in understanding before outsourcing answers.

### Step 3: Timebox Your Learning

Work in short, focused sprints using timeboxing techniques like Pomodoro:

- Spend 25 minutes implementing something tangible (even if it’s broken).
- Take a 5-minute break to reflect or reset before continuing.

Use the "touch it once" principle: work on the task until completion or until time runs out. If distracted, gently redirect attention without self-criticism.

Pro Tip: If you hit a blocker during implementation, pause and ask yourself:

- What’s not working? Why?
- What specific question do I need answered right now?

### Step 4: Build First, Research Second

Start getting hands-on immediately—even if you don’t fully understand the concept yet. Research only when you hit a blocker or error that prevents progress.

**Checklist:**

- [ ] Am I focusing on isolated tasks (not major architectural changes)?
- [ ] Have I tried solving this with existing knowledge before researching?

When researching:

1. Look for similar problems on forums like StackOverflow or GitHub issues first.
2. Use AI tools only as a last resort after clarifying your question.

Pro Tip: Start with the simplest possible implementation: "Make it work before making it right; make it right before making it fast."

### Step 4: Document & Reflect

After each session, take a few minutes to document what you’ve learned and identify gaps in your understanding. This reinforces retention and helps guide your next steps.

**Checklist:**

- [ ] What did I learn today? (1–2 sentences)
- [ ] What gaps remain in my understanding? (specific questions)

Example: "I understand how spans work but not how parent-child relationships are created."

Use techniques like the Feynman Technique for deeper understanding:

1. Write down the concept at the top of a page.
2. Explain it in simple terms as if teaching someone else (or a rubber duck).
3. Identify gaps in your explanation—these are areas to revisit later.

### Step 6: Teach It Back

You truly understand something when you can teach it to others or apply it in new contexts. Teaching also exposes gaps you might not notice otherwise.

Here are ways to "teach back" what you’ve learned:

1. **Pull Request Reviews:** Submit a PR showcasing your implementation and ask reviewers specific questions about areas you're unsure of.
2. **Write About It:** Create a blog post, README section, or internal documentation explaining what you learned.
3. **Open Source Contribution:** Apply what you’ve learned by contributing to an open-source project.
4. **Pair Programming:** Teach someone else while pairing on similar tasks.

Pro Tip: Teaching doesn’t have to be formal—recording yourself explaining something (e.g., Loom videos) can be just as effective.

## Tips

Here are some practical tips to help you stay focused, productive, and effective while learning.

### Make Tasks Actionable

Use the SMART framework to turn vague goals into actionable tasks:

- **Specific:** "Implement a logging system that captures errors" instead of "learn logging."
- **Measurable:** Define concrete outcomes (e.g., "Create a working prototype with 3 design patterns").
- **Achievable:** Choose tasks you can complete with your current resources.
- **Relevant:** Ensure tasks directly apply to your work or projects.
- **Time-bound:** Set deadlines for each milestone.

### Identify Knowledge Gaps

Ask yourself:

- What problems am I trying to solve?
- What tasks am I currently unable to complete?
- What concepts do I struggle to explain to others?
- Which errors or issues repeatedly challenge me?

### Create a "No-AI Zone" for Core Skills

Some skills should be mastered without relying on AI tools:

- Identify foundational skills (e.g., debugging, version control).
- Practice these regularly without assistance.
- Use AI only for reviewing or validating after completing the work independently.

### For Technical Topics

- Decompose by functionality: Break down topics like "debugging" into smaller parts (e.g., setting breakpoints, reading stack traces).
- Create a dependency tree: Identify which concepts depend on others.
- Build a learning roadmap: Arrange subtopics from foundational to advanced.
- Make each task concrete and actionable by using the the SMART Framework:

### For Abstract Concepts

- Find concrete implementations: For example, look at codebases that exemplify software design principles like SOLID.
- Reverse-engineer examples: Study well-designed systems and identify the principles at work.
- Apply to your own code: Refactor an existing project using what you’ve learned.

### Harness Hyperfocus & Creativity

Leverage neurodivergent strengths like hyperfocus and creative problem-solving:

1. Identify your peak focus hours and schedule learning sessions during those times.
2. Set clear, achievable goals for each session.
3. Create connections between new concepts and what you already know—visualize how components interact in the bigger picture.

### Last But Not Least

- Build a personal knowledge base—any format that works for you.
- Regularly review and update your notes and code snippets.
- Gamify progress by setting up rewards for milestones or turning learning into a game.
- Use physical movement to process information (e.g., take short walks between sessions).

## Wrap-Up & Next Steps

Mastering new concepts and solving problems effectively is about more than just completing tasks—it’s about building lasting competence. Some skills form the backbone of engineering expertise and should be learned independently of AI tools or automation. These are essential for developing mental models, problem-solving confidence, and adaptability in a rapidly evolving industry.

For a detailed list of core skills every software engineer should master without AI, check out [LEARN.md](LEARN.md).

Experiment with the Learn Fast framework, adapt it to your needs, and share your feedback or improvements via Issues or Pull Requests.

Let’s keep learning—and building—together! 🎉
