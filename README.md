# Custom-Zshrc-for-MacOS

## Porting of Kali linux Zshrc to MacOS

*This is a native zshrc file not an oh my zsh tamplate*

### Features : 
- Highlight 
- Suggestion (based on history)
- Some keyboard shortcuts 
- Full colorisation (including validity of command, man, research like grep, navigation through tab sugestion with arrows)
- Choice of prompt patern (one line, two line, or backtrack)

### Installation :

1. Download the zip file. 
2. Put the .zshrc in your home directory (be aware to copy your already existing alias, export etc of the old .zshrc int the new .zshrc). 
3. Put **zsh-autosuggestions** and the **zsh-syntax-highlighting** folders where you want.
4. Change the directory at the line        in the .zshrc.
5. Launch your terminal drag the **.terminal** in the list run a new window of the terminal (source .zshrc in your home directory if needed).  


### Known bug : 

- Accuracy of the colorisation : some time the colorisation is a bit bland
- Problem of compatibility with certain font (like it with the "Pro" preset)
