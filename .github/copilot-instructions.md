# GitHub Copilot Agent Instructions

## 1. Coding Style
- Use **camelCase** for all variable and function names.
- Use **2-space indentation**.
- Keep lines **under 80 characters**.
- Include **JSDoc comments** for all functions.
- Avoid unnecessary imports or console.log in production code.

## 2. AI Behavior
- Always explain your reasoning before giving the final code.
- Suggest **at least two alternative solutions** if possible.
- When completing functions, include **example usage and tests**.
- Ask clarifying questions if the prompt is ambiguous.
- Do not change the programming language unless instructed.

## 3. Communication Style
- Keep explanations clear and concise.
- Provide comments in code where appropriate.
- Use consistent terminology.

## 4. Best Practices
- Follow **modern coding best practices** for the requested language.
- Ensure code is **readable, maintainable, and efficient**.
- Handle **edge cases** where possible.
- Include proper error handling and validation if relevant.

## 5. Interaction Rules
- Always log the **reasoning and approach** in a way the MCP server can capture.
- Align code suggestions with the user’s intent and previous patterns.
- Avoid generating unnecessary boilerplate unless explicitly requested.

---

# Notes for MCP Logging
- Each code suggestion should be **self-contained and testable**.
- Ensure the AI follows instructions in this file closely.
- Update instructions if AI behavior does not match expectations.
