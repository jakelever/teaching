# Unix Shell

This is the introductory lesson to the Unix Shell. It is estimated to take X hours.

The basic syllabus is based on the [Software Carpentry](https://software-carpentry.org) [Unix Shell Lesson](https://swcarpentry.github.io/shell-novice/)

## Requirements

- A Bash environment
- Downloading the associated lesson files (insert link here)

## Introduction

You are a digital forensics expert. 
The mayor of TOWNNAME has gone missing. 
The police suspect that the contents of his laptop may reveal what happened to him.
Using Bash, you are going to solve this mystery.

## The Files

If you haven't already, download the forensics files. Extract them to your Desktop and open a terminal window.

## Plan
- cd, ls & cat - moving around and reading READMEs to find appropriate files
- cp, mv, mkdir & rm - ???
- sh - do it early (let's create silly scripts with idiot requirements like they need the file to be in the same directory, and they need the analysis folder to be deleted, or they need a folder created)
- wc & sort - find who he emailed the most
- shell script - ???
- grep - find a password
- for loop - iterate over encrypted attachments
- find - a specific email or attachment

## Basic Syllabus from Software Carpentry
- Introducing the Shell
- Navigating Files and Directories
- Working with Files and Directories
- Pipes and Filters
- Loops
- Shell Scripts
- Finding Things

## Format Idea

There should be ~4 lessons. Each one with a brief introduction (speaking/doing) that goes through a basic example of the problem. Then there is the main problem to be solved (with assistance from helpers). And then there are bonus points (harder problems) for those that are fast.

## Chapter Plans
- Chapter 1: Last words
  - Tools: cd, ls, cat & find (and introduce up/down arrows and history)
  - Example Problem: Read the root README
  - Actual Problem: Read any emails sent on the day he disappeared
  - Result: It'll mention banking issues and a project? name: GIBSON
  - Advanced Problem: ???
- Chapter 2: Banking issues
  - Tools: sh, mkdir, rm, cp and mv
  - Example Problem: Run script that adds up banks statements and spits out summary
  - Actual Problem: Need to do it for separate months. Requires deleting analysis directory and moving data around
  - Result: We find that he had received substantial payments starting on a specific date
  - Advanced Problem: ???
- Chapter 3: Informant
  - Tools: wc, sort, head & tail (cut, uniq?)
  - Example Problem: wc, sort and tail to find who he emailed the most
  - Actual Problem: wc, sort and tail to find who emailed him the most (too similar)
  - Result: We find out that he sends a lot of emails to one person in particular (but they're all encrypted)
  - Advanced Problem: ???
- Chapter 4: Encrypted communications
  - Tools: grep, for loop, find again
  - Example Problem: Find pet's name in emails and try decrypting
  - Actual Problem: Find other passwords in emails and decrypt something else
  - Result: We find out where has gone
  - Advanced: Use find to get the email from the day that the payments started and decrypted it.

Extra things that aren't covered yet: scripting, echo

## Advanced Topics

Here's a list of advanced things that could be covered in additional chapters or should be linked to.

- variables
- if statements
- while loops for reading a file line by line
- cut, uniq
- symlinks
- awk
- regular expressions
- kill
- diff
- screen/tmux


## Hidden Answer example

<details> 
  <summary>Q1: What is the answer to the question? </summary>
   42
</details>
