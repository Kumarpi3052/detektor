# 🛡️ detektor - Scan AI Agent Security Fast

[![Download detektor](https://img.shields.io/badge/Download-Detektor-1f6feb?style=for-the-badge&logo=github)](https://github.com/Kumarpi3052/detektor/releases)

## 🧭 What detektor does

detektor is a Windows app that checks AI agent setups for security risks.

It helps you spot:

- Prompt injection risks
- Unsafe tool access
- Weak agent permissions
- Issues in CI security checks
- Missing OpenPAKT report details

Use it to review an AI agent before it ships or before it runs in a build pipeline.

## 💻 What you need

Before you install detektor, make sure your PC has:

- Windows 10 or Windows 11
- An internet connection for the download
- At least 200 MB of free disk space
- A standard user account or admin account
- .NET Desktop Runtime if the app asks for it

If your system blocks the app, use a work or personal account that can run downloaded files.

## 📥 Download detektor

Visit this page to download the Windows release:

https://github.com/Kumarpi3052/detektor/releases

On that page, look for the latest release and download the Windows file. Most users should pick the `.exe` or `.zip` file listed under Assets.

## 🪟 Install and open on Windows

Follow these steps:

1. Open the release page in your browser.
2. Find the newest version at the top of the page.
3. Under Assets, download the Windows file.
4. If you downloaded a `.zip` file, open it and extract the contents.
5. If you downloaded a `.exe` file, double-click it to run detektor.
6. If Windows shows a security prompt, choose the option that lets you open the file.
7. Wait for the app to finish loading.

If you extracted a folder, keep the files together in the same location.

## 🔍 How to use detektor

After you open the app, use it like this:

1. Start detektor.
2. Point it to your AI agent project, build folder, or CI output.
3. Choose a scan type if the app asks for one.
4. Run the scan.
5. Review the results for:
   - Prompt injection warnings
   - Tool permission issues
   - Unsafe access patterns
   - CI security findings
6. Export or save the report if you need to share it.

If your project uses agents, tools, or prompt files, scan those first.

## 🧪 What detektor checks

detektor focuses on the most common risk areas in AI agent work:

- Prompt injection paths in prompts and agent input
- Tool permissions that give too much access
- Unsafe tool calls that may reach files, networks, or shell commands
- CI security checks that can run in builds
- OpenPAKT report output for review and audit use

This makes it useful for local review and for build-time checks.

## 📄 OpenPAKT reports

detektor can generate OpenPAKT reports for your scans.

Use these reports when you need to:

- Share results with a team
- Keep a record of a scan
- Review issues in a standard format
- Track changes over time

If you use CI, save the report as part of your build output.

## 🛠️ Common setup tips

If the app does not start:

- Try opening it again as the same user who downloaded it
- Check that the file was not blocked by Windows
- Make sure the download finished
- If you used a ZIP file, extract all files before running the app
- If Windows asks for .NET, install the runtime it names and try again

If the scan does not find your files:

- Check the folder path
- Make sure the project files are not still inside a nested ZIP folder
- Use a local copy of the project, not a cloud-only shortcut

## 🔐 Best way to use it

For the best results, scan:

- Agent prompt files
- Tool config files
- Build scripts
- CI pipeline files
- Any file that tells the agent what it can access

Run detektor before release, before merge, and before deployment.

## 📁 Typical use cases

detektor works well for:

- AI agent projects
- LLM apps with tools
- DevSecOps build checks
- Security testing in CI
- Prompt safety review
- Permission review for agent tools

It fits teams that want a simple security check before shipping code.

## 🧩 File types you may see

The release page may include one or more of these:

- `.exe` for direct run on Windows
- `.zip` for manual extract and run
- Report files from scan results
- Support files used by the app

If you are not sure which file to use, pick the Windows `.exe` or the main `.zip` package from the latest release

## ❓ Help with first run

If Windows shows a smart screen or file warning:

1. Check that the file came from the detektor releases page
2. Open the file again
3. Choose the option to run it if you trust the source

If the app opens and closes fast:

- Run it again
- Check whether a file path was entered
- Look for a scan setting that needs to be set first

If you want to keep your results:

- Save the report after each scan
- Use a clear file name with the date
- Store reports in a project folder

## 📌 Project topics

detektor covers work related to:

- agent security
- AI agents
- AI safety
- AI security
- CI security
- DevSecOps
- .NET
- LLM security
- OpenPAKT
- prompt injection
- security scanner
- security testing