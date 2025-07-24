<p align="center">
    <a href="#">
        <img width="150" src="_assets/images/logo.png" alt="logo" />
    </a>
</p>

<p align="center">
    <a href="#"><img alt="license MIT" src="https://img.shields.io/badge/license-MIT-8dbb05.svg" /></a>
    <a href="#"><img alt="Stars" src="https://img.shields.io/github/stars/veffo/gitignore?style=flat-square" /></a>
    <a href="#"><img alt="Forks" src="https://img.shields.io/github/forks/veffo/gitignore?style=flat-square" /></a>
</p>

<p align="center">
    A .gitignore file used by the Git version control system to specify which files and directories to ignore.
    <br />
    <a href="mailto:q.6110@mail.ru">Report bug</a>
    ·
    <a href="mailto:q.6110@mail.ru">Request feature</a>
</p>

<div id="user-content-toc">
    <ul align="center" style="list-style: none;">
        <summary>
            <h1>
                A collection of <code>.gitignore</code> templates
            </h1>
        </summary>
    </ul>
</div>

## Table of Contents

<details>
    <summary>
        <b>Expand list</b>
    </summary>
    <ul>
        <li>
            <a href="#about-the-project">
                About The Project
            </a>
        </li>
        <li>
            <a href="#features">
                Features
            </a>
        </li>
        <li>
            <a href="#installation">
                Installation
            </a>
        </li>
        <li>
            <a href="#how-to-use">
                How To Use
            </a>
            <ul>
                <li>
                    <a href="#ignoring-single-files">
                        Ignoring single files
                    </a>
                </li>
                <li>
                    <a href="#folders">
                        Folders
                    </a>
                </li>
                <li>
                    <a href="#matching-many-characters">
                        Matching many characters
                    </a>
                </li>
            </ul>
        </li>
        <li>
            <a href="#requirements">
                Requirements
            </a>
        </li>
        <li>
            <a href="#documentation">
                Documentation
            </a>
        </li>
        <li>
            <a href="#support">
                Support
            </a>
        </li>
        <li>
            <a href="#license">
                License
            </a>
        </li>
    </ul>
</details>

## About The Project

This project is github’s collection of <a href="http://git-scm.com/docs/gitignore" target="_blank"><code>.gitignore</code></a> file templates.
Use this list to populate the `.gitignore` template choosers available
in the github.com interface when creating new repositories and files.

## Features

<ul>
    <li>
        Selecting the required files for indexing.
    </li>
    <li>
        Make a local config that will not be affected by `git pull`.
    </li>
    <li>
        Protect confidential information from accidental disclosure.
    </li>
    <li>
        Fast clean your project from temporary files.
    </li>
</ul>

## Installation

To install for local use, download this repo and copy everything from this repository to:

```bash
# Clone this repository
git clone https://github.com/veffo/gitignore

# Go into the repository
cd gitignore
```

Create a `.gitignore` file in your root directory your project.

Then you can add what you need to your `.gitignore` file.

## How To Use

## Ignoring single files

### Must specify filename and extension

```bash
example.txt
```

### Keeping single files

```bash
!example.txt
```

### Multiple files with the same extension

```bash
*.txt
```

### Multiple files with the same name

```bash
example*
```

## Folders

```bash
examples/
```

### Files inside of folders

**You can apply the same techniques for multiple files inside the root directory**

```bash
examples/example.txt
```

### Everything inside of a folder except for some files

**When first ignoring the whole folder, you must have a star at the end.**

**The star means you are ignoring the files in the folder, while not having a star means that you are ignoring the whole folder**

```bash
examples/*
!examples/example.txt
```

### Ignoring files in every directory

**This ignores all files named example.txt in every folder. You can use the same techniques for ignoring specific names or extensions with this syntax as well.**

```bash
**/example.txt
```

### Ignoring files only in the root directory

**Must include a slash in the beginning**

```bash
/example.txt
```

## Matching many characters

**This ignores files named `Example.txt` and `example.txt`. You can match against as many characters as you like at once.**

```bash
[Ee]xample.txt
```

## Requirements

<ul>
    <li>
        Git
    </li>
</ul>

## Documentation

Resources for information about how `.gitignore` files work, and how to use them:

- The <a href="https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository#_ignoring" target="_blank">Ignoring Files chapter</a> of the <a href="http://git-scm.com/book" target="_blank">Pro Git</a> book.
- The <a href="https://help.github.com/articles/ignoring-files" target="_blank">Ignoring Files article</a> on the GitHub Help site.
- The <a href="http://git-scm.com/docs/gitignore" target="_blank">gitignore</a> manual page.

## Support

For all questions, please contact us by email: <a href="mailto:q.6110@mail.ru">q.6110@mail.ru</a>

## License

This project is open-sourced software licensed under the <a href="https://opensource.org/license/MIT" target="_blank">MIT license</a>.<br/>
Distributed under the <a href="https://opensource.org/license/MIT" target="_blank">MIT license</a>. See <a href="https://opensource.org/license/MIT" target="_blank">MIT license</a> for more information.
