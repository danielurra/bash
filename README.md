# Bash
![bash](https://github.com/danielurra/bash/assets/51704179/b73da097-8e3f-4e0e-95e2-2bd67bb0f1af)<br>
`Bash` is the default "<b>Shell</b>" for Unix-based Operating Systems like `Linux distributions` and also the famous `Apple's Mac OS`<br>
Shell is the interface which allow persons to interact with computers through commands, see below others commonly used names:<br>
* Command Line Interface (CLI)
* Console
* Terminal
## Linux CentOS, how to know the version of Bash?
Use the following command to reveal the bash version running on your computer:<br>

```bash
bash --version
```
<img src="/img/bash--version.png" alt="bash version"><br>
## Do you have Linux running on Windows?
You probably know that's possible to have a **Linux Ubuntu** running on you Windows computer<br>
A must have for any software developer.<br>
![wsl](https://github.com/danielurra/bash/assets/51704179/60813dfc-d071-49db-bc75-fe5c4b53a37d)<br>
## Windows Subsystem for Linux (WSL)
Make sure you follow Microsoft's documentation to get `Ubuntu Linux` running on your PC.<br>
https://learn.microsoft.com/en-us/windows/wsl/install<br>
See the image below, these two additional features must be enabled:<br>
![win-features](https://github.com/danielurra/bash/assets/51704179/417ce6e9-01c9-4b3e-beb0-86653905c67c)<br>
Use the following CMD command to open the enable features window:<br>
```cmd
appwiz.cpl
```
![run](https://github.com/danielurra/bash/assets/51704179/7b61a923-64c1-40f0-931a-448b2a414a94)<br>
Then on the left hand side click where it says `"Turn Windows features ON/OFF"`<br>
## Bash version of WSL
Let's see which version was installed on my computer by enabling WSL<br>
![bash-version](https://github.com/danielurra/bash/assets/51704179/aafb35c6-772c-4a2d-adfb-ffbf420a4b2f)<br>

## Scripting, Compiled, Interpreted languages
**Bash** executes programs directly from its `source code`, usually just text files, these text files actually are more than just text<br>
they are a set of commands, most of these commands are well known by software engineers and system administrators<br>
they are quite often already familiarized with them, because they're used on their daily tasks<br>
Using these commands and programming sentences we can tell the computer what to do<br>
We use the term "source code", and this particular code makes the "scripting language"<br>
Compiled languages on the other hand can not be executed just from the source code <br>
they need to be converted to a machine language, that is called compilation.<br>
**C, C++, C#** and **Java** are good examples of `compiled programming languages.`<br>
The main difference between compiled and interpreted programming languages is that the last ones<br>
are able to execute the **source code** directly without prior compilation.<br>
**PHP, Ruby, Python, and JavaScript** are examples of `Interpreted programming languages.`<br>
## CentOS, using "vi" to create our first bash script
Most Linux distributions comes with a well know text editor called `"vi"`<br>
Nowadays we all use an enhanced version called `"vim"`, you won't notice this because an alias will do the work under the hood<br>
The learning curve for this useful tool is not a fast one, but once you get familiar with<br>
its operation modes and how to move inside a text file, you're ready to conquer the world<br>
```bash
vi hello-world.sh
```
<img src="/img/bash-hello-world-01.png" alt="bash 01"><br>
Following the tradition we're gonna create the classic "Hello World!" program<br>
We must press "i" immediately after executing vi to change to INSERT mode<br>
Once in the "insert" mode we can type the command which will allow us to print text on the screen<br>
in Bash that command is "echo", see below screenshot<br>
```bash
echo Hello World!
```
<img src="/img/bash-hello-world-02.png" alt="bash 02"><br>
And that's it! Quite a short program, don't you think?<br>
We must use the ESC key to exit the edition mode of vi<br>
then type "WQ!" (write and quit) and hit Enter<br>
<img src="/img/bash-hello-world-03.png" alt="bash 03"><br>
Let's see if our new file is there<br>
<img src="/img/bash-hello-world-04-v2.png" alt="bash 04"><br>
Now we can run our first bash script<br>
<img src="/img/bash-hello-world-05-v2.png" alt="bash 05"><br>
## chmod - Change Mode command
I did try a few minutes ago with my WSL and it was needed to give execute permission to my user<br>
```bash
chmod u+x hello-world.sh
```
![chmod and execute](https://github.com/danielurra/bash/assets/51704179/313a0658-a941-4d3f-a7c1-3135ba9f5395)<br>

## How to find all the bash (.sh) files
First of all, let's see how many `".sh"` files we do have in our entire system, I mean starting from the root folder `/`<br>
it's quite probable that we'll find **a lot** of them, but there's nothing to worry about<br>
we can always narrow down our search to any particular folder we'd like<br>
```bash
find / -name "*.sh" 2> /dev/null | wc -l
```
<img src="/img/finding-all-bash-files-word-count-how-many.png" alt="bash 05"><br>
I was right, 239 will give us a long list, let's then narrow down our search to only include the directory `/etc`<br>
```bash
find /etc -name "*.sh" 2> /dev/null | wc -l
```
<img src="/img/finding-bash-files-narrow.png" alt="bash 05"><br>
Only 10 that's what I was looking for, now then let's list them<br>
```bash
find /etc -name "*.sh" 2> /dev/null
```
<img src="/img/finding-bash-files.png" alt=""><br>
WAIT! Azure? Aren't we on Linux? <br>
## Example of the content of a bash file
<img src="/img/example-01.png" alt=""><br>
As you can see, the content of a bash file is just text, text in the form of sentences and commands<br>
the main idea behind bash and the scripting language is to help system administrators to deal with tedious and repetitive tasks<br>
making their job a little bit easy and enjoyable at the same time<br>
## Do you prefer the colored syntax provided by modern text editors?
I do prefer the colored syntax, see how easy is to identify the code comments<br>
By the way, the following screenshot belong to Atom text editor<br>
<img src="/img/example-02.png" alt=""><br>

