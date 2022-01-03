# Custom-Zshrc-for-MacOS

## Porting of Kali linux Zshrc to MacOS

*This is a native zshrc file not an oh my zsh tamplate*

### Features : 
- Highlight 
- Suggestion (based on history)
- Some keyboard shortcuts 
- Full colorisation (including validity of command, man, research like grep, navigation through tab sugestion with arrows)
- Choice of prompt patern (one line, two line, or backtrack)
<img width="675" alt="Capture d’écran 2022-01-03 à 23 32 13" src="https://user-images.githubusercontent.com/62914065/147987543-caf11cdf-f58f-4df2-a8f7-90af9b8040e4.png">
<img width="717" alt="Capture d’écran 2022-01-03 à 23 33 18" src="https://user-images.githubusercontent.com/62914065/147987615-1cf61672-60a6-4b09-b822-0df226ad2575.png">
<img width="563" alt="Capture d’écran 2022-01-03 à 23 34 50" src="https://user-images.githubusercontent.com/62914065/147987725-ba9a59eb-e30e-4aa3-a605-b3a89ee80766.png">
<img width="682" alt="Capture d’écran 2022-01-03 à 23 36 31" src="https://user-images.githubusercontent.com/62914065/147987840-06f5e762-fa91-4fbe-ac2a-20ec001a681a.png">


### Installation :

1. Download the zip file. 
2. Put the .zshrc in your home directory (be aware to copy your already existing alias, export etc of the old .zshrc int the new .zshrc). 
3. Put **zsh-autosuggestions** and the **zsh-syntax-highlighting** folders where you want.
4. Change the directory at the line 121, 122 and 234, 235 by your directory of **zsh-autosuggestions.zsh** and the **zsh-syntax-highlighting.zsh** in the .zshrc.
5. Launch your terminal drag the **.terminal** in the list run a new window of the terminal (source .zshrc in your home directory if needed).  

You can choose line pater at the line 110 of .zshrc
### Known bug : 

- Accuracy of the colorisation : some time the colorisation is a bit bland when there is suggestions.
- Problem of compatibility with certain font (like it with the "Pro" preset)
