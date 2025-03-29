# Existing Repository Setup for Cline

This is an existing repository that already uses Cline. Please help me integrate it with the centralized shared instructions:

## Integration Steps

1. Check if the shared instructions repository is available:
   - Path should be at: `/c/Dev/shared_cline_instructions`
   - If not accessible, clone from: `https://github.com/wboult/cline-shared-instructions.git`

2. Set up real-time collaboration:
   - Create a `buffer.md` file in the root directory if it doesn't exist, with this structure:
     ```markdown
     # Buffer File
     
     [General notes and content can go here]
     
     ## INSTRUCTIONS BUFFER
     [New instructions will be placed here and should be checked regularly]
     ```
   - Begin monitoring the INSTRUCTIONS BUFFER section at regular checkpoints during tasks

3. Integrate with existing project instructions:
   - Locate and analyze current project-specific instructions
   - Update to include references to shared base instructions and knowledge management directives
   - Preserve existing project-specific guidelines while standardizing format
   - Add buffer file monitoring instructions

## Knowledge Management Integration

1. Check if a knowledge store exists at `docs/project_context.md`:
   - If it exists, review and ensure it follows the standardized structure
   - If it doesn't exist, create it with appropriate sections based on project history

2. For existing knowledge store, ensure it has:
   - Project Overview section
   - System Architecture section
   - Component Documentation section
   - Known Issues section
   - Roadmap section
   - Changelog section with historical entries preserved

## Real-time Collaboration

Remember to check the `buffer.md` file at regular intervals for any new instructions or feedback I might add while you're working.

## Check for Updates

Before starting any task, ensure the shared instructions are up-to-date by running:
```
git -C /c/Dev/shared_cline_instructions pull
```

## Project Analysis

Please analyze this repository's existing Cline usage:
1. Review past interactions and patterns
2. Identify any project-specific conventions already established
3. Note any existing knowledge management practices

After analysis, provide your understanding of the current Cline setup and recommend steps to improve integration with the shared instructions.
