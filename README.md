# Fun Police Framework

The Fun Police Framework enforces architectural discipline and engineering best practices
through a comprehensive AI pair programming system.
This README explains how to set up the framework in your own project.

See instructions.org for detailed usage instructions.

## Setup Instructions

### 1. Add Fun Police as a Git Submodule to your project

```bash
# From your project root
git submodule add https://github.com/monkeypants/fun-police.git .fun-police
```

### 2. Add a Tech Stack Specificaitons

You can either use an existing tech stack as a git submodule:

```bash
# From your project root
git submodule add https://github.com/monkeypants/fun-police-stack1.git .tech
```

Or create a bespoke .tech/ directory for your specific project needs.

The .tech/ directory must contain
- .tech/systemPatterns.org
- .tech/techContext.org

### 3. Create a Spec Directory

```bash
mkdir -p spec
```

the spec/ directory must contain project-specific files, such as:
- projectbrief.org
- productContext.org
- tasks.org
