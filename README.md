Interactive Git Command Guide with AI (Single-File Version)
A comprehensive, all-in-one web application designed to be the ultimate resource for learning and mastering Git. This tool is a self-contained, single HTML file that can be run directly in your browser. It is built for developers of all skill levels, from absolute beginners trying to understand their first command to experienced users looking for a quick reference, a practical solution, or a safe space to experiment.

The guide transforms a static list of commands into a dynamic, multi-faceted learning platform, complete with an AI assistant to answer any question.

✨ Features
This project is packed with features designed to cover every aspect of the Git learning journey:

📚 8-Tab Interface: A clean, organized layout that separates concepts for a guided learning experience.

🧠 Key Concepts: Beginner-friendly explanations of core ideas like "Repository" and "Branch" using simple analogies.

⌨️ Command Reference: A searchable and filterable database of essential Git commands, each with a clear explanation, usage, and copy-pasteable example.

🔬 Interactive Playground: A safe sandbox environment to visually experiment with commands like commit and branch and see their effect on a repository graph in real-time.

🛠️ Common Scenarios: A practical "cookbook" of step-by-step recipes for solving common real-world problems, like undoing a commit or fixing a mistake.

📄 .gitignore Generator: A handy utility to generate .gitignore files tailored to your project by selecting technologies like Node, Python, and VS Code.

🏆 Best Practices: Professional wisdom and conventions for writing great commit messages and using the Feature Branch Workflow.

🤖 AI Assistant: A floating chat window powered by the Google Gemini API. Ask it any Git-related question, paste an error message, or get a custom explanation for any concept. (Requires setup for local use, see below).

🛠️ Tech Stack
Frontend: HTML, Tailwind CSS, Vanilla JavaScript

AI: Google Gemini API

🚀 How to Use
Basic Use (Without AI)
Download the .html file.

Open the file in any modern web browser (like Chrome, Firefox, or Edge).

All features, except the AI Assistant, will work immediately out of the box.

Activating the AI Assistant (For Local Use Only)
To get the AI chat feature working on your local machine, you need to provide it with a free API key from Google.

Get Your API Key:

Visit Google AI Studio.

Sign in and click "Get API key", then "Create API key in new project".

Copy the generated key. Keep this key private!

Edit the HTML File:

Open the .html file in a text editor (like VS Code, Notepad++, or Sublime Text).

Scroll down to the <script> section near the bottom.

Find the line that says: const apiKey = "";

Paste your API key between the quotation marks, like this: const apiKey = "YOUR_API_KEY_HERE";

Save the file.

Reload the File in Your Browser: Now when you open the .html file, the AI assistant will be fully functional for your local use.

🌐 Deployment and Limitations
You can easily share this project by deploying the single .html file.

Simple Deployment: Use a drag-and-drop service like Netlify Drop or Vercel. Just drag your HTML file onto their page, and they will give you a live URL.

⚠️ Important Limitation: AI Assistant on a Live Website
The AI Assistant in this version of the code will not work when deployed to a public website.

Why? To make the AI work for local use, you have to paste your secret API key directly into the HTML file. If you upload this file to the internet, your secret key will be publicly visible to everyone. This is a major security risk, and for this reason, Google's services will block requests coming from a live website that expose a key in this way.

Solution: To make the AI work on a live server, the project needs to be refactored to use a secure server-side function that hides the API key. This single-file version is therefore best suited for offline/local use.
