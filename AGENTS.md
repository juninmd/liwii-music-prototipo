```markdown
# AGENTS.md Guidelines

These guidelines are designed to ensure the creation and maintenance of high-quality, reliable, and maintainable AI coding agents within this repository. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   **Module Design:** Each module should encapsulate a specific, well-defined responsibility. Avoid creating overly complex or intertwined modules.
*   **Reusable Components:** Design components that can be reused across multiple projects or modules. Consider creating standard components with well-documented interfaces.
*   **Abstraction:** Use abstraction to handle common patterns and variations.  Don’t over-generalize.
*   **Single Responsibility Principle:** Each function or class should have a single, clearly defined purpose.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimize Complexity:**  Keep the code as concise and straightforward as possible.  Avoid unnecessary complexity.
*   **Readability:** Prioritize clear and consistent code formatting, naming conventions, and comments.
*   **Simple Logic:** Favor simple algorithms and data structures over overly complex ones where simpler solutions suffice.
*   **Focused Design:** Each module should have a clear and understandable goal.

## 3. SOLID Principles

*   **Single Responsibility Principle:**  Each class/module should have one reason to change.
*   **Open/Closed Principle:**  The code should be open for extension but closed for modification.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without affecting the correctness of the program.
*   **Interface Segregation Principle:** Each interface should have a single reason for needing it.
*   **Dependency Inversion Principle:** High-level modules should not depend on low-level modules.  They should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Code:**  Only implement functionality that is explicitly required at the time of development.  Defer implementation until needed.
*   **Future-Proofing:** Design the code with the potential for future expansion and modifications.  Don’t prematurely add features that are not currently required.
*   **Quick Initial Development:** Focus on building a working prototype quickly before adding extensive features.

## 5. Code Generation & Structure

*   **File Length:**  Each file must be a maximum of 180 lines of code.
*   **Code Clarity:** Code should be easy to understand and follow.  Use whitespace and comments effectively.
*   **Error Handling:**  Implement basic error handling (e.g., `try...except` blocks in Python) where appropriate, but avoid excessive logging.
*   **Data Structures:** Employ appropriate data structures (e.g., lists, dictionaries, sets) to optimize performance and maintainability.
*   **Algorithm Choice:** Select efficient algorithms for the task at hand.

## 6. Testing & Coverage

*   **Unit Tests:** All functions and classes should have at least 80% test coverage.
*   **Comprehensive Tests:**  Test all edge cases, boundary conditions, and potential failure scenarios.
*   **Test-Driven Development:**  Write tests before writing the code.
*   **Mocking:**  Strictly adhere to mocking techniques.  Use mocks to isolate the functionality being tested.  Do *not* utilize simulated data or external dependencies.
*   **Integration Tests:**  Include integration tests to verify the interaction between different modules.


## 7.  Project-Specific Rules & Considerations

*   **Data Format:**  Specify data formats for input and output (e.g., JSON, CSV, protobuf).
*   **API Specification:**  If the agent interacts with external APIs, document the API specification clearly.
*   **Configuration Management:**  Consider a simple configuration management system (e.g., YAML) for parameters and settings.
*   **Versioning:**  Use version control (Git) consistently.

## 8.  Documentation

*   **Docstrings:**  All functions, classes, and modules should have comprehensive docstrings explaining their purpose, parameters, and return values.
*   **Comments:**  Use comments to clarify complex logic or explain design decisions.
*   **README:** Maintain a clear and informative README file explaining the project's goals, setup instructions, and usage examples.

By adhering to these guidelines, we aim to build a robust, maintainable, and reliable AI coding agent repository.
```