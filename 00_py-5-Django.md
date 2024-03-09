# Folder - py-5-Django

1. For my job I need to do software development
2. I do have lot files and information and need to standadize.

## Goals

1. What do I want to learn ? Master Django v.5
2. Where is it used in production ? All my Django apps shall be migrated to Django v.5
3. Timeline / Deadline ? as soon as possible
4. Deliverable ? Learning, Code for tests,

## Situation, Reasoning , and nexts tings to do

1. Start: 23-12-2023 new , Start: dd-mm-yyyy name of precurser project
2. What has been done ? Created this directory and the .env directory using python 3.12.
3. What did not work ? all worked fine
4. What are the resources (time, finance, energy) ? middle
5. What are Concepts, Diagrams, Reasoning, Outlook? Continue with Django Tutorial Part 2 with using the Djangoshell

### Folders with learning objectives

1. DjangoMoveModelExperiment_RealPython from Realpython teaches how to change and move Models (datatables in db) using Django tools and ORM.
2. FK_DjangoMastery from YTABO Djagno Mastery teaches use of of foreigne key in Django

## Prerequits for SPs

- What intepreter / virtuell machine / packages / modules / files / folders
- Do I have git ? Which server repository ?
- Where is this code synced to ? How ? 
- Does is run on Win11 , ubespace , android ? Runs on Win11

>SP: Document structure and procedure

``` text
USE----name of structure to use
CREAT--folder, file, object etc.  
COPY---"01_ProjectTemplate.md" into new \folder\ and change
     --the of the file to 00_<Name of folder>.md
VERB---documention of set-up, SP and progress (Journal section)  
```

>Creating an environment

``` text
OPEN---- Terminal
CLI----- movde to the folder, where I want to create my environment. 
TYPE---- py -3.10 -m venv .env
```

>SP: Adding packages to the environment

``` text
TYPE
py -m pip freeze > requirements.txt
py -m pip install -r requirements.txt
```

>SP: Updating package in the environment

``` text
TYPE---- python -m pip install --upgrade django
TYPE---- python -m pip install Django==3.2.13
```

>SP: Upgrade python in an environment [YVI](https://www.youtube.com/watch?v=y6xdIumaEy4)

``` text
ACTIVATE---- python virtual environment
TYPE-------- py -3.10 --version     # check what version I have before upgrade
             py -3.9 --version
DOWNLOAD---- Newest python version
INSTALL----- Downloade python version
TYPE-------- py -3.10 -m venv --upgrade (path/toMy/.env)    # Does not work since I do not have the permission apperently.
TYPE-------- py -3.10 --version
             py -3.9 --version      # check what version I have after upgrade



PS C:\Users\raine> py
Python 3.10.2 (tags/v3.10.2:a58ebcc, Jan 17 2022, 14:12:15) [MSC v.1929 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> import sys
>>> print(sys.executable)
C:\Program Files\Python310\python.exe
```

## References

1. Guideline: Set-up a development environment, which works within the folder where it is living. Use always relative path.
2. [Markdown Guide](https://www.markdownguide.org/) -> Markdown Syntax and related Software.
3. [GIThub flavored Markdown GFM](https://github.github.com/gfm/#what-is-github-flavored-markdown-) -> I use GSM specification, which is very detailed.  
4. Guideline .md: To create a new line, I use two spaces at the end of the line.
5. Installed VScode Plub-Ins: Markdown Preview Mermaid Support, Mermaid Markdown Syntax Highlighting, Markdwon All in One, Markdown Preview Enhanced, Markdownlint
6. [Mermaid Home](https://mermaid-js.github.io/mermaid/#/)
7. [How to Move a Django Model to Another App, RealPython](https://realpython.com/move-django-model/)
8. [Python Django | Getting data through Foreign Key integration | Mastery Tips and Tricks #43](https://youtu.be/zF0t666RZAY)

## Journal (today on top)

### MON 25-12

-1- Dowloaded Django 5 documentation. I can build it with Sphinx myself, for which I download the tar.gz file. I can also download entire documentin as a HTML file collection. >R: docs_Tutorial-Source_Django


### SAT 23-12-2023

-1- Finished Set-up Django 5 with py 3.12

-2- Started tutorial Djang part 2  >N: do the Djangoshell , Get local version https://docs.djangoproject.com/en/5.0/intro/whatsnext/