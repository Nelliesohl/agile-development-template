# Agile Development Template for GitHub Projects

This template provides tools and guidance for managing your project using Agile methodology. It includes templates and workflows for user stories, product backlog, prioritization, task estimate, iteration backlog and a Kanban board to ensure smooth collaboration and efficient project management.

---

## Features

1. **User Story Issue Template**
   - Define user stories with a clear structure to capture functionality requirements.
   - Includes fields for: As a [role], I can [capability] so that [benefit],
   - Includes sections for: Acceptance criteria and Tasks

3. **Labels**
   - `Theme`: Organize user stories based on themes or high-level goals.
   - `Epic`: Group body of work that can be broken down into specific stories.
   - `MoSCoW`: Categorize backlog items into Must-Have, Should-Have, Could-Have, and Won't-Have priorities.
   - `Story Point`: Assess the complexity and effort required for each task, improving sprint planning.

2. **Product Backlog**
   - Centralize all Product Backlog Items (PBIs) in a GitHub Milestone to manage planned work.

5. **Iteration Backlog**
   - Enables grouping of PBIs into GitHub Milestones for specific iterations (e.g., Iteration 1, Iteration 2).

7. **Kanban Board**
   - Leverages GitHub Projects for a visual representation of the workflow, making task progress clear at a glance.
   - Includes columns: `To Do`, `In Progress`, `Done`
   - Columns reflect the current sprint's PBIs and their progress.


---

## Setup Instructions

### Step 1: Add User Story Issue Template

1. Create a `.github/ISSUE_TEMPLATE/user_story.md` file with the following content:

```markdown
---
name: User Story
about: Template for creating user stories.
title: 'USER STORY: <TITLE>'
labels: ''
assignees: ''

---

**As a** <role>,  
**I can** <capability>,  
**So that** <benefit>.

---

### Acceptance Criteria
- [ ] Criterion 1
- [ ] Criterion 2

---

### Tasks

1.  
2.  
3.  

```

### Step 2: Set Up MoSCoW Prioritization

1. Add labels to your GitHub repository for:
   `Must-Have`
   `Should-Have`
   `Could-Have`
   `Won't-Have`

   Assign these labels to backlog items based on priority.

### Step 3: Enable Story Point Labels

1. Add labels to represent story points for tasks:
   `1`, `2`, `3`, `5`, `8`, `13`, `20`, `40`.

   Use these labels to estimate effort for each task or user story.

### Step 4: Add Theme and Epic Labels

1. Add theme labels to categorize issues based on high-level goals:

   Examples: `UI/UX`, `Backend`, `Frontend`, `Performance`.
   
3. Add epic labels to group related user stories or tasks:
   
   Examples: `Epic: User Authentication`, `Epic: Reporting Dashboard`.

### Step 5: Create Milestones

1. Add milestones to your GitHub repository:
   
   **Product Backlog**: Comprehensive list of all planned features.
   
   **Iteration 1**: First sprint of tasks and goals.

### Step 6: Enable a Kanban Board

1. Navigate to the "Projects" tab in your GitHub repository.
2. Create a new project board with columns:
   
   `To Do` `In Progress` `Done`

   Drag and drop issues into appropriate columns to manage workflow.

---
