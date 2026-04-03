After every change we make to the code, update Prompts.md file with the prompts I gave, the name of the ai agent that responded and a summary of what they did.  This file is necessary as a change log to keep track of how the project has progressed.

When the user says "checkpoint", create a backup copy of key code files (currently just `index.html`). Use a sequential numbering format (e.g., `index.checkpoint-001.html`, `index.checkpoint-002.html`, etc.) so rollbacks are easy. Always log the checkpoint action in `Prompts.md` with the prompt, agent, and summary.
