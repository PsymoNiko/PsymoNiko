# My Agent: A Playbook for AI-Assisted Development

This agent guides the development process from issue triage to documentation, leveraging an AI assistant at each stage.

---

### **Phase 1: Issue Triage and Organization**

**Goal:** To understand and categorize the work that needs to be done.

**Prompt to Copilot:**
> "Let's triage the issues for the `{owner}/{repo}` repository. Please list all open issues and suggest labels for each from the following categories: `bug`, `feature-request`, `enhancement`, `documentation`, `refactor`. Present them in a table for my review."

---

### **Phase 2: Project Planning and Roadmap**

**Goal:** To create a structured plan and visualize the work on a project board.

**Prompt to Copilot:**
> "Now, let's build the project plan. Based on the labeled issues, please do the following:
> 1.  Create a new project board named '[Project Name] Development Plan'.
> 2.  Add the columns: `Backlog`, `Ready to Start`, `In Progress`, `In Review`, `Done`.
> 3.  For each issue we've labeled, propose a concise task title and add it to the `Backlog`.
> 4.  Identify any large 'epic' issues (like `feature-request`) and suggest a list of smaller sub-tasks to break them down."

---

### **Phase 3: Development and Implementation**

**Goal:** To select a task and get it done with AI assistance.

**Prompt to Copilot:**
> "It's time to code. The next priority is task '[Task Title]'. To get started:
> 1.  What are the most relevant files in the codebase for this task?
> 2.  Let's think through the implementation steps. What's a good approach?
> 3.  Help me write the code for [specific part of the task]."

---

### **Phase 4: Creating the Wiki and Documentation**

**Goal:** To document the work that has been completed to build a knowledge base.

**Prompt to Copilot:**
> "The pull request for '[Task Title]' has been merged. Let's update the documentation.
> 1.  Based on the original issue and the final code, please draft a new page for the repository Wiki.
> 2.  The page should be titled '[Feature Name]' and include a brief explanation of what it does, how to use it, and a simple code example if applicable."

---

### **Phase 5: Open Discussion and Knowledge Sharing**

**Goal:** To discuss concepts, architecture, or ideas at any time.

**Prompt to Copilot:**
> "I'd like to have a discussion about the project's [concept, architecture, feature]. Based on your understanding of the repository, what are your thoughts on [specific question]?"
