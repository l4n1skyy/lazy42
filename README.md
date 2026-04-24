# Scripts

Helper scripts for preparing 42 Piscine C code files.

## Quick Start

**1. Clone and make executable:**
```bash
git clone <your-repo>
chmod +rwx scripts/*
```

**2. Configure (one-time):**
Edit `scripts/prep.config`:
```
SCRIPTS_DIR=/absolute/path/to/your/scripts
CODE_DIR=/absolute/path/to/your/code
PREP_USERNAME=your-login
PREP_EMAIL=your-email@student.42kl.edu.my
```

**3. Run:**
```bash
./scripts/prep-all                # all modules
./scripts/prep-all c-01           # single module
./scripts/prep-all c-01 c-02      # multiple modules
```

The script stages changes in a temporary directory, shows a summary, and asks to accept or revert.
