# Scripts

Helper scripts for preparing 42 Piscine C code files.

## Quick Start

**1. Clone and make executable:**
```bash
git clone https://github.com/l4n1skyy/lazy42.git
chmod +rwx lazy42/*
```

**2. Configure (one-time):**
Edit `scripts/prep.config`:
```
SCRIPTS_DIR='/home/l4n1skyy/Downloads/42kl-piscine-0416/lazy42/'
CODE_DIR='/home/l4n1skyy/Documents/42kl/'
PREP_USERNAME=lanusri-
PREP_EMAIL=lanusri-@student.42kl.edu.my
```

**3. Run:**
```bash
./scripts/prep-all                # all modules
./scripts/prep-all c-01           # single module
./scripts/prep-all c-01 c-02      # multiple modules
```

The script stages changes in a temporary directory, shows a summary, and asks to accept or revert.
