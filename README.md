# cpp-vscode

VSCode settings that I use to write and debug C/C++ code on WSL2(Ubuntu 20.04).

## Shell script:

`script.sh` clones the settings into a folder named by the command line argument and removes everything except the settings.
Run it locally after saving it or remotely using curl:

```bash
curl https://raw.githubusercontent.com/Wahaj404/cpp-vscode/master/script.sh | bash -s [folder name here]
```
