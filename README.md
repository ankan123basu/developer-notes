# developer-notes

A collection of concise software development notes, best practices, and engineering guidelines for Software Development Engineers.

## Engineering Best Practices for Freshers & SDE Interns

### 1. Technical & Engineering Excellence 🛠️
- **Financial & High-Precision Calculations**:
  - Never use standard floating-point numbers (`float` / `double`) for monetary or high-precision calculations to avoid rounding errors.
  - Use fixed-point integer representation (e.g., smallest currency units like cents or paisa) or specialized decimal libraries (e.g., `Decimal.js`, `bignumber.js`, `BigDecimal`).
- **Data Privacy & Security**:
  - Never log Sensitive Personal Identifiable Information (PII), authentication tokens, or private credentials.
  - Mask sensitive data in log outputs and maintain strict environment variable security (never commit `.env` files).
- **Self-Review Pull Requests**:
  - Always review your own code diff line-by-line on GitHub before requesting peer reviews.
  - Ensure all linters, static analysis tools, and automated unit tests pass prior to review.
- **Small & Atomic Commits**:
  - Keep pull requests concise and focused on a single feature or bug fix. Smaller PRs reduce risk and simplify code reviews.

### 2. Codebase Navigation & Workflows 💻
- **Trace Execution End-to-End**:
  - Before modifying existing code, trace execution end-to-end across layers (UI → API → Business Logic → Database / External Services).
  - Understand historical context and architectural patterns before refactoring existing implementations.
- **Test-Driven Development & Edge Cases**:
  - Write unit and integration tests for critical business rules and edge cases early in the development lifecycle.
- **Maintain Internal Documentation**:
  - Document setup workflows, API contracts, and non-obvious configurations for team clarity and reference.

### 3. Professional Communication & Collaboration 🚀
- **Structured Problem-Solving (The 20-Minute Rule)**:
  - Spend 15–20 minutes attempting to isolate and debug issues independently.
  - When seeking assistance, articulate the context clearly: expected behavior, actual behavior, steps tried, error logs, and your current hypothesis.
- **Effective Daily Standup Updates**:
  - Structure status reports clearly:
    1. **Completed**: Tasks and tickets closed.
    2. **In Progress**: Active work items for the day.
    3. **Blockers**: Dependencies, missing specifications, or environment issues.
- **Active Listening & Note-Taking**:
  - Maintain meeting notes during 1-on-1s, design reviews, and technical discussions to minimize redundant clarifications.

### 4. Continuous Growth & Mindset 📈
- **Code Quality Over Quantity**: Focus on readability, performance, and long-term maintainability rather than raw output volume.
- **Proactive Feedback Seeking**: Regularly ask senior engineers and mentors for constructive feedback on PRs and engineering practices.
- **Reliable Communication**: Raise blockers and potential deadline adjustments early to keep team workflows transparent.

## Development Resources

A concise collection of notes, references, and useful resources for software development.

## Project Structure

Documentation is organized by topic to make development references easier to navigate.

## Contribution Guidelines

Contributions should be focused, clearly documented, and easy to review.
