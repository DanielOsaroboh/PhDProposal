
[ChatGPT Plus](https://chatgpt.com/)

- - No project chats
        
    

[

](https://chatgpt.com/)

Explain Obsidian to me from scratch level to professional level, step by step

  

Worked for 12s

# Obsidian: From Complete Beginner to Professional

## 1. What is Obsidian?

**Obsidian is a note-taking and knowledge-management application.**

It helps you:

- Write and store notes.
    
- Connect related ideas.
    
- Organise research, work, study and personal information.
    
- Manage projects and tasks.
    
- Create your own searchable knowledge library.
    
- Keep files on your computer instead of depending entirely on an online platform.
    

Obsidian stores most notes as ordinary `.md` Markdown files inside a folder on your device. This folder is called a **vault**. Because the files are locally stored and use a widely supported format, you retain control of them and can open them with other text-editing applications. 

A simple way to understand it is:

> **Microsoft Word creates documents.  
> OneNote creates notebooks.  
> Obsidian creates a connected personal knowledge system.**

---

# LEVEL 1 — COMPLETE BEGINNER

## 2. Understand the important Obsidian terms

### Vault

A **vault** is the main folder containing your notes and attachments.

For example:

```
Daniel's Obsidian Vault
```

Inside it, you may have:

```
Daniel's Obsidian Vault
├── Daily Notes
├── Research
├── Employment
├── Bible Study
├── Projects
├── Attachments
└── Templates
```

A vault is not a special cloud account. It is primarily a folder on your computer.

### Note

A note is normally a Markdown file ending in:

```
.md
```

For example:

```
HPHT Foam Rheology.md
```

### Markdown

Markdown is a simple method of formatting plain text.

For example:

```
# Main Heading

## Subheading

**Bold text**

*Italic text*

- First item
- Second item

1. First step
2. Second step
```

Obsidian recognises this formatting and displays it neatly. 

### Attachment

An attachment may be:

- A picture.
    
- A PDF.
    
- An audio file.
    
- A video.
    
- Another supported file.
    

Obsidian can store and embed these files inside notes. 

### Link

A link connects one note to another.

Example:

```
[[Machine Learning]]
```

This creates a connection to a note called **Machine Learning**.

### Backlink

A backlink tells you which other notes are referring to the current note.

Suppose this note:

```
HPHT Foam Rheology
```

contains:

```
This research may use [[Machine Learning]].
```

When you open the **Machine Learning** note, the Backlinks panel can show that it was mentioned inside **HPHT Foam Rheology**. 

---

## 3. Install Obsidian

1. Visit the official Obsidian website.
    
2. Download the correct version for Windows, macOS, Linux, Android or iOS.
    
3. Install it like a normal application.
    
4. Open Obsidian.
    
5. Select **Create new vault**.
    

Obsidian is free to use for personal, commercial and non-profit purposes. Obsidian Sync and Obsidian Publish are separate optional paid services. 

---

## 4. Create your first vault

When Obsidian opens:

1. Click **Create new vault**.
    
2. Enter a vault name, such as:
    

```
Daniel Knowledge Hub
```

3. Click **Browse** or **Choose**.
    
4. Select where the folder should be stored.
    
5. Click **Create**.
    

A suitable Windows location might be:

```
Documents\Obsidian\Daniel Knowledge Hub
```

Avoid placing your first vault in a complicated system folder.

---

## 5. Understand the Obsidian screen

The main screen usually contains:

### Left sidebar

This may contain:

- File Explorer.
    
- Search.
    
- Bookmarks.
    
- Tags.
    
- Ribbon commands.
    

### Centre area

This is where you:

- Open notes.
    
- Write notes.
    
- View PDFs.
    
- Open Canvas.
    
- Work with multiple tabs.
    

### Right sidebar

This may show:

- Backlinks.
    
- Outgoing links.
    
- Outline.
    
- Properties.
    
- Tags.
    

### Bottom-left settings button

The cogwheel opens **Settings**.

### Command Palette

The Command Palette allows you to search for almost any available action.

On Windows, the default shortcut is generally:

```
Ctrl + P
```

You can also pin frequently used commands or assign custom keyboard shortcuts. 

---

## 6. Create your first note

1. Click the **New note** icon.
    
2. Give the note a meaningful title:
    

```
Welcome to My Knowledge Hub
```

3. Type:
    

```
# Welcome to My Knowledge Hub

This vault contains my:

- Research work
- Employment records
- Training certificates
- Bible studies
- Personal projects
```

Obsidian automatically saves your changes. You do not normally need to click a Save button.

---

## 7. Learn basic Markdown

### Headings

```
# Heading 1
## Heading 2
### Heading 3
```

Use only one main `#` title where possible.

### Bold

```
**Important information**
```

### Italics

```
*Important information*
```

### Highlighting

```
==Important information==
```

### Bullet list

```
- Item one
- Item two
- Item three
```

### Numbered list

```
1. Download the application
2. Create a vault
3. Create a note
```

### Checklist

```
- [ ] Submit application
- [ ] Upload transcript
- [x] Prepare CV
```

An `x` marks the task as completed.

### Quotation

```
> Knowledge must be organised before it can be applied.
```

### Divider

```
---
```

### Code

Inline code:

```
Use the `print()` command.
```

Code block:

````
```python
print("Hello")
```
````

---

## 8. Create links between notes

Suppose you have a note called:

```
Machine Learning
```

Inside another note, type:

```
My research uses [[Machine Learning]].
```

To create a link:

1. Type two opening square brackets:
    

```
[[
```

2. Begin typing the note name.
    
3. Select the note from the suggestions.
    
4. Press Enter.
    

Obsidian supports both Wikilinks such as `[[Machine Learning]]` and standard Markdown links. By default, Wikilinks are usually the simplest option. Obsidian can also update internal links when a note is renamed. 

### Link to a heading

```
[[Research Proposal#Methodology]]
```

### Link to a displayed name

```
[[Machine Learning|ML]]
```

The link points to **Machine Learning**, but displays **ML**.

### Link to a specific block

You can assign a block identifier:

```
The experiment used five-fold cross-validation. ^cross-validation
```

Then link to it:

```
[[Research Methodology#^cross-validation]]
```

---

## 9. Embed one note inside another

A normal link looks like this:

```
[[Research Objectives]]
```

An embedded note uses an exclamation mark:

```
![[Research Objectives]]
```

The contents of the linked note will appear inside the current note.

You can also embed:

```
![[Research Diagram.png]]
```

```
![[Research Paper.pdf]]
```

```
![[Research Paper.pdf#page=5]]
```

---

# LEVEL 2 — ORGANISING YOUR VAULT

## 10. Create a simple folder structure

Do not create hundreds of folders immediately.

Start with:

```
00 Inbox
01 Daily Notes
02 Projects
03 Areas
04 Resources
05 Archive
06 Templates
07 Attachments
```

### What each folder means

**00 Inbox**

Temporary notes that have not yet been organised.

**01 Daily Notes**

Daily records, activities, meetings and ideas.

**02 Projects**

Work with a clear outcome or completion date.

Examples:

```
University of Adelaide PhD Application
UWS PhD Application
Electrical Engineering Job Search
```

**03 Areas**

Long-term responsibilities.

Examples:

```
Career
Research
Health Training
Faith
Finance
```

**04 Resources**

Reference information.

Examples:

```
Machine Learning
Power Systems
HPHT Foam Rheology
Bible Study
```

**05 Archive**

Completed or inactive material.

**06 Templates**

Reusable note structures.

**07 Attachments**

PDFs, pictures and other files.

You can set the attachment destination under:

```
Settings → Files and Links → Default location for new attachments
```

By default, attachments may otherwise be placed in the vault root. 

---

## 11. Folders versus links

Folders tell you:

> Where is this note stored?

Links tell you:

> What is this note connected to?

For example, a note called:

```
Uncertainty Quantification
```

may be stored under:

```
04 Resources/Research Methods
```

But it can link to:

```
[[HPHT Foam Rheology]]
[[Machine Learning]]
[[Monte Carlo Dropout]]
[[Bayesian Optimisation]]
[[PhD Proposal]]
```

Professional Obsidian use normally combines:

- A simple folder structure.
    
- Meaningful links.
    
- Properties.
    
- Search.
    
- Index notes.
    

---

## 12. Use tags properly

A tag begins with `#`.

Example:

```
#research
```

Other examples:

```
#phd
#application
#completed
#waiting
#important
```

Nested tags are also possible:

```
#status/waiting
#status/completed
#research/machine-learning
```

### Good use of tags

Use tags for broad classification or status:

```
#status/waiting
```

### Poor use of tags

Do not create a different tag for every individual subject:

```
#machinelearningalgorithmsandmethods
```

A subject is often better represented by a linked note:

```
[[Machine Learning]]
```

A useful distinction is:

- Use **links** for concepts and relationships.
    
- Use **tags** for status and broad categories.
    
- Use **folders** for storage and navigation.
    

---

## 13. Use Properties

Properties are structured information placed at the beginning of a note.

Example:

```
---
type: research-project
status: active
supervisor: Mary Gonzalez Perdomo
institution: University of Adelaide
date-created: 2026-07-20
deadline: 2026-08-15
tags:
  - phd
  - research
---
```

Properties can contain:

- Text.
    
- Numbers.
    
- Dates.
    
- Checkboxes.
    
- Lists.
    
- Links.
    
- Tags.
    

Obsidian stores note properties in YAML frontmatter and can use them for filtering, sorting and database-like views. 

### Example for an application note

```
---
type: application
institution: University of Adelaide
programme: PhD
status: interview
deadline: 2026-08-10
priority: high
---
```

### Example for a research paper

```
---
type: literature-note
author: Smith et al.
year: 2025
topic:
  - HPHT
  - foam-rheology
reviewed: false
---
```

---

## 14. Create templates

A template is a reusable note format.

First:

1. Create a folder called `06 Templates`.
    
2. Open **Settings**.
    
3. Select **Core plugins**.
    
4. Enable **Templates**.
    
5. Open the Templates settings.
    
6. Choose `06 Templates` as the template folder.
    

Templates are included as a core plugin and allow predefined material to be inserted into notes. 

### Daily-note template

```
---
type: daily-note
date: {{date}}
---

# {{date}}

## Main priorities

- [ ]
- [ ]
- [ ]

## Meetings

### Meeting 1

- Time:
- People:
- Discussion:
- Decision:
- Next action:

## Notes

## Tasks completed

- [ ]

## Reflection

## Tomorrow
```

### Research-paper template

```
---
type: literature-note
title:
authors:
year:
journal:
doi:
status: unread
topics:
---

# Paper title

## Full reference

## Research problem

## Aim

## Methodology

## Dataset

## Main findings

## Limitations

## Relevance to my research

## Important quotations

## My critical assessment

## Related notes

- [[ ]]
```

### Meeting template

```
---
type: meeting
date: {{date}}
status: completed
---

# Meeting: Title

## Participants

## Purpose

## Discussion

## Decisions

## Actions

- [ ] Task — Owner — Deadline

## Follow-up date
```

---

# LEVEL 3 — BUILDING A KNOWLEDGE SYSTEM

## 15. Use Daily Notes

A Daily Note is one note for each day.

Example:

```
2026-08-02
```

Contents:

```
# Sunday, 2 August 2026

## Priorities

- [ ] Review HPHT foam literature
- [ ] Organise Obsidian vault
- [ ] Check university email

## Notes

I learned how backlinks operate in [[Obsidian]].

## Meetings

Discussed the PhD proposal with [[Professor Gonzalez Perdomo]].

## Ideas

Create an uncertainty-aware operating-window model.
```

Daily Notes are valuable because they provide a chronological record without requiring you to decide immediately where every thought belongs.

---

## 16. Use an Inbox workflow

When information arrives:

1. Capture it in `00 Inbox`.
    
2. Give it a clear title.
    
3. Add important properties.
    
4. Link it to related notes.
    
5. Move it to the correct folder.
    
6. Add an action if required.
    
7. Archive it when no longer active.
    

Example inbox note:

```
# Idea — ML model for foam stability

Use pressure, temperature, foam quality, salinity and nanoparticle concentration to predict stability.

Related:
- [[HPHT Foam Rheology]]
- [[Machine Learning]]
- [[University of Adelaide PhD Proposal]]
```

Do not stop your work to build a perfect organisational structure every time an idea appears. Capture first; organise later.

---

## 17. Create index notes

An index note is sometimes called a:

- Map of Content.
    
- MOC.
    
- Hub note.
    
- Dashboard.
    
- Home note.
    

Example:

```
# Research Hub

## Active projects

- [[University of Adelaide PhD Proposal]]
- [[Power Systems Fault Diagnosis Proposal]]
- [[Agentic AI Research]]

## Research methods

- [[Machine Learning]]
- [[Uncertainty Quantification]]
- [[Bayesian Optimisation]]
- [[SHAP]]
- [[Cross-Validation]]

## Subject areas

- [[HPHT Foam Rheology]]
- [[Hydraulic Fracturing]]
- [[Power System Protection]]
- [[Agentic AI]]

## Literature

- [[Literature Review Index]]

## Tasks

- [ ] Complete methodology section
- [ ] Review uncertainty methods
```

This provides a controlled entry point into your vault.

---

## 18. Understand backlinks properly

Suppose you create:

```
Uncertainty Quantification.md
```

Several notes link to it:

```
[[University of Adelaide PhD Proposal]]
[[Machine Learning Methodology]]
[[Operating Window Identification]]
```

When you open **Uncertainty Quantification**, the Backlinks panel shows notes that mention it.

Backlinks help you discover:

- Where a concept has been used.
    
- Which projects depend on it.
    
- Which ideas are related.
    
- Where information may need updating.
    

Obsidian can display both linked mentions and unlinked mentions of the active note’s title. 

---

## 19. Use Graph View correctly

Graph View displays:

- Notes as circles or nodes.
    
- Links as connecting lines.
    
- Larger nodes when they have more incoming references.
    

It is a visual representation of the relationships among notes. 

However, do not spend all your time trying to make the graph beautiful.

Graph View is useful for:

- Finding isolated notes.
    
- Discovering clusters.
    
- Exploring connections.
    
- Checking whether a project is well linked.
    

It is not a substitute for:

- Good note titles.
    
- Search.
    
- Index notes.
    
- Properties.
    
- Clear writing.
    

---

## 20. Use search professionally

Open search with:

```
Ctrl + Shift + F
```

on Windows or Linux. 

### Search for a word

```
rheology
```

### Search for an exact phrase

```
"uncertainty quantification"
```

### Search for either word

```
foam OR rheology
```

### Search inside a folder

```
path:"02 Projects"
```

### Search for a tag

```
tag:#phd
```

### Search for incomplete tasks

```
task-todo:""
```

Search syntax can evolve, so use Obsidian’s search suggestions and official documentation for specialised operators.

---

## 21. Create atomic notes

An atomic note focuses mainly on one idea.

Instead of creating one extremely long note called:

```
Everything About Machine Learning
```

Create smaller notes:

```
Machine Learning
Supervised Learning
Random Forest
Artificial Neural Network
Cross-Validation
Feature Selection
Data Imbalance
SMOTE
Uncertainty Quantification
```

Then connect them:

```
[[Machine Learning]] includes methods such as [[Random Forest]] and [[Artificial Neural Network]].

Model evaluation may use [[Cross-Validation]].

Class imbalance may be managed using [[SMOTE]].
```

Atomic notes are easier to:

- Reuse.
    
- Link.
    
- Update.
    
- Search.
    
- Combine into new writing.
    

However, do not divide notes into meaningless fragments. Each note should still contain enough context to be understood.

---

## 22. Write notes in your own words

A good knowledge note should not merely copy a source.

Use this structure:

```
# Monte Carlo Dropout

## Meaning

Monte Carlo Dropout estimates model uncertainty by keeping dropout active during repeated prediction runs.

## Why it matters

It produces a distribution of predictions rather than only one point prediction.

## Application to my research

It could be used to quantify uncertainty in predicted foam viscosity under HPHT conditions.

## Limitation

It approximates Bayesian uncertainty but is not a complete substitute for a fully Bayesian model.

## Related notes

- [[Uncertainty Quantification]]
- [[Artificial Neural Network]]
- [[HPHT Foam Rheology]]
```

This transforms copied information into usable understanding.

---

# LEVEL 4 — PROJECT AND RESEARCH MANAGEMENT

## 23. Manage projects in Obsidian

Create one main note for each project.

Example:

```
---
type: project
status: active
priority: high
start-date: 2026-07-20
deadline: 2026-08-10
---

# University of Adelaide PhD Interview

## Desired outcome

Successfully explain my research preparation and proposed methodology.

## Key preparation areas

- [[Prior Research Experience]]
- [[HPHT Foam Rheology]]
- [[Hydraulic Fracturing Fluid Design]]
- [[HPHT Data Sources]]
- [[Heterogeneous Dataset Management]]
- [[Uncertainty Quantification]]
- [[Operating Window Identification]]

## Tasks

- [ ] Prepare two-minute introduction
- [ ] Review foam-quality definition
- [ ] Identify likely experimental datasets
- [ ] Prepare uncertainty implementation example
- [ ] Prepare questions for supervisor

## Documents

- [[Research Proposal]]
- [[Academic CV]]
- [[Interview Questions and Answers]]

## Next action

Review [[HPHT Data Sources]].
```

A project note should answer:

- What is the outcome?
    
- What is the current status?
    
- What is the next action?
    
- What information supports it?
    
- What decisions have been made?
    
- What is the deadline?
    

---

## 24. Manage literature reviews

A professional literature workflow could be:

### Step 1: Create a source note

```
Smith et al 2025 — HPHT Foam Stability
```

### Step 2: Record bibliographic information

```
---
type: literature-note
authors: Smith et al.
year: 2025
journal: Journal of Petroleum Science
topic:
  - HPHT
  - foam-stability
status: reviewed
---
```

### Step 3: Summarise the paper

```
## Research question

## Experimental conditions

## Inputs

## Outputs

## Model or analytical method

## Results

## Limitations

## Relevance to my research
```

### Step 4: Extract concept notes

Create separate notes such as:

```
Effect of Temperature on Foam Stability
Effect of Pressure on Apparent Viscosity
Nanoparticle-Stabilised Foam
```

### Step 5: Link the source and concept notes

```
The study found that temperature affected foam stability under the tested conditions.

Related concept:
[[Effect of Temperature on Foam Stability]]

Source:
[[Smith et al 2025 — HPHT Foam Stability]]
```

### Step 6: Link the concepts into your proposal

```
The proposed model should account for the [[Effect of Temperature on Foam Stability]].
```

This separates:

- What the paper said.
    
- What the idea means.
    
- How the idea supports your own work.
    

---

## 25. Use Canvas

Canvas gives you an open two-dimensional workspace where you can place and connect:

- Notes.
    
- Text cards.
    
- Images.
    
- PDFs.
    
- Websites.
    
- Groups.
    

Canvas files use the open `.canvas` JSON Canvas format. 

You could create a research-methodology Canvas:

```
Data Sources
     ↓
Data Cleaning
     ↓
Feature Engineering
     ↓
Model Training
     ↓
Uncertainty Quantification
     ↓
Multi-objective Optimisation
     ↓
Operating Window
     ↓
Engineering Decision Support
```

Use Canvas for:

- Research methodology.
    
- Project planning.
    
- Brainstorming.
    
- Literature mapping.
    
- Presentation planning.
    
- System architecture.
    
- Relationship diagrams.
    

Do not use Canvas as the only place where important information exists. Link its cards to proper notes.

---

## 26. Use Bases

Bases is a core Obsidian feature that creates database-like views of notes. It can display, filter, sort and edit notes based on their properties, using layouts such as tables and cards. 

For example, you could create a Base for applications:

|Institution|Programme|Status|Deadline|Priority|
|---|---|---|---|---|
|Adelaide|PhD|Interview|10 Aug 2026|High|
|UWS|PhD EEE|Under review|—|High|
|Teesside|PhD AI|Submitted|—|Medium|

Each row can correspond to an actual note.

Properties:

```
---
type: application
institution: University of Adelaide
programme: PhD
status: interview
deadline: 2026-08-10
priority: high
---
```

Bases can be used for:

- Applications.
    
- Research papers.
    
- Projects.
    
- Training certificates.
    
- Contacts.
    
- Reading lists.
    
- Job opportunities.
    
- Meeting records.
    

---

# LEVEL 5 — PLUGINS AND CUSTOMISATION

## 27. Understand core plugins

Core plugins are built into Obsidian.

Useful core plugins include:

- Backlinks.
    
- Bases.
    
- Bookmarks.
    
- Canvas.
    
- Command Palette.
    
- Daily Notes.
    
- File Recovery.
    
- Graph View.
    
- Outline.
    
- Page Preview.
    
- Properties View.
    
- Search.
    
- Tags View.
    
- Templates.
    
- Sync.
    
- Publish.
    

The available list may depend on your installed Obsidian version. 

For a beginner, enable:

```
Backlinks
Bookmarks
Canvas
Command Palette
Daily Notes
File Recovery
Graph View
Outline
Page Preview
Properties View
Search
Templates
```

---

## 28. Understand community plugins

Community plugins are third-party additions.

To install one:

1. Open **Settings**.
    
2. Select **Community plugins**.
    
3. Turn off Restricted Mode.
    
4. Click **Browse**.
    
5. Search for the plugin.
    
6. Click **Install**.
    
7. Click **Enable**.
    

Community plugins do not necessarily update automatically; users should check for updates. 

### Security warning

Community plugins can execute third-party code and inherit Obsidian’s access level. Obsidian cannot reliably restrict every plugin to narrowly defined permissions. Only install plugins you genuinely trust and need. 

Do not install 30 plugins during your first week.

Start with the standard Obsidian features. Add a plugin only when you can clearly state the problem it solves.

---

## 29. Useful professional plugin categories

Common plugin categories include:

### Task management

Used to create advanced task queries, due dates and recurring tasks.

### Calendar

Provides calendar-based navigation for daily notes.

### Dataview-style querying

Used to retrieve and display notes based on properties or metadata.

### Citation management

Useful for linking Obsidian with academic reference-management workflows.

### Diagramming

Useful for hand-drawn diagrams and visual explanations.

### Git integration

Useful for version control and remote backups.

### Templating

Useful for advanced variables, automatic titles and conditional templates.

Because community plugins are independently maintained, review their documentation, update history and security implications before depending on them.

---

# LEVEL 6 — BACKUP, SYNC AND GIT

## 30. Understand the difference between sync and backup

### Sync

Sync keeps versions of your vault available across multiple devices.

Example:

```
Laptop ↔ Phone ↔ Desktop
```

### Backup

Backup gives you a separate recoverable copy if files are:

- Deleted.
    
- Corrupted.
    
- Overwritten.
    
- Lost with the device.
    
- Damaged by a sync conflict.
    

Sync and backup are not exactly the same.

A deletion may sync to every device. A proper backup lets you restore an earlier copy.

---

## 31. Obsidian Sync

Obsidian Sync is the official paid syncing service. It is designed to synchronise vaults across devices and supports end-to-end encrypted remote vaults. 

General setup:

1. Create an Obsidian account.
    
2. Purchase a Sync plan.
    
3. Open your vault.
    
4. Enable the Sync core plugin.
    
5. Sign in.
    
6. Create or connect to a remote vault.
    
7. Select what should be synced.
    
8. Repeat the connection process on your other devices.
    

Obsidian Sync is optional. You can use Obsidian locally without it.

---

## 32. Using Git with Obsidian

Git records changes to files over time.

A Git-based workflow can provide:

- Version history.
    
- Off-device backup when pushed to a remote repository.
    
- The ability to restore earlier versions.
    
- A record of when files changed.
    
- Controlled collaboration.
    

### Important distinction

**Git** is the version-control system.

**GitHub** is an online platform that can host Git repositories.

### Basic Obsidian Git structure

Your vault may look like:

```
Daniel Knowledge Hub
├── .git
├── .obsidian
├── 00 Inbox
├── 01 Daily Notes
├── 02 Projects
└── 04 Resources
```

Obsidian stores vault-specific settings, themes, hotkeys and plugin information in a hidden `.obsidian` folder. 

### Basic manual Git workflow

Open Git Bash or Terminal inside the vault:

```
git init
```

Add files:

```
git add .
```

Create the first commit:

```
git commit -m "Create Obsidian knowledge vault"
```

Connect to a remote repository:

```
git remote add origin YOUR_REPOSITORY_ADDRESS
```

Push:

```
git branch -M main
git push -u origin main
```

For later updates:

```
git add .
git commit -m "Update research notes"
git push
```

### Before working from another computer

Run:

```
git pull
```

Then work on your files.

### After working

Run:

```
git add .
git commit -m "Update notes"
git push
```

### Never upload sensitive information publicly

Do not place these in a public repository:

- Passport copies.
    
- Bank statements.
    
- Visa documents.
    
- Medical records.
    
- Passwords.
    
- Private email correspondence.
    
- Confidential workplace information.
    
- Personally identifiable client information.
    
- Unpublished confidential research data.
    

Use a **private repository** for personal vaults.

---

## 33. Create a `.gitignore`

A `.gitignore` tells Git which files not to track.

A possible starting point is:

```
# Operating-system files
.DS_Store
Thumbs.db

# Obsidian temporary workspace files
.obsidian/workspace.json
.obsidian/workspace-mobile.json

# Trash
.trash/

# Sensitive folders
Private/
Confidential/
```

Whether you track the rest of `.obsidian` depends on your goal:

### Track `.obsidian`

Advantages:

- Plugins and settings can follow you across computers.
    
- Hotkeys and appearance can remain consistent.
    

Disadvantages:

- Device-specific settings may conflict.
    
- Plugin configurations may create noisy commits.
    

### Ignore all of `.obsidian`

```
.obsidian/
```

Advantages:

- Cleaner repository.
    
- Fewer device-specific conflicts.
    

Disadvantages:

- Settings and plugins are not restored through Git.
    

A balanced approach is often to track stable settings while ignoring workspace files.

---

## 34. Do not combine sync systems carelessly

Be cautious about simultaneously using several systems on the same vault, such as:

```
Obsidian Sync + OneDrive + Git + Dropbox
```

Multiple systems can attempt to modify the same files and may create:

- Duplicate files.
    
- Conflicts.
    
- Corrupted settings.
    
- Unclear version histories.
    

A safer setup is:

```
One primary sync method
+
One separate backup method
```

For example:

```
Obsidian Sync for device synchronisation
+
Git or scheduled backup for version history
```

---

# LEVEL 7 — PROFESSIONAL WORKFLOWS

## 35. Build a professional Home dashboard

Create:

```
Home.md
```

Example:

```
# Daniel's Knowledge Hub

## Today

- [[2026-08-02]]
- [[Current Tasks]]
- [[Waiting For]]

## Active projects

- [[University of Adelaide PhD Application]]
- [[UWS PhD Application]]
- [[Electrical Engineering Career]]
- [[Professional Training Records]]

## Main areas

- [[Research Hub]]
- [[Career Hub]]
- [[Training Hub]]
- [[Faith and Bible Study Hub]]
- [[Personal Administration Hub]]

## Recently important

- [[HPHT Foam Rheology]]
- [[Uncertainty Quantification]]
- [[Power System Protection]]
- [[Obsidian Learning Plan]]

## Inbox

- [[00 Inbox]]
```

Pin or bookmark this note.

---

## 36. Use a consistent naming system

### Daily notes

```
2026-08-02
```

### Meetings

```
2026-08-10 — Meeting with Professor Gonzalez
```

### Literature notes

```
Smith et al 2025 — HPHT Foam Rheology
```

### Projects

```
Project — University of Adelaide PhD Application
```

### People

```
Person — Professor Gonzalez Perdomo
```

### Organisations

```
Organisation — University of Adelaide
```

A consistent naming system improves:

- Search.
    
- Sorting.
    
- Linking.
    
- Retrieval.
    
- Automation.
    

---

## 37. Create people and organisation notes

### Person note

```
---
type: person
organisation: University of Adelaide
role: Professor
---

# Professor Gonzalez Perdomo

## Role

Potential PhD supervisor.

## Research interests

- HPHT foam rheology
- Energised fracturing fluids
- Reservoir engineering
- Data-driven subsurface modelling

## Meetings

- [[2026-08-10 — Meeting with Professor Gonzalez]]

## Related projects

- [[University of Adelaide PhD Application]]
```

### Organisation note

```
---
type: organisation
country: Australia
---

# University of Adelaide

## Applications

- [[University of Adelaide PhD Application]]

## People

- [[Professor Gonzalez Perdomo]]

## Documents

- [[University of Adelaide Research Proposal]]
```

---

## 38. Create a decision log

For important projects, record decisions separately.

```
---
type: decision
date: 2026-08-02
project: "[[University of Adelaide PhD Application]]"
status: accepted
---

# Decision — Use uncertainty-aware ML framework

## Context

The research must remain strongly anchored in petroleum engineering.

## Decision

Use machine learning to predict viscosity and stability while quantifying model uncertainty.

## Reason

This connects my AI experience to HPHT foam rheology and engineering decision-making.

## Alternatives considered

- Generic AI optimisation
- IoT-only monitoring
- Pure experimental rheology

## Consequences

The methodology must include credible HPHT data sources and uncertainty validation.
```

A decision log prevents repeated arguments and forgotten reasoning.

---

## 39. Create a “Waiting For” note

```
# Waiting For

- [ ] UWS application decision
- [ ] Adelaide supervisor confirmation
- [ ] Reference from former supervisor
- [ ] Transcript response from university
```

Each item can link to its project:

```
- [ ] Adelaide interview confirmation — [[University of Adelaide PhD Application]]
```

Review this note weekly.

---

## 40. Use weekly reviews

Create one weekly note:

```
2026-W31 Weekly Review
```

Template:

```
# Weekly Review — 2026-W31

## Completed

## Progress made

## Important decisions

## Problems

## Waiting for

## Projects requiring attention

## Notes to organise

## Next week's priorities

1.
2.
3.

## Files to archive

## Reflection
```

A professional system requires regular review. Otherwise, even well-organised notes become an unused storage archive.

---

# LEVEL 8 — PROFESSIONAL STANDARDS

## 41. Keep source notes separate from your conclusions

For research, distinguish among:

### Source statement

What the author reported.

### Your interpretation

What you understand it to mean.

### Your application

How it affects your work.

Example:

```
## Source finding

Smith et al. reported reduced foam half-life at higher temperatures under their tested formulation.

## My interpretation

The temperature effect may depend on surfactant type, pressure and nanoparticle concentration.

## Application to my research

Temperature should be included as an input and interaction effects should be evaluated.
```

This reduces accidental misrepresentation.

---

## 42. Record provenance

Provenance means recording where information came from.

For every important research claim, capture:

- Author.
    
- Publication year.
    
- Title.
    
- Journal or source.
    
- DOI or stable link.
    
- Page number.
    
- Date accessed where appropriate.
    

Example:

```
## Claim

Higher temperature reduced stability for the tested foam system.

## Source

Smith et al. (2025), p. 14.

## Confidence

Medium — result may be formulation-specific.
```

---

## 43. Protect confidential data

Create separate vaults where appropriate:

```
Personal Knowledge Vault
Work Vault
Research Vault
Public Notes Vault
```

Do not mix confidential work records with a vault that may later be:

- Published.
    
- Shared.
    
- Uploaded to GitHub.
    
- Given to collaborators.
    

Community plugins should also be assessed carefully because they can access material available to Obsidian. 

---

## 44. Maintain your system

Once a week:

1. Process the Inbox.
    
2. Review active projects.
    
3. Update Waiting For.
    
4. Complete or reschedule tasks.
    
5. Add missing links.
    
6. Remove useless duplicate tags.
    
7. Archive completed projects.
    
8. Check plugin updates.
    
9. Confirm backup success.
    
10. Review unresolved Git conflicts.
    

Once a month:

1. Review your folder structure.
    
2. Check orphaned notes.
    
3. Consolidate duplicate concepts.
    
4. Review installed plugins.
    
5. Test restoring a backed-up file.
    
6. Check that confidential information is properly separated.
    

---

# A RECOMMENDED VAULT FOR YOU

Based on your academic, employment and faith-related activities, this structure would be suitable:

```
Daniel Knowledge Hub
│
├── 00 Inbox
│
├── 01 Daily Notes
│
├── 02 Projects
│   ├── PhD Applications
│   ├── Job Applications
│   ├── Research Proposals
│   └── Professional Training
│
├── 03 Areas
│   ├── Career
│   ├── Education
│   ├── Research
│   ├── Faith
│   ├── Personal Administration
│   └── Professional Development
│
├── 04 Resources
│   ├── Artificial Intelligence
│   ├── Electrical Engineering
│   ├── Petroleum Engineering
│   ├── Healthcare Training
│   ├── Bible Study
│   └── Writing and Communication
│
├── 05 People
│
├── 06 Organisations
│
├── 07 Templates
│
├── 08 Attachments
│   ├── Images
│   ├── PDFs
│   └── Certificates
│
├── 09 Archive
│
└── Home.md
```

---

# YOUR FIRST SEVEN DAYS

## Day 1: Installation and basics

- Install Obsidian.
    
- Create one vault.
    
- Create five basic folders.
    
- Write three notes.
    
- Practise headings, lists and checkboxes.
    

## Day 2: Links

- Create ten notes.
    
- Connect them using `[[links]]`.
    
- Open Backlinks.
    
- Rename one note and observe the links.
    

## Day 3: Templates and Daily Notes

- Enable Templates.
    
- Create a Daily Note template.
    
- Create a meeting template.
    
- Start using Daily Notes.
    

## Day 4: Projects

- Create one project note.
    
- Add outcome, deadline and tasks.
    
- Link supporting notes.
    
- Create a Waiting For note.
    

## Day 5: Research system

- Add one research paper.
    
- Create a literature note.
    
- Extract two concept notes.
    
- Link the concepts to your research proposal.
    

## Day 6: Properties and Bases

- Add properties to projects.
    
- Add properties to literature notes.
    
- Create a simple Base or table view.
    
- Filter active projects.
    

## Day 7: Backup and review

- Decide on a sync method.
    
- Create a backup.
    
- Consider a private Git repository.
    
- Process the Inbox.
    
- Perform your first weekly review.
    

---

# The professional Obsidian principle

A professional Obsidian system is not the one with:

- The most folders.
    
- The most plugins.
    
- The most colourful graph.
    
- The most complicated dashboard.
    

It is the one where you can reliably:

1. Capture information.
    
2. Find it again.
    
3. Understand where it came from.
    
4. Connect it to relevant work.
    
5. Turn it into decisions or action.
    
6. Protect it from loss.
    
7. Maintain it without unnecessary complexity.
    

Start with notes, links, folders and templates. Add properties, Bases, Canvas, plugins and Git gradually as your real needs become clear.

  

Use or purpose of Hub

  

In Obsidian, a **Hub** is a central note that helps you navigate a subject, project, or part of your vault.

It is like a **homepage or table of contents**.

For example, a **Research Hub** may contain:

```
# Research Hub

## Active Projects
- [[University of Adelaide PhD Proposal]]
- [[Power Systems Research Proposal]]

## Research Topics
- [[Machine Learning]]
- [[HPHT Foam Rheology]]
- [[Uncertainty Quantification]]

## Literature
- [[Literature Review]]
- [[Research Papers]]

## Important Tasks
- [ ] Review methodology
- [ ] Update references
```

## Main purposes of a Hub

### 1. Easy navigation

Instead of searching through many folders, you open one Hub and access the important notes from there.

### 2. Organising related notes

A Hub brings notes from different folders together.

For example, your **Career Hub** may link to:

- [[CV]]
    
- [[Job Applications]]
    
- [[Training Certificates]]
    
- [[Interview Preparation]]
    
- [[Professional Skills]]
    

### 3. Showing the bigger picture

Individual notes contain details. The Hub shows how those notes relate to one another.

### 4. Tracking active work

A project Hub can show:

- Current status.
    
- Tasks.
    
- Deadlines.
    
- Meetings.
    
- Documents.
    
- Decisions.
    
- Next action.
    

### 5. Preventing lost notes

You may create many notes and forget where they are. Adding important notes to a Hub makes them easier to find later.

## Hub versus Folder

A **folder** stores files in one location.

A **Hub** connects related notes, even when those notes are stored in different folders.

For example:

```
02 Projects/Adelaide PhD Application.md
04 Resources/HPHT Foam Rheology.md
05 People/Professor Gonzalez.md
01 Daily Notes/2026-08-02.md
```

All these notes can appear in one:

```
University of Adelaide PhD Hub
```

## Hub versus Tag

A tag such as:

```
#research
```

groups notes broadly.

A Hub gives structure, explanation and direct links.

## Types of Hub you can create

For your own vault, useful Hubs could include:

```
Home Hub
Research Hub
PhD Applications Hub
Career Hub
Professional Training Hub
Bible Study Hub
Personal Administration Hub
```

Your main **Home Hub** can connect all the other Hubs:

```
# Daniel's Home Hub

## Main Areas

- [[Research Hub]]
- [[PhD Applications Hub]]
- [[Career Hub]]
- [[Professional Training Hub]]
- [[Bible Study Hub]]

## Today

- [[2026-08-02]]

## Current Priorities

- [ ] Prepare for Adelaide interview
- [ ] Organise training certificates
- [ ] Update job applications
```

The main purpose of a Hub is to give you **one clear starting point** instead of opening folders and searching for files every time.


- General Skills Knowledge
Below are the **key terms** for your proposed PhD work, arranged in **alphabetical order**. These are the terms you should know well for your interview.

### A

- Algorithms
    
- Aleatoric Uncertainty
    
- Apparent Viscosity
    
- Artificial Intelligence (AI)
    
- Artificial Neural Network (ANN)
    

### B

- Bayesian Hyperparameter Optimisation
    
- Bootstrapping
    
- Bubble Size Distribution
    

### C

- Calibration
    
- Carbon Dioxide (CO₂)
    
- Confidence Interval
    
- Cross-Validation
    

### D

- Data Cleaning
    
- Data Fusion
    
- Data Heterogeneity
    
- Data Normalisation
    
- Data Preprocessing
    
- Decision Support System
    
- Dimensionless Parameters
    
- Dropout
    

### E

- Ensemble Learning
    
- Epistemic Uncertainty
    
- Extrapolation
    

### F

- Feature Engineering
    
- Flowback
    
- Fluid Leak-off
    
- Foam Half-life
    
- Foam Quality
    
- Foam Rheology
    
- Foam Stability
    
- Fracture Conductivity
    
- Fracture Propagation
    

### G

- Gas Composition
    
- Gas-Liquid Ratio
    

### H

- High-Pressure High-Temperature (HPHT)
    
- Hydraulic Fracturing
    
- Hydraulic Fracturing-Fluid Design
    

### I

- Input Variables
    
- Interpretable Machine Learning
    

### J

- Journal of Natural Gas Science and Engineering
    
- Journal of Petroleum Science and Engineering
    

### K

- k-Fold Cross-Validation
    

### L

- Laboratory Data
    
- Leak-off
    
- Limited Dataset
    

### M

- Machine Learning (ML)
    
- Metadata
    
- Model Calibration
    
- Model Generalisation
    
- Monte Carlo Dropout
    
- Multi-objective Optimisation
    

### N

- Nanoparticle Concentration
    
- Nitrogen (N₂)
    
- Normalisation
    

### O

- Operating Window
    
- Optimisation
    
- Outlier Detection
    

### P

- Petroleum Engineering
    
- Prediction Interval
    
- Prediction Uncertainty
    
- Pressure
    
- Pressure Gradient
    
- Proppant
    
- Proppant Transport
    

### Q

- Quantified Confidence
    
- Quantitative Prediction
    
- Quantitative Uncertainty
    
- Quality Control
    

### R

- Random Forest
    
- Regression
    
- Reservoir Conditions
    
- Reservoir Temperature
    
- Reservoir Pressure
    
- Robust Validation
    

### S

- Salinity
    
- Shear Rate
    
- Standardisation
    
- Surfactant Concentration
    
- Support Vector Regression (SVR)
    

### T

- Temperature
    
- Thermal Stability
    
- Training Dataset
    

### U

- Uncertainty Quantification (UQ)
    
- Uncertainty-Aware Machine Learning
    

### V

- Validation Dataset
    
- Viscosity
    

### X

- XGBoost
    

---

## The **20 most important keywords** to master for your interview are:

1. Apparent Viscosity
    
2. Artificial Neural Network (ANN)
    
3. Cross-Validation
    
4. Ensemble Learning
    
5. Foam Quality
    
6. Foam Rheology
    
7. Foam Stability
    
8. High-Pressure High-Temperature (HPHT)
    
9. Hydraulic Fracturing
    
10. Hydraulic Fracturing-Fluid Design
    
11. Machine Learning
    
12. Monte Carlo Dropout
    
13. Operating Window
    
14. Pressure
    
15. Proppant Transport
    
16. Random Forest
    
17. Shear Rate
    
18. Temperature
    
19. Uncertainty Quantification (UQ)
    
20. XGBoost
    

If you can confidently explain these 20 concepts and how they relate to your proposed research, you will be well prepared for most technical questions in your PhD interview.