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
	`$ echo 'source ~/.zsh-remainingtimer' >> ~/.zshrc`
4. and reflect.  
	`$ source ~/.zshrc`

## Image
before sourcing
![unsettimer](https://user-images.githubusercontent.com/53845948/121271937-b8592e00-c8ff-11eb-8212-7a204d4b0f90.png)

after sourcing
![settimer](https://user-images.githubusercontent.com/53845948/121272078-0a9a4f00-c900-11eb-8d40-4829baa019f2.png)

## Note
If an error message "no matches found" is shown when sourcing the script on your
Mac OS, you can write "setopt nonomatch" in your .zshrc to suppress the message.
