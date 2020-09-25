# cpp-vscode

VSCode settings that I use to write and debug C/C++ code on WSL2(Ubuntu 20.04).

## Shell script:

This script clones the settings into a folder named by the command line argument and removes .git and README.md.

Remove `&> /dev/null` to view the output from `git clone`.

Remove the last line to not open the folder in vscode immediately.

```bash
#!/bin/bash

git clone https://github.com/Wahaj404/cpp-vscode.git $1 &> /dev/null
rm -rf $1/.git
rm $1/README.md
code $1
```
