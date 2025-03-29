# Knowledge Management Directives

This document outlines the standardized knowledge management practices to be applied across all projects. These directives ensure that project knowledge is consistently captured, organized, and maintained.

## Project Knowledge Store

Each project should maintain a knowledge store in `docs/project_context.md` that serves as the central repository for project information.

## When to Update the Knowledge Store

Update the project knowledge store after implementing ANY significant changes to the codebase:

1. New features or enhancements
2. Bug fixes or inconsistency resolutions
3. Architectural decisions
4. Dependency/configuration changes
5. New issues discovered
6. Roadmap items completed
7. User preferences or project-specific conventions

## How to Update the Knowledge Store

When updating `docs/project_context.md`:

1. For new changes: Add dated entries to the Changelog section
2. For new features: Update the Component Documentation 
3. For architectural changes: Update the System Architecture
4. For roadmap progress: Move completed items to Changelog
5. For known issues: Add new issues and remove resolved ones

## Knowledge Capture Triggers

Certain phrases in user prompts should automatically trigger knowledge capture:

1. "Remember for future reference"
2. "Remember this for later"
3. "Make a note of this"
4. "Add this to documentation"

Proactively identify and document any information that would be useful for future development, even if not explicitly requested.

## Knowledge Store Structure

A well-organized knowledge store should include:

1. **Project Overview**: Brief description and purpose
2. **System Architecture**: Components and their relationships
3. **Component Documentation**: Detailed descriptions of individual components
4. **API Documentation**: Interfaces and usage examples
5. **Development Workflow**: Processes for development, testing, and deployment
6. **Configuration**: Environment variables, config files, etc.
7. **Known Issues**: Documented bugs or limitations
8. **Roadmap**: Planned future enhancements
9. **Changelog**: Record of changes with dates

## Documentation Quality Standards

Ensure all documentation is:

1. Clear and concise
2. Up-to-date with the current codebase
3. Properly formatted (Markdown)
4. Organized in a logical structure
5. Free of technical jargon where possible
6. Including examples where helpful

## Documentation Review Process

After completing significant work:

1. Review the knowledge store for accuracy
2. Ensure all relevant sections are updated
3. Check for consistency with the codebase
4. Verify links and references are working
