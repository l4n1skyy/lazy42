# 🦥 Lazy42

Helper script for preparing 42 Piscine C code files. Can fix all these stuff by just running one command :>
- comments out (and moves if needed) main to your code file
- puts 42 header
- deletes unnecessary files for submission
- fixes 90% norminette errors, except like logic ones and line/function/file too long stuff

⚠️ NOTE: Please make a backup before trying it. It lets you set the path to the location of the code folder you wanna use it on, so just copy paste the whole folder to make a backup somewhere first.

<h4 align="center" >Built with ❤️ by <b>l4n1skyy</b></h4>

##  Quick Start

**1. 📦 Clone and make executable:**
```bash
git clone https://github.com/l4n1skyy/lazy42.git
chmod +rwx lazy42/*
```

**2. 🛠️ Configure (one-time):**
Edit `lazy42/prep.config`:
```
SCRIPTS_DIR='/home/l4n1skyy/Downloads/42kl-piscine-0416/lazy42/'
CODE_DIR='/home/l4n1skyy/Documents/42kl/'
PREP_USERNAME=lanusri-
PREP_EMAIL=lanusri-@student.42kl.edu.my
```

**3. 🚀 Run:**
```bash
./scripts/prep-all                # all modules
./scripts/prep-all checkpoint00   # one checkpoint folder
./scripts/prep-all checkpoint00 checkpoint01
```

The script stages changes in a temporary directory, shows a summary for each requested folder, and asks once whether to accept or revert the whole batch. Pass any parent folder, module folder, or specific exercise folder that lives under your configured `CODE_DIR`.
