AI-Powered Frontend Development Agent
------------------------------------
This project is an autonomous AI agent built with Node.js that leverages Google Generative AI (Gemini API) to automate the process of creating a complete frontend website directly from user instructions.

🔹 Key Features:

AI Agent Workflow – Implements a PLAN → EXECUTE → VALIDATE → REPEAT loop to iteratively build projects.

Dynamic Tool Calling – Uses a custom executeCommand tool to run terminal/shell commands (file creation, editing, deletion).

Cross-Platform Support – Handles Linux/macOS and Windows differently for reliable file writing (cat << 'EOF' vs PowerShell here-strings).

Automated Frontend Setup – Creates a project directory, generates index.html, style.css, and script.js, populates them with code, and validates content.

Self-Correcting Execution – Analyzes errors and retries with alternative commands until the task is successfully completed.

Interactive CLI – Takes natural language instructions from users to generate websites (e.g., “Build me a calculator app”).

🔹 Tech Stack:
Node.js, Google Generative AI (Gemini), Child Processes (exec), Readline-Sync, OS module

🔹 Use Case:

AI-driven website generation

Automated file system operations

Smart developer assistant for frontend prototyping
