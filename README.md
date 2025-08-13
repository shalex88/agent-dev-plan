# agent-dev-plan

Workflows for AI-assisted software development inspired by [ai-dev-tasks](https://github.com/snarktank/ai-dev-tasks) and tailored for GitHub Copilot

## 1. Defining Scope: Product Requirement Document (PRD)

Generate PRD by ```create-prd.md``` and providing the basic project goal as input

Use the best thinking model for this stage

```markdown
Use #file:create-prd.instructions.md
Here's the feature I want to build: [Describe your feature in detail]
Preferred tech stack: [Optional: list your preferred technologies, frameworks, and tools]
Reference these files to help you: [Optional: #file:file1.py #file:file2.ts]
```

## 2. Detailed Planning: Task Breakdown

Define tasks by ```generate-tasks.instructions.md``` and providing the generated ```prd-[project-name].md``` as input

```markdown
Take #file:prd-[project-name].md and create tasks using #file:generate-tasks.instructions.md
```

## 3. Manually review the tasks list

## 4. Iterative Implementation: One Task at a Time

Start implementation by ```process-task-list.instructions.md``` and providing the generated ```tasks-list-[project-name].md``` as input

```markdown
Please start on task 1.1 from #file:tasks-prd-[project-name].md and use #file:process-task-list.instructions.md
```

## 5. Review the task execution
