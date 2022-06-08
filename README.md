
# Super Necessary

## Homebrew
**Why?**
- Brew will be used to install most of the software
- It allows for easy software updates

**Requirements:**
-  `xcode-select --install` (Command Line Tools (CLT) for Xcode)

**Install:**
- `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
- To view all top-level packages that are not dependencies and that were previously manually installed: 
  - `brew  --installed-on-request | xargs -n1 brew desc`
- To update all formulae and casks; to limit their scope to only formulae or casks add the --formula or --cask option to the command line.
  - `brew update`
  - `brew outdated`
  - `brew upgrade`

____________________
## Firefox
**Why?**
- Internet browser that can easily be configured for privacy

**Install:**
- `brew install --cask firefox`

____________________
## Alfred
**Why?**
- Alfred Workflows allow you to use the mouse far less

**Install:**
- `brew install --cask alfred`

**Alfred Workflows:**
- Firefox Assistant: https://github.com/deanishe/alfred-firefox
- Firefox Assistant Add-On: https://github.com/deanishe/alfred-firefox
- Menu Bar Search: https://github.com/BenziAhamed/Menu-Bar-Search

____________________
## Rectangle
**Why?**
- Window Resizer

**Install:**
- `brew install --cask rectangle`


____________________
____________________
# Programming
## Iterm2
**Why?**
- Better terminal

**Install:**
- `brew install --cask iterm2`
____________________

## VSCode
**Why?**
- Code editor

**Install:**
- `brew install --cask visual-studio-code`
____________________

