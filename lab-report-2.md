# Lab Report 2

Hello CSE 15L!
Here is a tutorial for doing all the starting things you'll need for Labs

Including but not limited to:
- Installing VScode
- Remotely Connecting
- Trying Some Commands
- Moving Files with scp
- Setting an SSH Key
- Optimizing Remote Running
So let us get started!

### Installing VSCode
VSCode will be the main programming thingamajig you will be using throughout the course. 

You can get it from this neat [site](https://code.visualstudio.com/).
![VSCode website](images/vscode-website.png)

Smash that big ol blue download button right in the middle to get that application onto your machine, mine being a mac. 

After going through the basic installing, you should get a page that should look like dis (give or take a little bit, I have a few extra addons):
![VSCode app](images/VSCode-app.png)

Now to access this funky terminal incorporated within the VSCode app, there's this place at the top of the screen (for my mac at least) where you can choose to open a new terminal for you to use. 
![VSCode terminal find](images/VSCode-find-terminal.png)

Good good! How wonderfully amazing. You have successfully completed the first part of this tutorioal!

---
### Remotely Connecting
We can use the terminal to connect to the official lab computers in UCSD remotely, I will show you how to do so. 

Mac already has SSH so we needn't worry about other configuration issues

[**Here you can find the username to use for the connection**](https://sdacs.ucsd.edu/~icc/index.php) by entering your profile information. 

Then you can proceed to connect by entering this into your terminal replacing the `zz` with the letters of your account username:
```
ssh cs15lwi22zz@ieng6.ucsd.edu
```
You can then enter your password to log in (Your entered password will be invisible)

