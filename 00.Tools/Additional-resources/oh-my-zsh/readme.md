# Fancy your work environment with oh-my-ZSH and Dotfiles

## Overview
1. [What is zsh?](#what-is-zsh)
2. [What are dotfiles?](#what-are-dotfiles)
3. [Basic installation](#basic-installation)
4. [Examples](#examples)

## What is ZSH

ZSH, also called the Z shell, is an extended version of the terminal, with plenty of new features, and support for plugins and themes. Since it's based on the same shell as Bash, ZSH has many of the same features, and switching over is a breeze.

## What are Dotfiles
Hackers love to refine and polish their shell and tools. We'll start with a great default configuration provided by Le Wagon, stored on GitHub. As your configuration is personal, you need your own repository storing it, so you first need to fork it to your GitHub account.

## Basic installation

Please choose your operating system (OS):

<table>
  <tr>
    <td>
      <a href="macOS.md">
        <img src="images/apple.png" alt="macOS" />
      </a>
    </td>
    <td>
      <a href="UBUNTU.md">
        <img src="images/linux.png" alt="Ubuntu" />
      </a>
    </td>
  </tr>
</table>

## Examples / Getting started

Now you have installed ZSH and added custom Dotfiles to your github here's a few examples of what you are able to personalize.
From here on the information assumes you have forked Dotfiles on your github and pulled locally

* Inside of the `aliases` file you will see there's a few pre-made commands/aliases for the terminal. Any command you regularely use can be shortened. (For example making an alias for "git commit -m" to be "gcm")
* Inside of the `zshrc` file on line nr 5 you can change the ZSH theme to [something to your liking](https://github.com/robbyrussell/oh-my-zsh/wiki/themes)	