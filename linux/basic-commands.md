# Basic Linux Commands

This file contains basic Linux commands I am learning for cybersecurity and system navigation.

---

## pwd
**Print Working Directory**

Shows the current directory you are in.

Example:
pwd

Why it matters:
Helps you know your exact location in the system, which is important when working on servers.

---

## ls
**List Directory Contents**

Lists files and folders in a directory.

Examples:
ls
ls -l
ls -a

Why it matters:
Allows you to view files, permissions, and hidden files which are often important in security.

---

## cd
**Change Directory**

Used to move between directories.

Examples:
cd /home
cd ..
cd ~

Why it matters:
Navigation is essential when analyzing systems or logs.

---

## mkdir
**Make Directory**

Creates a new folder.

Example:
mkdir test_folder

Why it matters:
Used when organizing files, scripts, or test environments.

---

## rm
**Remove Files or Directories**

Deletes files or folders.

Examples:
rm file.txt
rm -r folder_name

⚠️ Warning:
This command permanently deletes files.

Why it matters:
Attackers and defenders both use this command; understanding it prevents mistakes.

---

## clear
Clears the terminal screen.

Why it matters:
Keeps the workspace readable during long sessions.
