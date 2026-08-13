# Hands-On Codex: Agentic Coding Workflows

In this course, you'll use Codex to build a small personal habit tracker while practicing how to supervise an AI coding agent.

The application tracks three daily habits—water, walking, and reading—and includes a seven-day view, streak calculations, and local persistence.

The application itself is deliberately small. The focus of the course is the **workflow around the agent**: defining success, reviewing the plan, delegating implementation, evaluating approval requests, validating the result, and recovering when the task moves outside the intended scope.

## Course workflow

```text
Define success
      ↓
Review the plan
      ↓
Delegate the build
      ↓
Evaluate approval gates
      ↓
Verify against acceptance criteria
      ↓
Detect scope drift
      ↓
Recover selectively
      ↓
Verify again
```

## What you are building

A simple personal habit tracker that lets you:

- Track daily habits such as water, walking, and reading
- Mark and unmark habits for a given day
- See the last seven days at a glance
- Calculate consecutive-day streaks
- Preserve progress across page refreshes

The implementation is intentionally not prescribed in advance. Part of the exercise is seeing how Codex translates product requirements and acceptance criteria into implementation decisions.

## What you are learning

The application is the example. The agentic workflow is the skill.

Throughout the course, focus on how to:

- Define what “done” means before delegating
- Review an agent’s plan before code is written
- Decide which implementation choices can be delegated
- Treat approval gates as decision points, not button clicks
- Review from the acceptance criteria outward
- Distinguish useful work from work that is actually in scope
- Recover selectively when an agent goes off track
- Re-verify both behavior and repository state after recovery

## Repository guide

```text
prompts/
  Reusable prompts demonstrated throughout the course.

LEARNER_GUIDE.md
  Overview of the project and the agentic workflow.

Application files
  Created with Codex as the course progresses.
```

## Key ideas

> **The goal isn’t maximum autonomy. It’s the right amount of autonomy for the risk of the task.**

> **Review from the acceptance criteria outward.**

> **Useful is not the same thing as in scope.**

> **The command and the intent are two different things to review.**

For recovery, remember:

> **Interrupt. Inspect. Preserve. Revert. Restate. Verify.**
