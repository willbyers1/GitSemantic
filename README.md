🐙 GitSemantic
Commit with Confidence. An AI-powered semantic analyzer that audits your git commit messages against "Conventional Commits" standards using Google Gemini.

📸 Screenshots
<img width="1366" height="768" alt="Terminal Interface" src="https://via.placeholder.com/1366x768/0d1117/22c55e?text=GitSemantic+Terminal+UI" /> <img width="1366" height="768" alt="Audit Result" src="https://via.placeholder.com/1366x768/0d1117/ef4444?text=AI+Audit+Analysis" />

📖 Overview
GitSemantic is a developer-experience (DevEx) tool designed to maintain repository hygiene. It acts as a pre-commit check in your browser. By leveraging the Google Gemini 1.5 Flash model, it semantically understands your commit intent and verifies if it aligns with the Conventional Commits specification (feat, fix, chore, etc.).

The application features a Terminal-inspired dark UI (#0d1117), mimicking the GitHub command line experience for a seamless workflow.

✨ Key Features
🤖 Semantic Audit: Uses LLM reasoning to determine if your message accurately describes the change and uses the correct type (e.g., distinguishing a feat from a chore).

✨ Auto-Fixer: If your commit message is invalid, GitSemantic provides a one-click copyable "Fixed Version" rewritten by AI.

🔐 BYOK Architecture: "Bring Your Own Key". Your Google Gemini API Key is stored locally in sessionStorage and never hits an intermediate server.

📟 Terminal UI: A monochromatic, monospace design that feels right at home for developers.

⚡ JSON-Mode: Forces the AI to return structured data for reliable parsing and UI updates.

🛠️ Tech Stack
Core: HTML5, Vanilla JavaScript (ES6+)

Styling: Tailwind CSS (via CDN)

AI Engine: Google Gemini API (REST)

Font: Monospace / Fira Code style

🚀 Getting Started
Clone the repository:

Bash

git clone https://github.com/WillByers/GitSemantic.git
cd GitSemantic
Run the app: Double-click index.html to open it in your browser.

🎮 Usage
Initialize: Enter your Gemini API Key when prompted.

Input: Type your raw commit message (e.g., "added login button").

Audit: Click "Audit Commit".

Action:

✅ Valid: You are good to push!

❌ Invalid: Read the reason and click the "Suggested Fix" box (e.g., "feat(auth): add login button component") to copy it.

🛡️ Privacy Note
GitSemantic is a client-side tool. No data is stored on external servers. API keys are cleared when the browser tab is closed.

📄 License
Distributed under the MIT License. See LICENSE for more information.

<div align="center">

CLICK TO USE
If the link doesn't work here is the URL: https://willbyers1.github.io/GitSemantic/

Created by Mert Batu Bülbül

💻 Computer Engineering Freshman (1st Year Student) 💻

</div>