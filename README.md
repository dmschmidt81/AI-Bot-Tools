# AI Bot Tools

This repository contains a growing collection of AI-powered educational, administrative, and personal workflow tools designed to solve specific problems with structured roles, rules, approvals, and task-focused behavior.

Rather than using AI as a general-purpose chatbot, this project explores how carefully designed assistants can support teaching, student learning, test preparation, communication, and repeatable professional workflows.

## Purpose

Each bot is built around a defined use case and includes instructions that control:

- Role and purpose
- Expected behavior
- Boundaries and limitations
- Workflow sequence
- Approval points
- Source verification
- Student interaction rules
- Output expectations
- Handoffs between tools

The goal is to make AI behavior more predictable, useful, and accountable.

## Current Tools

### AP Computer Science A

Tools designed to support Java programming instruction and AP Computer Science A coursework.

- `ApCsaTestPrep.md` — AP Computer Science A test-preparation assistant
- `CompScieWarmUp.md` — Computer science warm-up and skill-development assistant
- `HomeworkHelper.md` — AP CSA homework coach designed to guide students through assignments without simply completing the work for them

### AP Test Prep

Tools designed around structured AP course preparation, reasoning, and feedback.

- `ApStatsTestPrep.md` — AP Statistics test-preparation assistant focused on reasoning, scoring, and AP-style expectations

### Administrative Tools

Tools designed to support school communication and administrative workflows.

- `C3comm.md` — Assistant for organizing and drafting C3 staff communications using defined procedures and exceptions

### Personal Workflow Tools

Tools designed to support repeatable professional and career workflows.

- `RandyResume.md` — Resume and cover-letter workflow that verifies sources, prevents unsupported claims, requires approval before document creation, and produces a structured handoff for job tracking
- `EmailAssist.md` — Email workflow that reviews job-related messages, connects them to a job tracker, proposes updates, requires approval before changes, and protects against outdated status information overwriting newer information

### Shared AI Template

- `AiTemplate.md` — Reusable starting structure for building additional AI assistants with consistent roles, workflows, and boundaries

## Design Philosophy

### Support Thinking Instead of Replacing It

Educational assistants should help students understand, plan, attempt, test, debug, and explain their work.

The goal is for the student to finish thinking:

> “I understand how I solved this.”

not:

> “The AI completed my assignment.”

### Use Clear Roles and Constraints

Each assistant is designed for a specific responsibility rather than being expected to handle every possible task.

Clear constraints make behavior easier to test, refine, and trust.

### Verify Before Acting

Where accuracy matters, assistants are instructed to distinguish verified information from assumptions and missing information.

Several workflows include explicit approval gates before changing data, creating final documents, or taking follow-up actions.

### Build Reusable Workflows

Common design patterns are separated into reusable structures so new assistants can be developed more consistently.

Some tools are also designed to hand verified information to another tool, creating a larger workflow rather than a collection of isolated prompts.

## Project Structure

```text
AI-Bot-Tools
│
├── Bots
│   ├── APCSA
│   │   ├── ApCsaTestPrep.md
│   │   ├── CompScieWarmUp.md
│   │   └── HomeworkHelper.md
│   │
│   ├── APTestPrep
│   │   └── ApStatsTestPrep.md
│   │
│   ├── Admin
│   │   └── C3comm.md
│   │
│   ├── Personal
│   │   ├── EmailAssist.md
│   │   └── RandyResume.md
│   │
│   └── AiTemplate.md
│
└── README.md
```

## Skills Demonstrated

This project reflects work in:

- AI instruction and prompt design
- Requirements analysis
- Workflow and system design
- Approval and verification logic
- Educational technology
- Instructional design
- Structured problem solving
- Java and AP Computer Science A curriculum support
- AI-assisted administrative workflows
- Career workflow automation design
- Iterative testing and refinement
- Git and GitHub version control

## Current Development

This repository is an active work in progress.

I am continuing to refine the assistants, improve reusable design patterns, test workflow behavior, and expand the project into additional educational, administrative, and professional use cases.

## Background

I am a high school computer science and technology educator with a previous background in mathematics education who is transitioning toward professional software development.

This project combines my experience in education, curriculum design, computer science, AI experimentation, and workflow design while giving me a structured environment for developing and documenting practical AI systems.
