# Cline Shared Instructions

This repository contains centralized instructions for Cline AI. It helps maintain consistent behavior and knowledge management across different repositories.

## Purpose

- Provide a single source of truth for common Cline AI instructions
- Standardize knowledge management practices
- Ensure consistent behavior in repetitive tasks
- Simplify updating instructions across multiple repositories

## Structure

- `base_instructions.md`: Core shared instructions used by all repositories
- `knowledge_management.md`: Common knowledge management directives
- `templates/`: Example project-specific extensions

## Usage

### 1. Clone this repository

```bash
git clone https://github.com/wboult/cline-shared-instructions.git
```

### 2. Reference in your project-specific instructions

In your project's custom instructions file, include a reference to the shared instructions:

```markdown
# Project-Specific Custom Instructions

# IMPORTANT: Reference to shared base instructions
# Base instructions are located at: /path/to/cline-shared-instructions/base_instructions.md
# Check for updates: git -C /path/to/cline-shared-instructions pull

# Additional Project-Specific Instructions:
1. Project-specific instruction 1
2. Project-specific instruction 2
```

### 3. Add update mechanism for Cline

Ensure Cline checks for updates to the shared instructions by adding this as the first instruction in your project's custom instructions:

```markdown
FIRST INSTRUCTION: Before starting any task, check if shared instructions are up-to-date:
1. Verify the local shared instructions repository exists
2. Run `git -C /path/to/cline-shared-instructions pull` to get latest updates
3. Read updated instructions before proceeding with task
```

## Best Practices

1. Keep project-specific instructions separate from shared instructions
2. Update the shared repository when changes apply to all projects
3. Use consistent formatting across instruction files
4. Regularly pull updates to ensure all repositories use the latest instructions

## Real-time Collaboration with Buffer File

Each repository maintains a buffer file (`buffer.md` in the project root) for real-time collaboration while Cline is working. This feature allows you to:

- Add notes, ideas, or feedback while Cline is working on a task
- Provide additional requirements without interrupting workflow
- See Cline process and incorporate your input at logical checkpoints

The buffer includes a specific "INSTRUCTIONS BUFFER" section at the bottom that Cline will check at the beginning and end of every chunk of work.

A ready-to-use template is available in `buffer_template.md` with predefined sections for:
- Project Notes
- Ideas
- Feedback
- Questions
- INSTRUCTIONS BUFFER (the monitored section)

See `base_instructions.md` for detailed implementation guidelines.

## Repository Setup Prompts

### For New Repositories

For new repositories, use the `new_repo_prompt.md` file as a starting point. This prompt:

1. Guides Cline to set up proper connections to shared instructions
2. Establishes the buffer file mechanism
3. Creates appropriate knowledge management structure
4. Helps Cline understand your project structure and conventions

Simply copy the contents of `new_repo_prompt.md` into your first message to Cline when starting with a new repository.

### For Existing Repositories

For repositories that already use Cline, use the `existing_repo_prompt.md` file to integrate with the shared instructions. This prompt:

1. Helps integrate shared instructions with existing project-specific instructions
2. Sets up the buffer file mechanism
3. Adapts the knowledge management structure to the existing project
4. Preserves project-specific conventions while standardizing format

Copy the contents of `existing_repo_prompt.md` into your first message to Cline when working with an existing repository.
