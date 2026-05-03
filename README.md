# 🦥 Lazy42

Helper script for preparing 42 Piscine C code files. Can fix all these stuff by just running one command :>
- comments out (and moves if needed) main to your code file
- puts 42 header
- deletes unnecessary files for submission
- fixes 90% norminette errors, except like logic ones and line/function/file too long stuff

⚠️ NOTE: Please make a backup before trying it. It lets you set the path to the location of the code folder you wanna use it on, so just copy paste the whole folder to make a backup somewhere first. The script lets you revert or accept the changes WHILE it is still running, and auto reverts if it gets interrupted, so no need to worry on that part.

##  Quick Start

**1. 📦 Clone and make executable:**
```bash
git clone https://github.com/l4n1skyy/lazy42.git
chmod +rwx lazy42/*
```

**2. 🛠️ Configure (one-time):**
Edit `scripts/prep.config`:
```
SCRIPTS_DIR='/home/l4n1skyy/Downloads/42kl-piscine-0416/lazy42/'
CODE_DIR='/home/l4n1skyy/Documents/42kl/'
PREP_USERNAME=lanusri-
PREP_EMAIL=lanusri-@student.42kl.edu.my
```

**3. 🚀 Run:**
```bash
./scripts/prep-all                # all modules
./scripts/prep-all c-01           # single module
./scripts/prep-all c-01 c-02      # multiple modules
```

The script stages changes in a temporary directory, shows a summary, and asks to accept or revert.


---

<div align="center">
  <h4>Built with ❤️ by <b>l4n1skyy</b></h4>
</div>
