# Set Your Terminal Welcome Message

#### Thi file instruct you to customize your Terminal Welcome Message. 

#### Please stick to the following steps.

Change the file path to `etc`, a directory where we store our message.
	
	cd /etc
	
Open or create a system file where we write the welcome message that shows up at the top of Terminal.

	sudo pico motd
	
You have to type your password before writing the message. The password will NOT be printed on the screen, so just press return after the password.

Now we are free to customize the Terminal welcome message. For example, `Hi, there: Welcome to Terminal!`. 

You may also mark down something to remind you next time.

Press `Control + x` to exit and then press `y` to accept and save.

Open your Terminal and you will find the new message!