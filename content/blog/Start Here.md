---
title: "Start here!!!"
date: 2020-06-15T17:59:39-07:00
draft: false
---
## Anne's Awesome Guide to Coding (Preface)
I hope you find this useful! You can use this guide to reference all the lessons to be posted in the future. 

## Learn how to use the terminal   
*I know the terminal is scary but you can do it!!* 

The terminal is necessary to navigate your computer file structure. You need to do this to find the correct files and run the code you write!!
By default all macOS comes with an install of Python 2.7, you can check your installation of python by opening the terminal.
> You can open the terminal by pressing `cmd + space` and search for `terminal`

In the terminal that opens type
> `python --version`

You should have version 2.7 installed and you can switch between python2 and python3 by using the commands `python` and `python3` respectively.

Now, let's start with learning how to navigate the terminal. I'm using windows so my terminal looks different but it should have all the same features

{{< figure src="/Start Here/bare terminal.png" title="Your First Terminal" >}}

There's not much in the way here. The only things visible are the user that you're logged in with and the current directory that you're in. To get started let's list everything in the current directory with the command `ls`. 

{{< figure src="/Start Here/ls_term.png" title="View your current folder" >}} 

Depending on where your terminal opened it will show you all the folders in your current directory. If you're feeling a little anxious about whats going on, then you can use `open .` to open the current directory in finder.

### Now let's create our project folder from within the terminal!

Use the `cd` command to move between directories. For example to get into the documents folder use `cd Documents`. 
*You can autocomplete a directory and most commands by just pressing tab halfway through typing out the directory name*

If you want to move back a directory you can use `cd ..`. The double dots translate to "move back a folder". 

Now let's see whats in our Documents directory by simply typing
> `ls`

{{< figure src="/Start Here/Documents Directory.png" title="Documents Directory" >}}

Now let's make our project folder by using the command 
> `mkdir 'First Python Project'`
* Make sure to use quotes around `'First Python Project'` or else the terminal will evaluate all the words as separate arguments*

*If you mess up with the quotes you can press `ctrl + C` at any time to cancel the running command.

Now change to the directory you just made with 
>`cd First\ Python\ Project/`
This looks funny because the `\` is used to escape the space character, which is usually used to separate arguments. In this case, we are telling the terminal to evaluate the space as a character and not split up the words into different arguments. 
*If you type `First` and press tab, it will auto-populate the rest of the path for you.*

## You're done here!
That's all you need to get started with the terminal. The next tutorial will go over the basics of the python shell and then creating your first python project!!

    
