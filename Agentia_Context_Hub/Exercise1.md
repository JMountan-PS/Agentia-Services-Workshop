# Exercise 1: Build and Navigate Your Workspace

## Overview

This is your first hands-on exercise with Agentia Context Hub. By the end of this exercise you will have created a fully configured workspace, explored every major area of the interface, and developed a foundational understanding of what workspaces are, why they exist, and how they change the quality of your AI-assisted work.

**Estimated Time:** 45-60 minutes
**Platform Access Required:** Yes. Log in at your Copado AI Platform URL before starting.
**Proof Required:** Screenshots at each checkpoint plus written answers to comprehension questions.

---

## Goals

By the end of this exercise you will have:

- Created a personal workspace scoped to CRT training
- Navigated and identified every major panel and feature in the Context Hub UI
- Understood the difference between a workspace and a general chat session
- Understood what knowledge sources are and how to manage them
- Understood the difference between instructions and knowledge source documents
- Understood the difference between uploading a file to a chat versus to a workspace

---

## Prerequisites

- [ ] Exercise 0 is complete and your training path is locked
- [ ] You have access to the Copado AI Platform and can log in
- [ ] You have Chrome or a modern browser available
- [ ] You have completed the onboarding confirmation with your AI Training Coach

---

## Background: What Is a Workspace?

> **Read this section before touching the platform. Your comprehension questions will draw from it.**

A workspace in Agentia Context Hub is a persistent, configured environment for AI-assisted work. Think of it as the difference between walking into a fully equipped, organized office versus sitting down at a blank desk with no tools, no files, and no context about what you are supposed to be doing.

When you chat with an AI in a general session, the AI starts fresh every time. It has no memory of your previous conversations, no knowledge of your organization's standards, no awareness of your tools or processes, and no instructions about how to behave. Every response is generic because the AI has no specific context to work from.

A workspace changes all of that. It is a persistent container that holds:

- **Instructions (System Prompt):** A set of directives that define the AI's role, behavior, tone, and scope. The AI reads these instructions at the start of every conversation in the workspace. This is the single highest-leverage configuration available to you.
- **Knowledge Sources:** Documents, files, and connected data sources that the AI can reference when generating responses. These ground the AI in your specific context rather than its general training data.
- **Integrations:** Live connections to external systems such as Salesforce orgs, Git repositories, Jira, and Azure DevOps. These allow the AI to access real, current data from your environment rather than relying on static documents alone.
- **Saved Prompts:** Reusable prompt templates that standardize how you interact with the AI for recurring tasks.

**Why does this matter for your work?**

The quality of an AI's output is directly proportional to the quality of the context it has been given. A workspace is the mechanism for providing that context consistently, across every conversation, without having to re-explain your situation every time you open a new chat.

For CRT specifically, a well-configured workspace means the AI already knows your naming conventions, your tagging strategy, your library preferences, your org structure, and your development standards before you type a single word. That is the difference between an AI that gives you generic Robot Framework advice and one that generates scripts that match your team's actual practices.

> **Citation:** Copado AI Platform documentation describes workspaces as "persistent environments that combine instructions, knowledge, and integrations to ground AI agents in org-aware context, enabling them to operate with full situational awareness rather than producing generic output."

> **Citation:** From the Copado Robotic Testing Core Training materials: "Building GOOD CONTEXT is a super important priority for AI Context Hub training. Focus on teaching how to create high-quality contextual documents and workspace setup that supports effective AI-assisted work."

---

## Section 1: Create Your Workspace

### Step 1.1: Navigate to the Workspace Area

1. Log in to the Copado AI Platform.
2. Locate the **Workspaces** section in the main navigation. This may appear as a sidebar item, a top navigation tab, or a home screen panel depending on your org's configuration.
3. Review any existing workspaces visible to you. Note their names and whether they appear to be personal or shared workspaces.

### Step 1.2: Create a New Workspace

1. Click **New Workspace** or the equivalent create button.
2. Fill in the following fields:
    - **Name:** `[YourName] CRT Training Workspace`
    - **Description:** `Personal workspace for Agentia Pro CRT training exercises. Scoped to Copado Robotic Testing content and best practices.`
3. Leave all other settings at their defaults for now. You will configure them in later exercises.
4. Save the workspace.

> **Checkpoint 1:** Take a screenshot of your newly created workspace showing the name and description clearly. Submit it to your AI Training Coach with the message: `"Checkpoint 1 complete."`

---

## Section 2: Navigate the UI

Work through each panel below in order. For each one, read the description, explore the area in your workspace, and take the required screenshot.

### Step 2.1: Chats Panel

The Chats panel is your conversation history within the workspace. Every conversation you start inside a workspace is stored here, separate from any general chat sessions outside the workspace.

**Explore the following:**
- How to start a new chat inside the workspace
- How to view and return to a previous conversation
- How to pin, rename, or delete a chat (if available in your org)
- How the chat history inside a workspace differs from your general chat history

> **Checkpoint 2:** Take a screenshot of the Chats panel inside your workspace. Submit it with the message: `"Checkpoint 2 complete."`

### Step 2.2: Prompts Panel

Saved prompts are reusable templates that standardize how you interact with the AI for recurring tasks. Instead of typing the same detailed prompt every time, you save it once and reuse it with a single click.

**Explore the following:**
- Where saved prompts are stored in the workspace
- How to create a new saved prompt
- Whether prompts in this workspace are visible outside of it
- Any prompt variables or placeholders available (e.g., `{{input}}` style fields)

> **Checkpoint 3:** Take a screenshot of the Prompts panel. If you can create a test prompt, do so and include it in the screenshot. Submit it with the message: `"Checkpoint 3 complete."`

### Step 2.3: Documents and Knowledge Sources Panel

This is one of the most important panels in the workspace. Knowledge sources are the documents, files, and data connections that the AI can reference when generating responses inside this workspace.

**Explore the following:**
- Where the Documents or Knowledge Sources panel is located
- What knowledge sources are currently available or pre-loaded
- How to upload a new document to the workspace
- How to enable or disable an individual knowledge source
- Whether there is a way to preview or view the content of an uploaded document

> **Checkpoint 4:** Take a screenshot of the Documents or Knowledge Sources panel showing at least one knowledge source visible. Submit it with the message: `"Checkpoint 4 complete."`

### Step 2.4: Integrations Panel

Integrations connect the workspace to live external systems. Unlike static documents, integrations pull real-time data from connected platforms, giving the AI access to current information rather than a snapshot.

**Explore the following:**
- What integrations are available in your workspace (Salesforce, Git, Jira, Azure DevOps, etc.)
- The connection status of any existing integrations
- What information is required to set up a new integration
- How an integration differs from an uploaded document as a knowledge source

> **Checkpoint 5:** Take a screenshot of the Integrations panel showing the available integration options. Submit it with the message: `"Checkpoint 5 complete."`

### Step 2.5: Workspace Settings

The Workspace Settings area is where you configure the core behavior of the workspace, including the system prompt (instructions), model selection, and access controls.

**Explore the following:**
- Where the Instructions or System Prompt field is located
- The character or token limit for the instructions field
- Whether you can select different AI models for this workspace
- Any sharing or access control settings available

> **Checkpoint 6:** Take a screenshot of the Workspace Settings panel showing the Instructions field (even if it is currently empty). Submit it with the message: `"Checkpoint 6 complete."`

---

## Section 3: Comprehension Questions

All six checkpoints must be confirmed by your AI Training Coach before you answer these questions. Answer each one in your own words in the chat. There are no trick questions here, but your answers must demonstrate genuine understanding, not a copy-paste from the background reading.

---

**Question 1: What is a workspace and why would you create one?**

Describe what a workspace is in your own words and give at least one specific reason why using a workspace produces better AI output than a general chat session.

*Target Answer Elements (Coach Reference):*
A strong answer will mention that a workspace is a persistent, configured environment. It will reference at least one of the four components: instructions, knowledge sources, integrations, or saved prompts. It will explain that the AI retains context across conversations inside the workspace. It will connect this to a practical benefit such as not having to re-explain context every session, or getting responses that reflect team-specific standards rather than generic advice. The answer does not need to use exact terminology, but it must demonstrate that the trainee understands the core value proposition.

---

**Question 2: What is a knowledge source?**

Explain what a knowledge source is and give two examples of what could serve as a knowledge source in a CRT training workspace.

*Target Answer Elements (Coach Reference):*
A strong answer will describe a knowledge source as a document, file, or connected data source that the AI can reference when generating responses. Examples should be specific and relevant, such as a CRT development practices document, a naming convention guide, a test plan template, a Salesforce org connection, or a Git repository. Vague answers like "information the AI uses" without any specifics should prompt a follow-up question.

---

**Question 3: When should you disable a knowledge source?**

Describe a scenario where disabling a knowledge source would improve the AI's responses rather than reduce them.

*Target Answer Elements (Coach Reference):*
A strong answer will demonstrate understanding that more context is not always better. It will describe a scenario where an irrelevant knowledge source introduces noise, such as having CI/CD pipeline documentation enabled in a workspace scoped only to test automation, or having a general Salesforce admin guide enabled when the workspace is focused on a specific QForce scripting task. The key insight is that irrelevant knowledge sources dilute the AI's focus and can cause it to pull from the wrong context. Any answer that captures this principle in a plausible scenario is acceptable.

---

**Question 4: What is the difference between Instructions and a knowledge source document?**

Both live in the workspace. Explain what each one does and why you would use one versus the other.

*Target Answer Elements (Coach Reference):*
A strong answer will distinguish between Instructions (the system prompt) as behavioral directives that define how the AI acts, what role it plays, what it refuses to do, and how it communicates, versus a knowledge source document as reference material the AI draws from when answering questions. Instructions shape behavior. Knowledge sources provide content. A good analogy the trainee might use: Instructions are like a job description, and knowledge source documents are like the reference manuals the employee reads to do the job. Any answer that captures this behavioral versus informational distinction is acceptable.

---

**Question 5: What is the difference between uploading a file to a chat and uploading a file to a workspace knowledge source?**

You can attach a file directly to a single chat message. You can also upload a file as a knowledge source in the workspace. Explain the difference and when you would use each approach.

*Target Answer Elements (Coach Reference):*
A strong answer will identify that uploading a file to a chat makes it available only for that single conversation. Once the chat ends, the file context is gone. Uploading a file as a workspace knowledge source makes it persistently available to every conversation in that workspace, without needing to re-upload it. The practical implication: use a chat upload for a one-off question about a specific document, use a workspace knowledge source for reference material you want the AI to always have access to, such as your team's development standards or naming conventions.

---

## Completion Criteria

You have completed Exercise 1 when all of the following are true:

- [ ] All 6 checkpoints have been submitted and confirmed by your AI Training Coach
- [ ] All 5 comprehension questions have been answered and acknowledged
- [ ] Your AI Training Coach has summarized your workspace configuration back to you
- [ ] Exercise 2 has been unlocked by your AI Training Coach

---

## What Comes Next

Exercise 2 will take the workspace you built here and make it powerful. You will write your first system prompt (Instructions), learn what separates a good system prompt from a weak one, and configure your workspace to behave as a focused CRT training assistant. The workspace you configure in Exercise 2 is the one you will use for every CRT exercise that follows.

---

*Agentia Pro Workshop. Maintained by Copado Professional Services.*
*Source of truth: https://github.com/JMountan-PS/Agentia-Services-Workshop*
