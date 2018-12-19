---
layout: default
---

# Command-Line Course


## Introduction

Introduction to command-line tools and to how to use them in an Unix environment. Includes writing basic scripts and using version control tools.
The following table presents the weekly subjects we handled on the course.

| Week | Subject |
| --- | --- | --- |
| Week 1 | Introduction to Command-Line Environments | 
| Week 2 | Navigating a UNIX System |
| Week 3 | Corpus Processing |
| Week 4 | Scripting and UNIX Configuration Files | 
| Week 5 | Installing and Running Programs |
| Week 6 | Version Control |
| Week 7  | Building Webpages using GitHub Pages |


![alt text](https://cdn3.iconfinder.com/data/icons/macosxstyle/macosxstyle_png/512/Terminal.png)

  

### Week 1:Introduction to Command-Line Environments

_How to install, Command-line basics, Text editors, File formats_
  * **Reflection:** I started up with very little knowledge and had barely used the Terminal before. This week I was introduced in using the Terminal and to what I can do with command-line. Fun!

`wget <address>`

Downloads a file from the online address to the directory you are in.



### Week 2: Navigating a UNIX System

_Commands, Permissions, Users, Working in a remote server_
  * **Reflection:** I learned to navigate a UNIX System by using the Terminal and command-line. I also learned for example what read, write and execute permissions are and how to change them.

`chmod a+x sample.txt` 

This command gives execute permission to a file sample.txt to all users.



### Week 3: Corpus Processing

_Useful commands for corpus processing, Processing data files, Standard input/output/error, Regular expressions_
  * **Reflection:** This week I got to use some basic commands that are useful for corpus processing. Some of these are for example grep and sed. I was already familiar with regular expressions from my previous courses, but still learned more especially on how to use them.

`grep "pattern" file.txt` 

Finds and matches a pattern using RegEx in the file given.



### Week 4: Scripting and UNIX Configuration Files

_Bash, Python, Perl scripts, Combining commands we have learned into a script_
  * **Reflection:** This week felt more difficult than the earlier ones. I dove deeper into things I had no prior knowledge about.  I learned a lot about scripts and even learned to make some myself.

```
for variable in <list>
do
    <command>
done
```
This is a for-loop, that loops through a list you give it and does the given command to each member of the list.



### Week 5: Installing and Running Programs

_Installing programs, Python and C/C++, Environment variables, Configuration files (.bashrc, .bash_history, .bash_profile)_
  * **Reflection:** I learned a lot of new things about installing programs. I also learned what is a configuration file like .bashrc and what I can use it for.

```
target: file1 file2
        some_command
```
Make rule that makes a target file using a list of files given to it by running a given command.



### Week 6: Version Control

_Using Git for version control_
  * **Reflection:** Git and GitHub was a totally new thing for me. However, I managed to practise version control using git and set up a GitHub accaount for myself.

`git clone git@github.com:myname/myproject.git`

Clones a git repository and creates a new local repository on my own computer. Current versions of the git-controlled files and directories within myproject are copied into my own computer to a folder myproject, which keeps connection to the remote repository.



### Week 7: Building Webpages using GitHub Pages

_Installing and using Jekyll, using GitHub Pages and building a website_
  * **Reflection:** I learned what is Jekyll and GitHub Pages and how to use them. I had a lot of trouble installing and using Jekyll on my own computer so I ended up learning how to use Cubbli Linux and working on that. This website was build as the final project on the course.
