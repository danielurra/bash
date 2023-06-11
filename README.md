# Bash
![bash](https://github.com/danielurra/bash/assets/51704179/b73da097-8e3f-4e0e-95e2-2bd67bb0f1af)<br>
Bash is the default "<b>Shell</b>" for both Operating Systems, Linux and Mac<br>
Shell is the interface which allow persons to interact with computers</br>
</br>
## How to know the version of Bash?
Use the following command to reveal the bash version running on your computer:</br>
``bash
bash --version
``
</br>
<img src="/img/bash--version.png" alt="bash version"></br>
## Are you using Linux in Windows?
You probably know that's possible to have a Linux Ubuntu running on you Windows computer<br>
A must have for any software developer.<br>
![wsl](https://github.com/danielurra/bash/assets/51704179/60813dfc-d071-49db-bc75-fe5c4b53a37d)<br>
## Windows Subsystem for Linux (WSL)
![win-features](https://github.com/danielurra/bash/assets/51704179/417ce6e9-01c9-4b3e-beb0-86653905c67c)
Let's see which version was installed on mi computer by enabling WSL<br>
![bash-version](https://github.com/danielurra/bash/assets/51704179/aafb35c6-772c-4a2d-adfb-ffbf420a4b2f)

## Scripting Languages vs Compiled languages
Bash executes programs directly from its source code, usually just text files<br>
these text files actually are more than just text they are a set of commands<br>
most of these commands are well known by software engineers and system administrators<br>
they are quite often already familiarized with them, because they're used on their daily tasks<br>
Using these commands and programming sentences we can tell the computer what to do<br>
We use the term "source code", and this particular code makes the "scripting language"<br>
Compiled languages on the other hand can not be executed just from the source code <br>
they need to be converted to a machine language, that is called compilation<br>
## Using vi to create our first bash script
<img src="/img/bash-hello-world-01.png" alt="bash 01"><br>
Following the tradition we're gonna create the classic "Hello World!" program<br>
We must press "i" immediately after executing vi to change to INSERT mode<br>
Once in the "insert" mode we can type the command which will allow us to print text on the screen<br>
in Bash that command is "echo", see below screenshot<br>
<img src="/img/bash-hello-world-02.png" alt="bash 02"><br>
And that's it! Quite a short program, don't you think?<br>
We must use the ESC key to exit the edition mode of vi<br>
then type "WQ!" (write and quit) and hit Enter<br>
<img src="/img/bash-hello-world-03.png" alt="bash 03"><br>
Let's see if our new file is there<br>
<img src="/img/bash-hello-world-04-v2.png" alt="bash 04"><br>
Now we can run our first bash script<br>
<img src="/img/bash-hello-world-05-v2.png" alt="bash 05"><br>
## How to find all the bash (.sh) files
First let's see how many ".sh" files we do have<br>
if we have a lot of them we can narrow our search to a particular folder<br>
<img src="/img/finding-all-bash-files-word-count-how-many.png" alt="bash 05"><br>
I was right, 239 will give us a long list<br>
let's then narrow our search to the directory /etc<br>
<img src="/img/finding-bash-files-narrow.png" alt="bash 05"><br>
Only 10 that's what I was looking for<br>
Now let's list them<br>
<img src="/img/finding-bash-files.png" alt=""><br>
WAIT! Azure? Aren't we on Linux? <br>
## Example of the content of a bash file
<img src="/img/example-01.png" alt=""><br>
As You can see, the content of a bash file is just text<br>
text in the form of sentences and commands<br>
the main idea behind bash and the scripting language<br>
is to help system administrators to deal with tedious and repetitive tasks<br>
making their job a little bit easy and enjoyable at the same time<br>
## Do you prefer the colored syntax provided by modern text editors?
I do prefer the colored syntax, see how easy is to identify the code comments<br>
By the way, the following screenshot belong to Atom text editor<br>
<img src="/img/example-02.png" alt=""><br>

