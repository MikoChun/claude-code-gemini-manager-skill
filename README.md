# Gemini Manager

An Agent Skill that lets Claude Code act as a manager while Gemini CLI does all the coding work.

## What It Is

Claude Code = Manager/Architect (thinks, plans, reads, verifies)
Gemini CLI = Intern (implements, codes, fixes)

Claude never writes code. Instead, Claude:
- Reads and understands the codebase
- Plans what needs to be done
- Tells Gemini exactly what to implement
- Verifies Gemini's work
- Requests fixes until it's correct

## Usage

Say things like:
- "Manage the implementation of X using Gemini"
- "Drive Gemini to add feature Y"
- "Use gemini-manager skill for this task"

## How It Works

1. Claude reads files to understand the task
2. Claude tells Gemini what to implement with specific commands
3. Claude verifies what Gemini produced
4. If needed, Claude tells Gemini to fix issues
5. Loop continues until Claude is satisfied

## Installation

As a project skill: Clone this repo
As a personal skill: Copy `gemini-manager/` to `~/.claude/skills/`