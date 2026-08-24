# The Project

This program is built around one project you start in Week 1 and ship in
Week 8: **a command-line tool of your own choosing, built in Rust.**

> [!IMPORTANT]
> **Start small, grow it weekly.** Week 1 can be a `cargo new` project that just prints something. The point isn't to design the whole tool up front — it's to have something real to apply each week's Rust concept to, so by Week 8 it's a proper tested, packaged CLI.

## What "a command-line tool" means here

The project is done when someone else can build it with `cargo build` and run it against their own input and get a useful result. A binary that only compiles on your machine with hardcoded paths is not a finished project; a CLI with a `--help` flag, error handling, and tests is.

Concretely, your application should:

* **Solve a specific problem** for a specific kind of user — you, a teammate, or someone with a similar workflow. Narrow it down: what does it do that a person would otherwise do by hand?
* **Take real input and produce real output** — files, arguments, or stdin in; a report, transformed file, or printed result out. No hardcoded sample data by Week 8.
* **Have a real command-line interface** with proper argument/option parsing (hand-rolled or via a crate like `clap`), and a `--help` flag — not just a binary you edit and recompile.
* **Handle errors, don't just panic.** Invalid input should produce a clear error message, not a crash. Use `Result`/`Option` deliberately, matching what you learned in Week 4.
* **Be tested and organized.** A `cargo test` suite covering the core logic, and code organized into a library plus a thin binary entry point, not one giant `main.rs`.

## Some directions (not a menu — pick your own)

These are here to show the shape of a good project, not to be copied directly:

* A file de-duplicator that scans a folder and reports (or removes) duplicate files
* A log or text file processor that extracts and summarizes patterns (errors, totals, counts)
* A simple task tracker that stores tasks in a local file and supports add/list/complete/delete
* A word/character count or text-statistics tool for a folder of documents
* A simple encoder/decoder or format converter (CSV to JSON, base64, etc.)

If your idea doesn't look like any of these, that's fine — the test is "would I actually run this again," not "does it match this list."

## Scoping it to 8 weeks

You don't need the full idea working in Week 1. The syllabus is built so the project grows with you:

1. **Weeks 1-2** — Pick the problem, get `cargo new` running, and write the first branching logic the problem needs.
2. **Week 3** — Add the loop-driven feature that processes a collection of items.
3. **Week 4** — Break the logic into functions and handle errors with Result instead of panicking.
4. **Week 5** — Model the project's core data as a struct with associated functions.
5. **Week 6** — Use vectors, strings, and enums/Option where they genuinely fit the data.
6. **Week 7** — Organize the code into a library plus binary, and add a test suite.
7. **Week 8** — Wire on a real CLI, polish, document, ship it publicly, and record the final demo.

If by Week 4 your project still doesn't do anything you'd actually use, that's the moment to narrow or pivot — not Week 8.

## What "done" looks like

See the [self-assessment checklist](./SELF_ASSESSMENT.md) for the concrete bar: documented, tested, organized, and public.
