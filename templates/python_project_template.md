# Python Project Custom Instructions for [PROJECT NAME]

# IMPORTANT: Reference to shared base instructions
# Base instructions are located at: /path/to/cline-shared-instructions/base_instructions.md
# Knowledge management directives: /path/to/cline-shared-instructions/knowledge_management.md
# Buffer file for real-time collaboration: Create and monitor buffer.md in project root
# Check for updates: git -C /path/to/cline-shared-instructions pull

# FIRST INSTRUCTION: Before starting any task, check if shared instructions are up-to-date:
1. Verify the local shared instructions repository exists
2. Run `git -C /path/to/cline-shared-instructions pull` to get latest updates
3. Read updated instructions before proceeding with task

# Python Project-Specific Instructions:

## Project Overview
[Brief description of the Python project and its purpose]

## Technology Stack
- Python version: [e.g., 3.10+]
- Key libraries: [List main dependencies]
- Environment management: [Poetry/Pipenv/venv/etc.]
- Database: [SQLAlchemy/Django ORM/Raw SQL/etc.]

## Project Structure
- `/src` or package directory: Main source code
- `/tests`: Test files
- `/docs`: Documentation
- `/scripts`: Utility scripts
- `requirements.txt` or `pyproject.toml`: Dependency management

## Python-Specific Development Guidelines

1. Follow PEP 8 style guidelines
2. Use type hints for better code readability
3. Add docstrings to all functions, classes, and modules
4. Use appropriate error handling with specific exceptions
5. Organize imports according to PEP 8 (stdlib, third-party, local)
6. Prefer explicit over implicit code

## Testing Requirements
1. Maintain test coverage above [Target]%
2. Include unit tests for all new functionality
3. Run tests with `pytest tests/`
4. Test edge cases and error conditions

## Performance Considerations
1. Consider time and space complexity for algorithms
2. Use appropriate data structures
3. Implement caching where beneficial
4. Profile code for bottlenecks when needed

## Environment Setup
1. [Instructions for setting up development environment]
2. [Required environment variables]
3. [Virtual environment setup]

## Deployment Process
1. [Pre-deployment checks]
2. [Deployment step 1]
3. [Post-deployment verification]

## Python Code Quality Tools
- Linting: [flake8/pylint/etc.]
- Formatting: [Black/yapf/etc.]
- Type checking: [mypy/pyright/etc.]
- Security scanning: [bandit/safety/etc.]

## Important Project Resources
- Documentation: [Link or path]
- API references: [Link or path]
- Development guides: [Link or path]
