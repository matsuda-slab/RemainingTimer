## Left Time Reminder
This script add remaining days to a certain event to your prompt.

## Requirements
* Nothing for Linux
* gdate for Mac OS

## Usage
1. Put .zsh-remainingtimer in your home directory.
2. Edit .zsh-remainingtimer to set the event name and date. 
Opening .zsh-remainingtimer by editor, edit the variables 'EVENTNAME', 'YEAR', 
'MONTH', and 'DAY'.
3. Write "source .zsh-remainingtimer" to your .zshrc.  
	`$ echo 'source .zsh-remainingtimer' >> ~/.zshrc`
4. and reflect.  
	`$ source ~/.zshrc`

## Note
If an error message "no matches found" is shown when sourcing the script on your
Mac OS, you can write "setopt nonomatch" in your .zshrc to suppress the message.
