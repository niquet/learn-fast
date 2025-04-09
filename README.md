# Learn Fast

*A neurodivergent-friendly system for mastering complex technical topics.*

## TL;DR

1. **Clarify** and isolate which problem you are trying to solve
2. **Identify** the smallest unit of knowledge that would allow you to do something useful
3. **Break down** the topic(s) into small tasks
4. **Focus** intensely on one task for 25 minutes
5. **Immediately apply** the concept to a real project (simplest possible implementation)
6. **Identify any gaps** in your understanding
7. **Adjust** your approach for the next topic
8. **Celebrate** progress, no matter how small :tada:

Isolate the problem/concept first. Then create proof of concept(s). Rely on online resources and StackOverflow before using AI tools.

## Advice

- Effective learning is active, not passive

Identify knowledge gaps through questions

- What problems am I trying to solve?
- What tasks am I currently unable to complete?
- What concepts do I struggle to explain to others?
- Which errors or issues repeatedly challenge me?

Practice deliberate retrieval

- After learning something, close all resources and try to implement it from memory
- Only check AI or documentation after you've made a genuine attempt
- Compare your solution with AI suggestions to identify gaps in understanding

Create a "No-AI Zone" for core skills

- Identify fundamental skills that you must master without assistance
- Practice these skills regularly without AI help
- Use AI only for review after you've completed work independently

*Below the process.*

## Minimum viable knowledge

**0. Clarify your purpose (5-10 minutes)**

- [ ] What problem am I trying to solve with this knowledge?
- [ ] Which outcomes am I trying to achieve? (1-3 specific outcomes)

Identify the smallest unit of knowledge that would allow you to do something useful. For example, break "observability" into: metrics collection, log aggregation, trace analysis, and alerting. *Start by breaking down whatever you're trying to learn into specific use cases or bite-sized chunks that take just a few minutes to understand.*

```
Example: "I want to implement effective logging in my microservices to troubleshoot issues faster"
```

**1. Use the ADEPT method (10-15 minutes)**

Start by just trying things out to get a feel for the topic. Get the gist by reading introductions, first/last paragraphs of sections, and code samples. Create a "read later" list for interesting but non-essential details to avoid rabbit holes.

- [ ] Analogy: Find a familiar concept to compare with the new topic
- [ ] Diagram: Sketch the concept visually
- [ ] Example: Find concrete instances of the concept in action
- [ ] Plain English: Explain it in simple terms
- [ ] Technical Definition: Only then dive into formal terminology

**3. Create a topic map** (10-15 minutes)

- [ ] Draw the main topic in the center of a page
- [ ] Branch out into 3-7 subtopics (no more to avoid overwhelm)
- [ ] For each subtopic, note 1-2 specific skills to develop

For "software design principles," branches might include: SOLID principles, design patterns, architecture styles. Use colors and symbols to make it visually engaging.

**3. Break down the topics into small tasks** (5-10 minutes)

- [ ] Break each subtopic into tasks requiring 25 minutes or less
- [ ] Make each task concrete and actionable

Make each task concrete and actionable by using the the SMART Framework:

- **Specific:** "Implement a logging system that captures errors in my application" instead of "learn logging"
- **Measurable:** Define concrete outcomes (e.g., "Create a working prototype that implements 3 design patterns")
- **Achievable:** Choose goals you can accomplish with your current resources
- **Relevant:** Ensure it applies to your work or projects
- **Time-bound:** Set deadlines for each learning milestone

```
Example: "Within the next 25 minutes, write a function that implements the Observer pattern" instead of "Learn the Observer pattern"
```

## Hands-on approach

**4. Set up your environment** (5 minutes)

- [ ] Clear physical and digital workspace
- [ ] Turn on "Do Not Disturb" mode on all devices
- [ ] Have water and a small snack ready
- [ ] Set a visual timer for your session

**5. Promodoro learning blocks** (25 minutes each)

- [ ] Focus intensely on one task for 25 minutes
- [ ] Use the "touch it once" principle: work on the task until completion or time runs out
- [ ] If distracted, gently redirect attention without self-criticism

**6. Active processing** (5 minutes)

- [ ] Stand up and move physically
- [ ] Verbally summarize what you just learned
- [ ] Sketch a quick diagram of the concept
- [ ] Do NOT check email or social media during this break

## Reinforcement

**7. Apply what you've learned** (25-50 minutes)

- [ ] Immediately apply the concept to a real project
- [ ] Start with the simplest possible implementation
- [ ] Focus on making it work before making it right
- [ ] Focus on making it right before making it fast

**8. Teach-back (immersion)** (10 minutes)

- [ ] Explain the concept out loud as if teaching someone
- [ ] Record a voice memo explaining the concept
- [ ] Write a brief explanation in your own words
- [ ] Identify any gaps in your understanding

Use the Feynman Technique to truly understand difficult concepts:

- Write down the concept at the top of a page
- Explain it in simple terms as if teaching someone else
- Identify gaps in your understanding
- Go back to source material to fill those gaps

**9. Connect the dots** (5-10 minutes)

- [ ] How does this relate to what I already know?
- [ ] Find at least two connections to familiar concepts
- [ ] Update your concept map with these connections

Learn from patterns by examining multiple examples of the concept. Search GitHub for code examples implementing the technique you're learning.

## Retention

**10. Spaced repetition** (5 minutes daily)

- [ ] Create flashcards for key concepts
- [ ] Review them using the Leitner system
- [ ] Schedule reviews at increasing intervals (1 day, 3 days, 7 days, etc.)

**11. Apply in a project** (varies)

- [ ] Incorporate the new knowledge into a personal or work project
- [ ] Start small and expand as your confidence grows
- [ ] Document your implementation process

**12. Reflect and adjsut** (10 minutes)

- [ ] Review what worked and what didn't in your learning process
- [ ] Adjust your approach for the next topic
- [ ] Celebrate progress, no matter how small

---

## Core skills to master without AI

- Algorithmic thinking
  - Basic data structures (arrays, linked lists, trees, graphs)
  - Common algorithms (sorting, searching, traversal)
  - Complexity analysis (Big O notation)
  - Problem decomposition
- Debugging fundamentals
  - Reading and interpreting error messages
  - Using breakpoints effectively
  - Tracing code execution manually
  - Formulating and testing hypotheses about bugs
- Core language proficiency
  - Syntax and semantics of your primary language
  - Memory management principles
  - Type systems and type safety
  - Control flow and error handling
- System design basics
  - Component separation and interfaces
  - State management
  - Data flow patterns
  - API design principles
- Testing discipline
  - Unit test writing
  - Test-driven development workflow
  - Identifying edge cases
  - Test coverage analysis
- Version control
  - Basic Git operations without GUI tools
  - Branching strategies
  - Conflict resolution
  - Reading and understanding commit history
- Performance optimizations
  - Identifying bottlenecks
  - Memory profiling
  - Execution time analysis
  - Resource utilization monitoring
- Security fundamentals
  - Input validation principles
  - Authentication vs. authorization
  - Common vulnerability patterns
  - Secure coding practices
  
**Practical approach**

For Technical Topics

- Decompose by functionality: Break down "debugging" into: setting breakpoints, reading stack traces, logging strategies, etc.
- Create a dependency tree: Identify which concepts depend on others
- Build a learning roadmap: Arrange subtopics from foundational to advanced

For Abstract Concepts

- Find concrete implementations: For "software design principles," look for specific codebases that exemplify them
- Reverse-engineer examples: Study well-designed systems and identify the principles at work
- Apply to your own code: Refactor an existing project using the principles you're learning

---

## 1. Break down complex topics into use cases

- Start by breaking down whatever you're trying to learn into specific use cases or bite-sized chunks that take just a few minutes to understand
- Instead of "learning observability," focus on "implementing metrics collection for a specific service"
- Rather than "mastering software design principles," try "applying the Single Responsibility Principle to one class"
- This approach makes it easier to know when you're done with each chunk, reinforcing your sense of progress

---

## Lean into your strengths

- Harness Hyperfocus
  - Identify your peak focus hours and schedule learning sessions during these times
  - Set clear, achievable goals for each hyperfocus session
  - Create a reward system for completing learning milestones
- Embrace Creative Problem-Solving
  - Apply systems thinking by considering how new concepts fit into the larger picture
  - Look for connections between what you're learning and what you already know
  - Visualize how components interact rather than focusing on isolated parts

## Practical tips

- Build a personal knowledge base
- Organize code snippets and explanations in a way that makes sense to you
- Regularly review and update your system
- Set up a reward system for completing learning milestones
- Turn learning goals into a game
- Take short walks between learning sessions to process information
- Use a standing desk while watching tutorials
- Try "walking meetings" when discussing concepts with peers

---

## Adopt a project-based approach

- Instead of abstract learning, build something concrete
- Start a small personal project using the technology you're learning
- Contribute to open-source projects that use the concepts you're studying
- Build a portfolio of mini-applications demonstrating different aspects of what you're learning
