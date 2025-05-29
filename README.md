# TR1Remastered – QA Checklist & Bug Reports


### 🧠 Why Tomb Raider 1?
Due to its recognizable mechanics and clean structure, TR1 serves as a perfect foundation for building clear, consistent, and scalable checklist. 
My additional experience with the Tomb Raider Level Editor provided insight into how certain mechanics function under the hood.
To ensure a thorough and relevant checklist and bug reports, I also researched various community forums to identify the most common bugs and edge cases encountered by players.


**Note:** This is a fan-made project created for portfolio purposes and is not affiliated with the official developers of Tomb Raider 1 Remastered.

---

### ✅ Chechlist

This checklist was created for the opening “Caves” level of the Tomb Raider 1 Remastered game, using the modernized graphics mode as the visual reference. 
The goal was to build a universal QA framework that can be reused and expanded to test other levels in the game. This checklist was created based on the following design principles:


* 🎯 **One Item** = One Check – Each test case targets a single, isolated behaviour for easier tracking and debugging.


* 🔄 **Logical Flow** – Sections are arranged to match the natural gameplay progression, from level start to completion.


* 📂 **Categorized Structure** – Checks are grouped into intuitive categories (e.g., Enemies, Traps, Items) for easier navigation and test planning.


* 🚦 **Prioritization** – Tests are marked by importance (High / Medium) to help testers focus on critical issues first.


* 🗣️ **Clear and Actionable Language** – All checks are written with direct, unambiguous language to reduce guesswork.


* ➕ **Positive and Negative Test Cases** – The checklist covers both expected behaviours and scenarios where things might go wrong.


* 🧪 **Edge Cases** – Special consideration is given to unusual or extreme situations that could break intended functionality.


> 🧾 [View the checklist here → TR1_Caves_Level_QA_Checklist.md](./TR1_Caves_Level_QA_Checklist.md)

---

### 🐞 Bug Reports

Alongside the checklist, this repository includes documented bugs encountered during playthroughs of Tomb Raider I Remastered. Each bug report follows a standardized format with:

* 🧠 **Summary** - Providing a concise and informative title that clearly answers WHAT the bug is, WHERE it happens, and WHEN it occurs. Including relevant keywords to improve searchability in the bug-tracking system.

* 🔁 **Steps to Reproduce** - Listing clear, sequential steps that describe the exact player actions needed to trigger the bug. Starting each step with a verb and avoiding unnecessary context.

* 👀 **Observed vs. expected results** - Stating clearly what actually happens and what should happen.
  
* 📎  **Attached reference image(s) or video(s)** - Adding visual evidence to help developers understand and reproduce the issue, using a consistent and relevant naming convention.
  
* ⚠️ **Severity rating** - Indicating the bug’s impact on gameplay or users to help developers prioritize the issue effectively.

* 🖥️ **Environment** - Describing the technical setup where the bug occurs, including platform, game version, and any relevant hardware or settings.


> 📄 [View bug reports here → TR1 - Bug examples.md](./TR1%20-%20Bug%20examples.md)
