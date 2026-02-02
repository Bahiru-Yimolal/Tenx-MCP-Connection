# Task 3: Documentation - MCP Setup Challenge

## 1. What I Did
I created and updated the `.github/copilot-instructions.md` file to guide GitHub Copilot in Agent Mode according to best practices for AI coding assistants. The rules I added cover:

- Coding Style (camelCase, indentation, line length, docstrings)
- AI Behavior (explanations, alternative solutions, example usage)
- Communication Style (clear, concise, commented)
- Best Practices (readable, maintainable, efficient code, edge case handling)
- Interaction Rules (reasoning logs for MCP, aligned with my intent)

## 2. What Worked
- Copilot followed **camelCase naming** and 2-space indentation.
- Docstrings and example usage were automatically included in generated functions.
- The rules file successfully guided Copilot in Agent Mode for basic Python and JavaScript functions.

## 3. What Didn't Work
- Copilot did not always provide **alternative solutions** automatically.
- Reasoning explanations sometimes had to be explicitly requested in prompts.
- Handling of complex edge cases required manual refinement.

## 4. Insights Gained
- Defining rules in `.github/copilot-instructions.md` significantly influences the AI’s coding behavior.
- Rules allow consistent coding style and better alignment with my intent.
- Testing and refining the rules iteratively improves AI performance and ensures interactions are logged correctly by the MCP server.
- Even a simple rules file can enhance collaboration with AI assistants.

## 5. Artifacts Included
- `.github/copilot-instructions.md` (final rules file)
- Example queries and Copilot outputs used for testing
- Screenshots showing Copilot following rules (optional)
- GitHub repository link: [INSERT YOUR PUBLIC REPO LINK HERE]

---

**Note:** My Tenx MCP connection was active throughout the assessment, ensuring all interactions with the AI agent were logged automatically.
