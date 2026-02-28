```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines are designed to ensure the quality, maintainability, and reliability of all AI coding agent development within the AGENTS repository. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   **Module Reuse:**  All functions, classes, and modules should have single, well-defined purposes.  Avoid creating duplicated code across multiple files.
*   **Template Design:** Utilize templates for common structures and logic to reduce boilerplate.
*   **Code Libraries:**  Consider creating reusable code libraries for frequently used functionalities.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimize Complexity:**  Favor straightforward solutions over overly clever or intricate ones.
*   **Clear Logic:**  Write code that is easy to understand and follow.  Use meaningful variable and function names.
*   **Avoid Over-Engineering:**  Don't introduce unnecessary complexity unless it demonstrably improves maintainability.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have a single, well-defined responsibility.
*   **Open/Closed Principle:**  The system should be extensible through public interfaces without modifying the internal code.  (This is a more advanced concept, not enforced directly, but considered.)
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without affecting the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be forced to depend on abstractions they do not use.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Features:**  Implement only the features explicitly required by the current task.  Refactor away unused functionality.
*   **Focus on Core Requirements:** Prioritize addressing the essential requirements of the project.

## 5. Testing & Quality Assurance

*   **Mocking Only:**  All tests MUST utilize mocks and stubs for unit testing and integration testing.  No use of real implementations.
*   **Test-Driven Development:**  Write tests *before* writing the code.  Ensure tests cover all critical functionality.
*   **Comprehensive Test Suite:**  Aim for 80% test coverage across all modules.
*   **Test Documentation:**  For each test case, provide a clear description of the scenario being tested.

## 6. Code Length & Structure

*   **Maximum Code Length:**  Maximum code length per file: 180 lines.
*   **Code Formatting:**  Follow consistent code formatting (e.g., using a linter).  Use a code formatter (e.g., `black` or `formatters` package).
*   **Comments:**  Add concise comments explaining complex logic or non-obvious code sections.  Keep comments updated.

## 7. Data Handling

*   **Immutable Data:**  Use immutable data structures to minimize side effects and simplify debugging.
*   **Data Validation:**  Implement robust data validation to prevent invalid input from causing errors.

## 8.  Development Workflow

*   **Version Control:**  Use Git for version control.
*   **Code Reviews:**  Conduct thorough code reviews before merging changes.
*   **Static Analysis:**  Utilize static analysis tools (e.g., `flake8`, `pylint`) to identify potential issues.

## 9.  Specific Requirements - (Add specific requirements as needed for this AGENTS.md)

*   [Specify a particular data structure or algorithm - e.g., "Use a hash map for storing user profiles."]
*   [Define a specific API contract - e.g., "All functions must return a boolean indicating success."]
*   [Outline a particular testing strategy - e.g., "Implement a comprehensive suite of unit tests covering all core functionalities."]

## 10.  General Considerations

*   **Readability:** Prioritize code readability – use meaningful variable names, clear formatting, and concise logic.
*   **Documentation:**  Document all functions, classes, and modules thoroughly.
*   **Error Handling:** Implement proper error handling and logging.

These guidelines are a foundational framework for AGENTS.md.  Regular review and updates are crucial to maintain the project’s quality.
```