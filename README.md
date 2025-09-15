# Bash Scripts Project

This repository contains Bash script exercises.  
Requirements:
- Allowed editors: vi, vim, emacs
- Scripts will be interpreted on Ubuntu 22.04
- All files end with a new line
- `README.md` at the root is mandatory
- All Bash script files are executable
- Scripts pass `shellcheck` without any error
- The first line of all Bash scripts is exactly: `#!/usr/bin/env bash`
- The second line of all Bash scripts is a comment explaining what the script does

How to run:
1. Make scripts executable:
   chmod +x ./0-hello_world

2. Run a script:
   ./0-hello_world

How to check:
- ShellCheck:
  shellcheck ./0-hello_world

- Verify newline at EOF:
  tail -n1 ./0-hello_world | od -An -t c
