# Useful Keyboard Shortcuts in VSCode

## Download Seiten

**Anaconda:** <https://www.anaconda.com/downloads>

**VS Code:** <https://code.visualstudio.com/>

Note: The shortcuts may differ in osx.

## Git

```bash
# git config
git config --global email "???"
git config --global user.name "Jan iMac"

# git clone
sudo apt install openssh-server
sudo apt install git
git clone https://github.com/ju1-eu/VSCodeGuide-master.git
```

## Python in VSCode

```bash
# Anaconda installieren
conda activate base
# environment
conda create -n pyMeister python=3.9
conda activate pyMeister
conda deactivate

pip install -r requirements.txt
# wenn Problem mit export in *.ipynb
pip uninstall nbconvert
pip install nbconvert -U

# VScode und Extension installieren
franneck94

[shift + command + p] python config files

# Terminal
jupyter notebook
```

## Problem-Lösungem

Bei MacOS und Linux anstatt "activate" bitte "conda activate" eingeben

## Editor

- Copy (selected) text: `Ctrl+C`
- Pase text: `Ctrl+V`
- Cut text: `Ctrl+X`
- Copy and paste current line to Up/Below: `Shift+Alt+(Down/Up)`
- Delete current line: `Ctrl+Shift+K`
- Search in File: `Ctrl+F`
- Search and Replace in File: `Ctrl+H`
- Replace one finding: `Enter`
- Replace all findings: `Ctrl+Alt+Enter`
- Fold All: `Ctrl+K, Ctrl+0`
- Unfold All: `Ctrl+K, Ctrl+J`
- Fold Level (x=1-9): `Ctrl+K, Ctrl+x`
- Format Document: `Ctrl+Alt+F`
- Go Back: `Alt+LeftArrow`
- Go Forward: `Alt+RightArrow`
- Quick Fix: `Ctrl+.`
- Go To Definition: `F12`

## Terminal

- Create new terminal instance: `Ctrl+Shift+C`

## Workspace

- Open File: `Ctrl+O`
- Open Folder: `Ctrl+K, Ctrl+O`

## Tasks, Debug and more

- Get Build Tasks: `Ctrl+Shift+B` oder Mac `Shift+Command+B`
- Run launch (debug) config: `F5`
- Show all Commands: `F1`

## File Formatieren

`Shift+Alt+F`
