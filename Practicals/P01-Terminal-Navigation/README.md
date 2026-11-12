# P1 – Project folder and terminal navigation

## Aim
Create a project folder and practise moving around the file system using terminal commands.

## Commands (macOS / Linux)
```bash
pwd                         # show the current directory
ls                          # list files and folders
mkdir web-lab               # create a folder
cd web-lab                  # enter the folder
mkdir p1-terminal           # create a subfolder
cd p1-terminal              # enter the subfolder
touch index.html            # create an empty file
ls -la                      # list all files, including hidden files
cd ..                       # move one level up
cd ~                        # move to the home directory
```

## Windows PowerShell equivalents
```powershell
Get-Location
Get-ChildItem
New-Item -ItemType Directory web-lab
Set-Location web-lab
New-Item -ItemType Directory p1-terminal
Set-Location p1-terminal
New-Item index.html -ItemType File
Get-ChildItem -Force
Set-Location ..
Set-Location ~
```

## Expected result
A folder named `web-lab/p1-terminal` containing an `index.html` file.

## Notes
- `pwd` displays the present working directory.
- `cd` changes the current directory.
- `mkdir` creates a directory.
- Use `ls` (or PowerShell's `Get-ChildItem`) to inspect a directory.
