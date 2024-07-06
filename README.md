## Introduction

Azad Chahal, PhD II Agricultural and Biological Engineering II Penn State👋

- 🔭 I’m currently working on Digitalization Farming and Solutions 
- 👯 I’m looking to collaborate on project regarding data science on Farm Managements
- 🌱 I’m currently learning GIS Software Development
- 🤔 I’m looking for help with Ag Data science projects
- 💬 Ask me about: Data Analytics, Data-Driven Modals, ADO, Ag Tech and Digitalization
- 📫 How to reach me: azadchahalpau@gmail.com

## Projects (How to add hyperlinks, Toggle Hyperlink or Control + L)
- GIS Software Development: A Python package for interactive mapping with Google Earth Engine
- [geemap](https://geemap.org): A Python package for interactive mapping of Google Earth engine 
- [leafmap](https://leafmap.org): A Python package for interactive mapping with folium, ipyleaflet, and ipwidgets.
- GitHub Profile repository: azadchahal (https://github.com/AzadChahal/azadchahal) 
- Personal Website (azadchahal.github.io) repository from GitHub : azadchahal.github.io (https://github.com/AzadChahal/azadchahal.github.io)
- Python Package Repository; digitaldatai: https://github.com/AzadChahal/digitaldatai

## Demos (How to add images), 
Ag _ Science_ Data!

![Image](https://waller.agrilife.org/welcome-to-waller-county/agriculture-2/)

You have to plant first!

![Planting](https://www.utsa.edu/today/2024/images/regenerative-agriculture-_680.png) 


## Some useful links

Cookiecutter template for a Python Package : https://github.com/cookiecutter/cookiecutter

GitHub repo: https://github.com/opengeos/cookiecutter-pypackage

Documentation: https://open.gishub.org/cookiecutter-pypackage

Free Software: BSD license

## Resources and Steps: 

1. Visual Studio Code
    - Download from https://code.visualstudio.com
        - Download and then Install
        - While installing, recommended add below two options as well
            - Select Additional Tasks
                - Checkmark Add "Open with Code" action to Window Explorer file context menu
                - Checkmark Add "Open with Code" action to Windows Explorer directory context menu
    - You can check for version from Help
    - Recommended VS Code extensions: 
        - Python
        - Jupyter
        - GitHub Copilot 
        - GitHub Copilot Chat
        - GitHub Pull Requests and Issues
        - GitHub Pull Requests and Issues
        - Code Spell Checker
        - CodeSnap
        - Markdown Shortcuts
        - GitLens
        - Prettier - Code formatter
        - auto-Docstring Python Docstring Generator
        - Material Icon Theme
    - If your VS Code terminal does not work, Run Windows PowerShell as administrator and paste Set-ExecutionPolicy Unrestricted into the Powershell. Hit Enter and Type A (Yes to All)

2. Git
    -  Git is a software. It is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency
    - Download from https://git-scm.com
        - Download Standalone Installer
        - Save and Install
        - While Installing, 
            - Choose the default editor used by Git
                - Use Visual Studio Code as Git's default editor
            - To Check if it is successfully installment, 
                - You can launch Git Bash if you want
                - Another way check in your "Terminal"
                    - Type git and then hit enter and see it is successfully installed
    - Common Git commands
        - Git Configuration
            - gitconfig--global user.name "Your Name"
            - git config-- global user.email "you@someplace.com"
            - git config--global--list
            - git clone https:/github.com/USERNAME/REPONAME.git
        - Git Initialization
            - gitinit[project-name]
        - Git Commmit
            - git add.
            - git commit-m "comment message"
            - git status
            - git push
            - git config credential.helper store
            - git pull
        - Git Branch
            - git checkout-b feature
            - git status
            - git add.
            - git commit-m "message"
            - git push       
    - Sign up for a GitHub account at https://github.com
3. Miniconda
    - Download https://docs.conda.io/en/latesh/miniconda.html
    - Download and Install
        - Install to all default setting
    - Conda is a package manager. It allows to create virtual environment
    - Ex: you can create as many virtual environment you want.

- What all these softwares are doing? 
    - Vizio Studio Code: Environment to write code
    - Git: Can connect to git hub. Can help pull changes
    - Conda: Helps to create virtual environments. To test the features

- Install packages 
    - Testing in Terminal
    - (base): 
    - conda hit enter, no error then it's good
    - ![Terminal Environment](image-2.png)
    - To check the environments, ```conda env list```
    - To create a new environment, ``` conda create  -n geo python ```
    - To activate a package, ```conda activate geo```
    - ![Virtual environment](image-3.png)
    - To install a new package, ```conda install - c conda - forge mamba```
    - To install a package from Git ```pip install git+ url```
    - To install package locally 
        - '''down zip, 
        - unzip the directory by extract all
        - project folder
        - go the files and click to open the Terminal, 
        - Or copy the path of the directory
        - Go to Terminate, having your conda directory activated
        - cd + paste the navigation
        - Next line type ``dir```
        - type ``` pip install .``` Period mean install from local computer
    - To upgrade the package ```pip install -U package name```
 
 4. The name of the package (thescienceai or digitaldataai)

 5. Python Packages repository
    - PyPi: https://pypi.org/
        - numpy.org

    - Condaforge: https://conda-forge.org

6. Create your website from GitHub
    - Create a new repository
    - Set unique username: abc
    - License Type: MIT license
    - Finally go to Action Tab and wait it got deployed
    - Website template available now: https;//html5up.net/
    - If interested (not required) get domain name from GoDaddy website
  
7. GitHub Profile
    - Create a new repository
    - Repository Name: abc
    - Description
    - Checkmark "Add a README file
    - Choose a license
    - Create repository

8. Python package with a cookiecutter template (https://www.youtube.com/watch?v=Z2d1Kw1xSVY)
    - Sample Repository: https://github.com/opengeos/cookiecutter-pypackage
    - Create a bunch of templates to create a Python package
        - pyproject.toml (This shows you all the dependencies)
        - docs (Holds the website - can be done in Mackdowns)
        - Steps: 
            0. Install the packages with your Terminal or Anaconda Prompt
                - ```pip install cookiecutter bump-my-version```
            1. Create the Package Structure
                - conda activate geo
                - paste: cookiecutter gh:opengeos/cookiecutter-pypackage
                - Once the package been built, look for it in your computer (navigation on Terminal could help!)
            2. Initialize and Commit to Git


9. **Python Basics** 
    - Follow my Websites for Python Basics ```https://azadchahal.github.io/digitaldatai/```
    - 01 Getting Started (Jupyter Notebook Keyboard Shortcuts)
        - Shift-Enter: run cell, select below
        - Ctrl- Enter: run selected cells 
        - Alt-Enter: run cell and insert below
        - Tab: code completion or indent
        - Shift-Tab: tooltip
        - Matplotlob plotting: %matplotlib inline

        Reference: Matthes, Eric (2022). Python Crash Course, 3rd Edition: A Hands-On, Project-Based Introduction to Programming. No Starch Press.ISBN: 978-1593279288.

    - 02 variables data type
        - In this part you'll learn about the different kind of data you work with in your Python programs. You'll also learn how to use variables to represent data in your programs
            - Variables
            - Strings
            - Numbers
            - Comments

       - Variables
            - Variables: Variables names can contain only letters, and underscores. They can start with a letter or an underscore, but not with a number. 
            - For instance, 
                - you can call a variable ```message_1``` but not ```1_message```. 
                - ```greeting_message``` is good but ```greeting message``` will cause errors.
                - Avoid using Python keywords and function names as variable names; Python keywords: https://www.programiz.com/python-programming/keyword-list
                - Variable names should be short but descriptive. For example, name is better than n, student_name is better than s_n, and name_length is better than length_of_persons_name.
                - Be careful when using the lowercase letter l and the uppercase letter O because they could be confused with the numbers 1 and 0.
            - Note: The Python variables you’re using at this point should be lowercase. You won’t get errors if you use uppercase letters, but uppercase letters in variable names have special meanings that we’ll discuss in later chapters.
            - Some Examples: 
            - ![Variable 01](image-4.png)
            - ![variable 02](image-5.png)
            
        - Strings
            - A _string_ is a series of characters. Anything inside quotes is considered a string in Python, and you can use single or double quotes around your strings like this:
                - ```"This is a string."```
                - ```'This is also a string.'```
                - This flexibility allows you to use quotes and apostrophes within your strings 
                - ```'I told my friend, "Python is my favorite language!"'```
               - ```"The language 'Python' is named after Monty Python, not the snake."```
               - ```"One of Python's strengths is its diverse and supportive community."```
               - Some Examples
               - ![string1](image-6.png)
               - ![alt text](image-7.png)
               - ![alt text](image-8.png)
               - ![alt text](image-9.png)
               - ![alt text](image-10.png)
               - ![alt text](image-11.png)
               - ![alt text](image-12.png)
               - ![alt text](image-13.png)
               - ![alt text](image-14.png)
               - ![alt text](image-15.png)

        - Numbers
            - Numbers are used quite often in programming to keep score in games, represents data in visualizations, store information, store information in web application, and so on. Python treats numbers in several different ways, depending on how they're being used. Let's first look at how Python manages integers, because they're simplest to work with

            - Integers
                - You can add (+), subtract (-), multiple (*), and divide (/) integers in Python.
                - Can also handle the power of the number 3**3 = 27
            - Floats
                - Python calls any number with a decimal point a float. This team is used in most programming languages, and it refers to the fact that a decimal point can appears at any position in a number. Every programming language must be carefully designed to properly manage decimal numbers so numbers behave appropriately no matter where the decimal points appears.
            - Integers and Floats
                - When you divide any numbers, even if they are integers that result in a whole number, you're always get a float:
                - ![alt text](image-17.png)
                - if you mix an integer and a float in any other operation, you'll get a float as well:
                - ![alt text](image-16.png)
            - Underscores in Numbers
                - ![alt text](image-18.png)
            - Multiple Assignment
                - You can assign values to more than one variable using just a single line. This can help shorten your programs and make then easier to read; you'll use this technique most often when initializing a set of numbers. For example. here's how you can initialize the variables x,y,and z to zero:
        - Constants
            - A constant is like a variable whose value stays the same throughout the life of the program.Python doesn't have built-in constant types, but Python programers use all capital letters to indicate a variable should be treated as a constant and never be changed
            - ![Constants](image-19.png)
        - Comments
            - In Python, the hash mark (#) indicates a comment. Anything following a hash mark in your code is ignored by the Python interpreter.
            - Shortcut for making comments in Jupyter Notebook: Ctrl+/

        - July 06 Test
            









