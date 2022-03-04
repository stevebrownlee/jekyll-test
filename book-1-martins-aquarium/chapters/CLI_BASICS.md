# Making Directories and Files in the Terminal

## Learning Objectives

* You should be able to create new directories in the terminal with the `mkdir` command.
* You should be able to create new files in the terminal with the `touch` command.
* You should be able to navigate directories in the terminal with the `cd` command.
* You should be able to create new directories in the terminal with the `mkdir` command.
* You should be able to create new directories in the terminal with the `mkdir` command.

Before you start writing code for any application, you want to set up the directory structure and create some initial files on the file system first. During this first book of the NSS course, you are going to build a web page to track the inventory of a rare fish aquarium.

You can watch the [Martin's Aquarium Directories and Files](https://www.youtube.com/watch?v=ogHzpf4Kelk) video that will also show you the basic terminal commands to use for this.

Since all of the work you will be doing at NSS will be contained in the `~/workspace` directory, you need to create a `martins-aquarium` subdirectory.

> If you don't have a workspace directory yet, go to your terminal and type in the following commands.
>    1. `cd` - This always takes you to your home directory
>    2. `mkdir workspace` - This makes the directory which will contain all of your projects
>    3. `cd workspace` - This changes the active directory to `workspace` which is now a sub-directory of your home directory.

While in your workspace directory, type `mkdir martins-aquarium` to make a new sub-directory which will contain the files for this project.

```sh
{home directory}
    +-- workspace
        +-- martins-aquarium
```

Go ahead and `cd martins-aquarium` so that you are working in your project direcotry.

Once the directory is created, you need to create the HTML file and the CSS file. The standard name for the initial HTML for any web site is `index.html`.

Create the file with the following command.

```sh
touch index.html
```

Next, create a `styles` sub-directory and create a file named `main.css` in it.

```sh
mkdir styles
touch styles/main.css
```

Create another sub-directory named `scripts` and create a file named `main.js` in it.

```sh
mkdir scripts
touch scripts/main.js
```

That's all you need to do in this chapter. Below are optional challenges you can try if you want to.


## Challenge: Creating Content in a File

> **NOTE:** These are completely optional exercises that you can choose to do. All we ask is that you complete all of the regular practice exercises before attempting to take on a challenge.
>
> If your instruction team has moved on to a new chapter or topics, it is far more important to work on the current practice exercises for that new topic than spending more time on a previous challenge.

During your career, you will be using powerful and extensible code editors like Visual Studio, IntelliJ, Webstorm, Eclipse, and many others to create your code. However, there are times that you want to put just a couple lines of code or a comment in a file and you don't want to fire up your powerful editor just to do that.

Read the well-written answer to a [question on the Stack Exchange website](https://unix.stackexchange.com/questions/77277/how-to-append-multiple-lines-to-a-file) and see if you can figure out how to get the following CSS code into the `main.css` file without using Visual Studio Code, but the `echo` command in the terminal.

```css
#fishtank {}

.fish {}

.fish__name {}
```

## Advanced Challenge: Terminal Welcome Message

> **NOTE:** Advanced challenges are only to be attempted once the practice exercises are complete and you feel you both (a) a solid grasp on the basic knowledge of the current topic, and (b) you have adequate time to devote to them. They are intended to be difficult to solve and you must spend time researching it before any instructor will offer guidance.

The terminal can do everything that all of your other applications you have, or ever will have, can do. There's just not a visual interface for doing it. It's all just text.

In this advanced challenge, you should research bash variables, bash aliases, and find out how to customize your `zsh` _(.zshrc)_ or `bash` _(.bashrc)_ initialization script to have a welcome message show up every time your launch a terminal session.

![welcome message in the terminal](./images/terminal-welcome.gif)

Helpful searches to get you started:

1. https://duckduckgo.com/?q=bash+my+username&ia=web
1. https://duckduckgo.com/?q=bash+current+day&ia=web
1. https://duckduckgo.com/?q=bash+display+calendar&ia=web
1. https://duckduckgo.com/?q=bash+script+for+beginners&ia=web
1. https://github.com/robbyrussell/oh-my-zsh

## Videos to watch if you want to learn more

These are supplementary, and are not required content. They are for your additional learning if you wish to watch them.

1. [Bash Basics Part 1 of 8 | Access and Navigation](https://youtu.be/eH8Z9zeywq0?t=885)
1. [Beginner's Guide to the Bash Terminal](https://www.youtube.com/watch?v=oxuRxtrO2Ag)
1. [The Most Important Thing You'll Learn in the Command Line](https://www.youtube.com/watch?v=q7-aEspwwEI)
1. [Shell Scripting Tutorial](https://www.youtube.com/watch?v=hwrnmQumtPw)
