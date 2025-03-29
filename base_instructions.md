# Cline AI Base Instructions

This document contains the core instructions that should be followed for all projects. These instructions establish baseline behaviors and requirements for Cline AI across all repositories.

## Real-time Collaboration with Buffer File

Each repository should maintain a buffer file (`buffer.md` in the project root) for real-time collaboration while Cline is working:

1. Before starting any task, check if the buffer file exists, and create it if it doesn't
   - Ensure the buffer file always includes an "## INSTRUCTIONS BUFFER" section at the bottom
   - This designated section is where new instructions will be placed

2. Check the "## INSTRUCTIONS BUFFER" section at these specific times:
   - At the beginning of every task
   - At the end of every chunk of work
   - Before moving to a new subtask
   - After running tests
   - Before commits

3. When new content is found in the buffer:
   - Acknowledge the new content
   - Consider how to incorporate the ideas into the current task
   - Prioritize buffer content based on relevance and impact
   - Once items have been actioned, remove them from the buffer area

4. Use the buffer for:
   - Receiving additional requirements while a task is in progress
   - Accepting feedback on work completed so far
   - Capturing ideas that may influence the current task
   - Addressing questions without interrupting the workflow

5. Buffer file structure:
   ```markdown
   # Buffer File
   
   [General notes and content can go here]
   
   ## INSTRUCTIONS BUFFER
   [New instructions will be placed here and should be checked regularly]
   ```

## Update Check Protocol

Before starting any task:

1. Verify the local shared instructions repository exists
2. Run `git -C /path/to/cline-shared-instructions pull` to get latest updates
3. Read any updated instructions before proceeding with task

## Code Quality Standards

1. Follow language-specific style guides (e.g., PEP 8 for Python)
2. Add appropriate comments and documentation:
   - Docstrings for functions, methods, and classes
   - Inline comments for complex logic
   - README files for project overviews

3. Ensure proper error handling:
   - Validate inputs
   - Use try/catch blocks where appropriate
   - Provide meaningful error messages

4. Write maintainable code:
   - Use meaningful variable and function names
   - Keep functions small and single-purpose
   - Minimize code duplication

5. Consider performance implications:
   - Optimize algorithms where necessary
   - Be mindful of memory usage
   - Consider time complexity for larger datasets

## Testing Guidelines

1. Run existing tests before finalizing changes
2. Identify and add new tests for new functionality
3. Ensure all tests pass before considering work complete
4. Consider edge cases and error conditions in tests

## Version Control Practices

1. Make meaningful commit messages that clearly describe changes
2. Use appropriate commit sizes: not too large, not too small
3. Group related changes into single commits
4. Pull latest changes before starting work
5. Push changes regularly to avoid large divergence

## File Management

1. Keep files organized according to project structure
2. Don't let files grow too large - refactor when appropriate
3. Follow project-specific naming conventions
4. Ensure consistent file encodings (UTF-8 preferred)

## Browser Testing

For web-based projects:
1. Open and test in browser when changes are complete
2. Click through key functionality to verify changes work as expected
3. Check console for errors or warnings
4. Verify responsive behavior if applicable

## Documentation Updates

1. Update documentation to reflect changes
2. Keep READMEs current
3. Document API changes
4. Update usage examples as needed
