<h1 align="center">Rust Fundamentals Applied Program</h1>

<p align="center">Beginner, project-based, portfolio-first Rust</p>

<div align="center">

<a href="https://ds500.paiml.com"><img src="https://img.shields.io/badge/Platform-Pragmatic_AI_Labs-blue" /></a>
<a href="https://ds500.paiml.com/mailing"><img src="https://img.shields.io/badge/Newsletter-Join-blue" /></a>
<a href="https://discord.gg/JJEcK7uzFS"><img src="https://img.shields.io/discord/973306113946681374" /></a>

</div>

<p align="center">
  <a href="https://ds500.paiml.com/learn/applied-program/rust-fundamentals"><img src="resources/applied-program.png" alt="Banner" /></a>
</p>

An 8-week, project-based, beginner program that teaches core Rust from scratch by building a real command-line tool. No prior Rust experience required — ship a working, tested CLI you can put on your resume. **Add to your calendar and start building**

<div align="center">

<a href="https://ds500.paiml.com/learn/applied-program/rust-fundamentals/calendar.html?calendar=google"><img src="https://img.shields.io/badge/Add_to_Calendar-Google-4285F4?logo=googlecalendar" /></a>
<a href="https://ds500.paiml.com/learn/applied-program/rust-fundamentals/calendar.html?calendar=outlook"><img src="https://img.shields.io/badge/Add_to_Calendar-Outlook-0078D4?logo=microsoftoutlook&logoColor=white" /></a>
<a href="https://ds500.paiml.com/learn/applied-program/rust-fundamentals/calendar.html?calendar=ics"><img src="https://img.shields.io/badge/Download-.ics-6E6E6E?logo=icalendar&logoColor=white" /></a>

</div>

<details>
  <summary><b>Table of Contents</b></summary>
  <br>

* [How this program works](#how-this-program-works)
* [Prerequisites](#prerequisites)
* [Week 1: Dev Environment, Git/GitHub Setup + Rust Basics](#week-1-dev-environment-git/github-setup--rust-basics)
* [Week 2: Variables, Control Flow & Shadowing](#week-2-variables-control-flow--shadowing)
* [Week 3: Loops & Match Control Flow](#week-3-loops--match-control-flow)
* [Week 4: Functions, Borrowing & Error Handling](#week-4-functions-borrowing--error-handling)
* [Week 5: Structs](#week-5-structs)
* [Week 6: Strings, Vectors & Enums](#week-6-strings-vectors--enums)
* [Week 7: Testing & Organizing Your Code](#week-7-testing--organizing-your-code)
* [Week 8: Build the CLI + Ship & Finalize](#week-8-build-the-cli--ship--finalize)
* [The Project](#the-project)
* [Community](#community)
* [PROJECT.md](./PROJECT.md) — full project guidance

</details>

[The Project](./PROJECT.md) · [Self-Assessment Checklist](./SELF_ASSESSMENT.md)

## How this program works

There's no grading, no enrollment gate, and no required login. Everything you need to complete the program is in this repository.

There are two ways to run through it:

* **Rolling (self-paced):** Start whenever you want. No meetings, no cohort — you work through the 8 weeks on your own schedule and self-assess your project against the [checklist](./SELF_ASSESSMENT.md).
* **Cohort:** Runs alongside a shared start date with a dedicated Discord channel and an end-of-run call where participants demo their projects to each other (peer feedback, not grading).

Each week lists a plain-language objective, supporting resources, and a demo video prompt. The video prompt is worth doing even outside a cohort — it's the habit that turns a week of work into a LinkedIn post and a portfolio entry.

> [!IMPORTANT]
> You are not required to watch or read every resource listed. Nothing here is graded. Use the content as support for your project, not as a checklist to complete for its own sake.

> [!NOTE]
> **Diversity Statement:** We share a commitment to diversity and equity, removing barriers to learning so that everyone can participate fully. This program is meant to be useful to people with a wide range of backgrounds, identities, and learning styles, whether you found it through a cohort or on your own on GitHub.

### Prerequisites

No prior Rust experience required. Basic comfort with a terminal and any programming language helps but isn't required — Rust syntax and concepts are taught starting Week 1.


**Command Line Basics**

If you've never used a terminal before, start here: [Linux and Bash for Data Engineering](https://ds500.paiml.com/course/nyu26) · [Coursera](https://www.coursera.org/learn/linux-and-bash-for-data-engineering-duke)


#### Additional support resources

* [Rust Fundamentals](https://ds500.paiml.com/course/g6u1k) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Rust For Devops](https://ds500.paiml.com/course/ex8eu) · [Coursera](https://www.coursera.org/learn/rust-for-devops)
* [Rust Data Engineering](https://ds500.paiml.com/course/9dyuw) · [Coursera](https://www.coursera.org/learn/data-engineering-rust)
* [Python and Rust with Linux Command Line Tools](https://ds500.paiml.com/course/9uu8k) · [Coursera](https://www.coursera.org/learn/python-rust-linux)
* [GitHub Fundamentals](https://ds500.paiml.com/course/mywlj) · [Coursera](https://www.coursera.org/learn/github-zero)
* [Introduction to Codespaces](https://ds500.paiml.com/course/a49jp) · [Coursera](https://www.coursera.org/learn/codespaces)


## 8-Week Syllabus


### Week 1: Dev Environment, Git/GitHub Setup + Rust Basics

1. Choose the problem your CLI tool will solve, and who it's for (see [PROJECT.md](./PROJECT.md))
2. Install Rust and set up VS Code with the Rust Analyzer
3. Learn Git basics and create your project's GitHub repository with a first commit
4. Set up Docker/dev-container basics for your Rust environment
5. Create your first Rust project with cargo and run it


* [Meet your instructor](https://ds500.paiml.com/course/g6u1k/1/1/1) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Installing RUST](https://ds500.paiml.com/course/g6u1k/1/1/4) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Overview of visual studio code](https://ds500.paiml.com/course/g6u1k/1/1/5) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Enabling the RUST Analyzer](https://ds500.paiml.com/course/g6u1k/1/1/6) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Using the RUST Analyzer](https://ds500.paiml.com/course/g6u1k/1/1/7) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Fundamentals of Codespaces](https://ds500.paiml.com/course/g6u1k/1/3/2) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Why consider version control](https://ds500.paiml.com/course/mywlj/1/1/4) · [Coursera](https://www.coursera.org/learn/github-zero)
* [Repository concepts](https://ds500.paiml.com/course/mywlj/1/1/5) · [Coursera](https://www.coursera.org/learn/github-zero)
* [The GIT command line tool](https://ds500.paiml.com/course/mywlj/1/2/2) · [Coursera](https://www.coursera.org/learn/github-zero)
* [Committing and pushing changes](https://ds500.paiml.com/course/mywlj/1/2/5) · [Coursera](https://www.coursera.org/learn/github-zero)
* [Using Docker and containers](https://ds500.paiml.com/course/a49jp/2/1/2) · [Coursera](https://www.coursera.org/learn/codespaces)


**Weekly demo video prompt:** Introduce the problem your CLI tool will solve and who it's for, show your Rust dev environment running "cargo new" and "cargo run", and show your project's GitHub repository with its first commit. Use the [Public Speaking](https://github.com/microsoft/workshop-library/tree/main/short/public-speaking) guidelines to deliver a clear demo.


### Week 2: Variables, Control Flow & Shadowing

1. Learn variable assignment, immutability, and shadowing in Rust
2. Practice if/else, loops, and match-based control flow
3. Write the first branching logic your CLI tool will need


* [Create a new RUST project](https://ds500.paiml.com/course/g6u1k/2/1/2) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Basic components of RUST code](https://ds500.paiml.com/course/g6u1k/2/1/4) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Variable assignment and Immutability](https://ds500.paiml.com/course/g6u1k/2/1/5) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Basics of control flow](https://ds500.paiml.com/course/g6u1k/2/1/6) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Shadowing variables](https://ds500.paiml.com/course/g6u1k/2/1/7) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)


**Weekly demo video prompt:** Show a piece of control flow (if/match) you wrote this week and explain the decision it makes.


### Week 3: Loops & Match Control Flow

1. Learn while loops, for loops, and break/continue
2. Use match as Rust's primary control-flow tool
3. Add a loop-driven feature to your CLI tool (e.g. processing a list of items)


* [Introduction to loops](https://ds500.paiml.com/course/g6u1k/2/2/2) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Other conditional statements](https://ds500.paiml.com/course/g6u1k/2/2/3) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [The while loop](https://ds500.paiml.com/course/g6u1k/2/2/4) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [The for loop](https://ds500.paiml.com/course/g6u1k/2/2/5) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Break and continue statements](https://ds500.paiml.com/course/g6u1k/2/2/6) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Match control flow](https://ds500.paiml.com/course/g6u1k/2/2/7) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)


**Weekly demo video prompt:** Demo the loop-driven feature you added and explain why you chose a for loop, while loop, or match.


### Week 4: Functions, Borrowing & Error Handling

1. Write functions with arguments and return values
2. Learn Rust's borrowing concept and why it prevents whole classes of bugs
3. Handle errors properly instead of using panic! everywhere


* [Simple unit functions](https://ds500.paiml.com/course/g6u1k/2/3/2) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Return values](https://ds500.paiml.com/course/g6u1k/2/3/3) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Using arguments](https://ds500.paiml.com/course/g6u1k/2/3/4) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [The Borrowing concept](https://ds500.paiml.com/course/g6u1k/2/3/5) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Using panic](https://ds500.paiml.com/course/g6u1k/2/3/6) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Error handling](https://ds500.paiml.com/course/g6u1k/2/3/7) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)


**Weekly demo video prompt:** Explain a borrowing error the compiler caught for you this week, and how you fixed it.


### Week 5: Structs

1. Define structs and create instances
2. Add associated functions and constructors
3. Model your CLI tool's core data as a struct


* [Defining Structs](https://ds500.paiml.com/course/g6u1k/3/1/2) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Creating struct instances](https://ds500.paiml.com/course/g6u1k/3/1/3) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Associated functions and Constructors](https://ds500.paiml.com/course/g6u1k/3/1/4) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Other struct uses](https://ds500.paiml.com/course/g6u1k/3/1/6) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)


**Weekly demo video prompt:** Show the struct you built for your project's data and explain one associated function on it.


### Week 6: Strings, Vectors & Enums

1. Work with String and &str, and manipulate text
2. Use vectors to store and retrieve collections of values
3. Define enums, including Option, and use them in your project


* [String and STR](https://ds500.paiml.com/course/g6u1k/3/2/2) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [String Manipulation](https://ds500.paiml.com/course/g6u1k/3/2/3) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Basics of Vectors](https://ds500.paiml.com/course/g6u1k/3/2/4) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Adding elements to Vectors](https://ds500.paiml.com/course/g6u1k/3/2/6) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Defining an ENUM](https://ds500.paiml.com/course/g6u1k/3/3/2) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [The option Enumerator](https://ds500.paiml.com/course/g6u1k/3/3/4) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Applied Enums](https://ds500.paiml.com/course/g6u1k/3/3/5) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)


**Weekly demo video prompt:** Show where your project uses a Vec and an enum (or Option), and why those were the right fit.


### Week 7: Testing & Organizing Your Code

1. Organize code into a library plus binary, using cargo and modules
2. Use crates and Cargo dependencies the right way for a growing project
3. Write unit tests for your project's core logic
4. Verify examples in your documentation with doctests


* [Creating a library with cargo](https://ds500.paiml.com/course/g6u1k/4/1/2) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Documenting your code](https://ds500.paiml.com/course/g6u1k/4/1/3) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Extending with modules](https://ds500.paiml.com/course/g6u1k/4/2/3) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Verify code with Doctest](https://ds500.paiml.com/course/g6u1k/4/2/4) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Introduction to testing in RUST](https://ds500.paiml.com/course/g6u1k/4/3/3) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Writing tests for your code](https://ds500.paiml.com/course/g6u1k/4/3/4) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Creating and using modules in RUST](https://ds500.paiml.com/course/9uu8k/1/4/7) · [Coursera](https://www.coursera.org/learn/python-rust-linux)
* [Working with Dependencies and libraries in RUST](https://ds500.paiml.com/course/9uu8k/1/4/9) · [Coursera](https://www.coursera.org/learn/python-rust-linux)
* [Using Crates io for RUST](https://ds500.paiml.com/course/9uu8k/1/4/10) · [Coursera](https://www.coursera.org/learn/python-rust-linux)
* [Ownership and Lifetimes](https://ds500.paiml.com/course/9dyuw/2/1/11) · [Coursera](https://www.coursera.org/learn/data-engineering-rust)


**Weekly demo video prompt:** Run "cargo test" live and explain what one test verifies and why it matters.


### Week 8: Build the CLI + Ship & Finalize

1. Wire a real command-line interface onto your project's logic, with subcommands, arguments, and environment variables
2. Run your project against the [self-assessment checklist](./SELF_ASSESSMENT.md)
3. Publish the repository publicly and write a short portfolio/LinkedIn post linking to it


* [Your first CLI in RUST](https://ds500.paiml.com/course/g6u1k/5/1/3) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Working with user input arguments and options](https://ds500.paiml.com/course/g6u1k/5/1/4) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Expanding with modules and libraries](https://ds500.paiml.com/course/g6u1k/5/1/5) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Managing errors and Panics](https://ds500.paiml.com/course/g6u1k/5/1/6) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Rust CLI best practices](https://ds500.paiml.com/course/g6u1k/5/1/7) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)
* [Creating a command line tool with sub commands in RUST](https://ds500.paiml.com/course/9uu8k/2/1/2) · [Coursera](https://www.coursera.org/learn/python-rust-linux)
* [Adding environment variables to your command line tool in RUST](https://ds500.paiml.com/course/9uu8k/2/1/8) · [Coursera](https://www.coursera.org/learn/python-rust-linux)
* [Release your RUST application to Crates io](https://ds500.paiml.com/course/9uu8k/2/2/5) · [Coursera](https://www.coursera.org/learn/python-rust-linux)
* [Crawling the Filesystem](https://ds500.paiml.com/course/ex8eu/3/1/3) · [Coursera](https://www.coursera.org/learn/rust-for-devops)
* [Building a RUST CLI to Parse files](https://ds500.paiml.com/course/ex8eu/3/1/4) · [Coursera](https://www.coursera.org/learn/rust-for-devops)


**Weekly demo video prompt:** Give a full demo of the finished CLI tool, what it does, and one thing you'd add next if you kept working on it.

Finish the project: publish the repository, run it against the [self-assessment checklist](./SELF_ASSESSMENT.md), and write a short portfolio/LinkedIn post pointing at the repo. Rolling learners get a closing email when they hit this week; cohort learners present on the end-of-run call instead of (or in addition to) posting.


## The Project

The whole program is built around a single project you start in Week 1 and ship in Week 8: a command-line tool of your own choosing, built in Rust. See [PROJECT.md](./PROJECT.md) for what that means and how to scope it, and the [self-assessment checklist](./SELF_ASSESSMENT.md) for what "done" looks like.

> [!IMPORTANT]
> **Pick a problem you actually have**, not a toy exercise you'll abandon. A tool you'd genuinely use again is easier to stay motivated on for 8 weeks — details in [PROJECT.md](./PROJECT.md).

The primary two resources for building an LLM solution on a local API:

1. [Rust Fundamentals](https://ds500.paiml.com/course/g6u1k) · [Coursera](https://www.coursera.org/learn/rust-fundamentals)



#### Rust References

* [Rust by example](https://ds500.paiml.com/course/sgu8g/1/3/9)
* [Rust Data Engineering](https://ds500.paiml.com/course/9dyuw) · [Coursera](https://www.coursera.org/learn/data-engineering-rust)
* [Rust For Devops](https://ds500.paiml.com/course/ex8eu) · [Coursera](https://www.coursera.org/learn/rust-for-devops)


### Referenced Media and Resources

* [GitHub Codespaces](https://github.com/features/codespaces)


<details>
<summary><b>Optional supplementary readings & media</b></summary>

* [Python and Rust with Linux Command Line Tools](https://ds500.paiml.com/course/9uu8k) · [Coursera](https://www.coursera.org/learn/python-rust-linux)
* [Linux and Bash for Data Engineering](https://ds500.paiml.com/course/nyu26) · [Coursera](https://www.coursera.org/learn/linux-and-bash-for-data-engineering-duke)

</details>

## Community

Join the shared PAIML Discord to ask questions, share progress, and post your weekly demos. If you're in a cohort, you'll also get invited to a dedicated channel for your run, alongside the shared server.
