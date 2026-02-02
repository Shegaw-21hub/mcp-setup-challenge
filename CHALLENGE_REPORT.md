# MCP Setup Challenge Report

## 1. Project Overview
This report documents the successful setup of the Model Context Protocol (MCP) and GitHub Copilot configuration for the 10 Academy TRP 1 challenge.

## 2. Tasks Completed
- **VS Code Update:** Manually updated Visual Studio Code to version 1.108.2 to enable native MCP support.
- **Task 1 (MCP Connection):** Configured `.vscode/mcp.json` to connect to the Tenx Analysis server and successfully authenticated via GitHub.
- **Task 2 (Agent Rules):** Created `.github/copilot-instructions.md` to define a "Senior Principal Engineer" persona, enforcing a strict "Analyze -> Plan -> Execute" workflow.
- **Task 3 (Documentation):** Created this repository to host the configuration files and project report.

## 3. Troubleshooting & Solutions
- **Update Issues:** The "Check for Updates" button was missing in my previous version; I resolved this by manually downloading and running the latest VS Code installer.
- **Network Errors:** Encountered a "Could not resolve host" error in the Git terminal. I bypassed this by using the GitHub web interface to manually create and upload the necessary folders and files.
- **Hidden Folders:** Learned the "slash trick" (`folder/file.ext`) on GitHub to create hidden directories like `.vscode` and `.github` without Windows file visibility issues.

## 4. Key Insights
- **Structured Planning:** Implementing the Senior Engineer rules changed the AI's behavior, making it provide structured plans before writing code, which improves accuracy.
- **MCP Benefits:** The live connection to the Tenx server allows the AI to use specific analysis tools, bridging the gap between local code and external feedback.
