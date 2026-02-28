```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines are designed to ensure the development of high-quality, maintainable, and testable AI coding agents.  Adherence to these principles is crucial for the long-term success and reliability of the project.

## 1. DRY (Don't Repeat Yourself)

*   **Single Responsibility Principle:** Each agent component should have a single, well-defined purpose.  Avoid creating overly complex agents with multiple, loosely related functionalities.
*   **Module Reuse:**  All agents should be encapsulated within modules. Modules should have clearly defined inputs, outputs, and responsibilities.
*   **Abstraction:**  Use abstraction to hide implementation details.  Represent data and logic in a way that is easily adaptable.
*   **Consistent API Design:** Maintain a consistent API design across all agents. Define clear naming conventions and documentation for all methods.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimalist Code:** Strive for the simplest possible implementation.  Avoid unnecessary complexity.
*   **Readability:**  Prioritize code clarity and maintainability.  Use descriptive variable and function names.
*   **Short Functions:** Keep functions concise and focused on a single task.
*   **Avoid Over-Engineering:** Don't introduce complexity that isn't absolutely necessary to solve the problem.

## 3. SOLID Principles

*   **Single Responsibility:**  Each class/module should have a single, well-defined purpose.
*   **Open/Closed Principle:**  The agent's design should be open for extension but closed for modification.  (Future enhancements can be added without modifying existing code).
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be forced to depend on methods they don’t use.
*   **Dependency Inversion Principle:**  High-level modules should be dependent on abstractions, not concrete implementations.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Over-Implementation:** Do not add functionality that is not currently needed.  Refactor as needed.
*   **Focus on Core Requirements:** The agent should solve the core problem defined in the requirements document.
*   **Don't Implement Features Unnecessarily:** Only implement features that are explicitly required to fulfill the current needs.

## 5. Development Practices & Rules

*   **Code Style:** Use a consistent code style (e.g., PEP 8 for Python).  A style guide should be defined and followed.
*   **Commenting:**  Add clear and concise comments to explain complex logic and non-obvious code. Comments should explain *why* not *what*.
*   **Documentation:**  Document agent components, data structures, and any significant design decisions.
*   **Testing:** All agent components must be thoroughly tested.
*   **Code Review:**  All code must be reviewed by another team member before merging.
*   **Version Control:**  Use Git for version control.
*   **Static Analysis:** Employ static analysis tools (e.g., pylint, flake8) to identify potential errors and improve code quality.
*   **Unit Tests:** Aim for 80% test coverage.  A test suite must be maintained and updated regularly.
*   **Integration Tests:**  Consider integration tests to verify interactions between agents.

## 6.  File Size & Structure

*   **Maximum File Size:** 180 lines of code maximum.
*   **File Organization:**  Organize files logically and consistently. Use consistent naming conventions.
*   **Documented Submodules:** Each submodule should be documented in a separate file explaining its purpose and dependencies.

## 7.  Specific Considerations

*   **Data Structures:** Define clear and well-documented data structures for each agent component.
*   **Error Handling:** Implement robust error handling and logging.
*   **Configuration:**  Separate configuration from the code where possible.

## 8.  Testing Emphasis

*   **Unit Tests:** All agent components must have a defined set of unit tests.
*   **Test-Driven Development:**  Prioritize writing tests before implementation.
*   **Test Coverage:** 80% test coverage is a mandatory target.

These guidelines are to be considered a baseline. Adjust as needed based on project requirements and evolving standards.
```