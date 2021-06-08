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

## Image
	before sourcing
	https://user-images.githubusercontent.com/53845948/121270581-f30d9700-c8fc-11eb-9083-0820e16cecd1.png

	after sourcing
	https://user-images.githubusercontent.com/53845948/121270488-ce192400-c8fc-11eb-9f56-4816e40f829d.png

## Note
If an error message "no matches found" is shown when sourcing the script on your
Mac OS, you can write "setopt nonomatch" in your .zshrc to suppress the message.
