# Developer Environment Setup Guide
 
 Table_of_Content
# Setting Up My Developer Environment
# Installing a Text Editor/integrated Development Environment (IDE)
# Setting Up Version Control System:
# Installing Necessary Programming Languages and Runtimes:
# Installing Package Managers:
# Configuring a Database (MySQL):
# Setting Up Development Environments and Virtualization (Optional):
# Explore Extensions and Plugins:

 Setting Up My Developer Environment


1. # Selecting mand installing Operating System (OS):
   I chose an operating system that best suited my project requirements, which was windows 11 then downloaded and Installed it from https://www.microsoft.com/software-download/windows11 successfully

2. # Installing a Text Editor/integrated Development Environment (IDE):
   Here i chose and IDE suitable for your programming languages and workflow but also versitile which is VS Code. Went to this website https://code.visualstudio.com/Download then followed necessary steps to install it successfully.

3. # Setting Up Version Control System:
   I installed Git and configured it on to my local machine, although it took time because my machine tends to be slow at times but eventually i was able to succeed. I then Created a GitHub account for hosting my repositories on github, initialized my first Git repository and made my first commit. 
    https://github.com
    
 # Step 1: Installing Git

First things first, I went to the official Git website: https://git-scm.com/. Once there, I found the download link that matched my computer's operating system Windows and clicked it. I followed the instructions in the installer wizard, just kept clicking "Next" or "Continue" until it was all installed.

# Step 2: Setting Up Git
Now that Git was installed, it was time to set it up! I opened up my computer's terminal or command prompt. If I was on Windows, I found it by searching for "Git Bash". Once I had that open, I typed git --version and pressed Enter. I saw a version number pop up, which meant Git was installed correctly. Next, I needed to tell Git who I was. I typed the following commands, replacing "Your Name" with my actual name and "your_email@example.com" with my email address:
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"

# Step 3: Making My First Repository
I created a new folder on my terminal where I wanted to keep my project. Once I had done that,  navigated to that folder using the cd command. For example:

cd path/to/my/folder
Once inside the folder, I typed git init and hit Enter. This initialized a new Git repository in that folder.

# Step 4: Making My First Commit

I added some content to my repository! I opened up a text editor like Notepad on Windowsand created a new file. I wrote something in it like "#HappytoleARN", and saved it as README.md. Then, I went back to my terminal or command prompt and typed git status. I saw that Git had detected a new file (README.md) that wasn't being tracked. To start tracking it, I typed git add README.md. Now, I committed this change! I typed git commit -m "Add README.md". This created a commit with a message saying "Add README.md", which explained what I did in this commit.

4. # Installing Necessary Programming Languages and Runtimes:
  Installe Python from http://wwww.python.org a programming language tha is mandatory for most of project and installed the respective compilers, interpreters, or runtimes while Ensuring that i have the necessary tools to build and execute codes using python.

# Step 1: Install Python

I went to Python website.
Download installer.
Run installer.
Checked "Add Python X.X to PATH".
Clicked "Install Now".

# Step 2: Verify Installation
Opened command prompt.
Typed python --version.

# Step 3: Optional - Set Up Virtual Environment
Navigated to project directory.
Ran python -m venv myenv.
Activated virtual environment.
Now Python was instaled and i the set up a virtual environment.

5. # Installing Package Managers:
   I then installed package manager which is pip
  
# Step 1: Check if Python is Installed
I opened a command prompt or terminal window.
I typed python --version and pressed Enter.
If Python was installed, I saw the version number. If not, I installed Python first.

# Step 2: Download get-pip.py
I went to https://bootstrap.pypa.io/get-pip.py in my web browser.
I right-clicked on the page and selected "Save As" to download get-pip.py to my computer.

# Step 3: Install pip
I opened a command prompt or terminal window.
I navigated to the directory where get-pip.py was saved using the cd command.
I typed python get-pip.py and pressed Enter to run the script.
Pip was installed. I verified by typing pip --version and pressing Enter.

6. # Configuring a Database (MySQL):
   here is how i install MySQL database.
 # Step 1:
I visited the MySQL downloads page and downloaded the MySQL Installer, https://dev.mysql.com/downloads/windows/installer/5.7.html
I opened the installer file I downloaded and followed the setup instructions.

# Step 2:Choose Custom Setup Type:
Instead of the "Developer Default," I chose the "Custom" setup option to select specific components.

# Step 3: Encounter a Problem:
During installation, I encountered an error message stating that Visual C++ Redistributable was missing.
Rectify the Problem:
I visited the Microsoft download page and downloaded the Visual C++ Redistributable package. After installing it, I restarted the MySQL installer.

# Step 4: Select Components:
In the "Custom" setup, I manually selected the components I needed, such as MySQL Server, MySQL Workbench, and MySQL Shell.

# Step 5: Install MySQL:
I clicked "Execute" to download and install the selected MySQL products.
Configuration:
After installation, the configuration wizard opened. I configured the server as per my needs, set a root password, and created user account.

7. # Setting Up Development Environments and Virtualization (Optional):

# Step 1: Installing Docker:
I downloaded Docker Desktop from the official Docker website and completed the installation process.
I created a Dockerfile to define the environment and a docker-compose.yml file to manage multi-container applications.

# Step 2: Installing VirtualBox:
I downloaded and installed VirtualBox from the official website.
I created a new virtual machine and installed the operating system (Ubuntu) on it.

# Step 3: Challenges:
Despite successfully installing these tools, I encountered difficulties in fully setting up the development environment:
Docker: I faced issues with configuring the network settings and ensuring all dependencies were correctly installed and connected. This prevented the Docker containers from running the project as expected.
VirtualBox: Setting up the virtual machine and configuring it to run the development environment proved challenging. Specifically, I had trouble with network configuration and dependency management within the VM.

While I was able to install Docker and VirtualBox, I need further assistance or resources to overcome these configuration challenges and complete the setup process.

8. # Explore Extensions and Plugins:
   To enhance the functionality of Visual Studio Code (VS Code), I explored and installed several extensions, plugins, and add-ons. These tools improve various aspects of the development process, including syntax highlighting, linting, code formatting, and version control integration. Here are some of the most useful extensions I found:

Syntax Highlighting
# Python Extension for Visual Studio Code
Description: Provides rich support for the Python language, including features such as IntelliSense, linting, and debugging.

# HTML CSS Support
Description: Enhances the editor's HTML and CSS capabilities with support for CSS class and ID completion in HTML documents.

# JavaScript (ES6) Code Snippets
Description: Adds snippets for JavaScript ES6, providing a quicker way to write standard code constructs.

# Pylint
Description: Integrates Pylint into VS Code, providing Python code analysis to enforce coding standards and find errors.

# Prettier - Code Formatter
Description: An opinionated code formatter that supports many languages, automatically formats code to maintain consistent style.

# Beautify
Description: Beautifies JavaScript, JSON, CSS, Sass, and HTML files.

# GitLens — Git supercharged
Description: Enhances the built-in Git capabilities, showing code authorship, code changes, and repository insights.

# Git History
Description: Provides a detailed view of Git history in VS Code, making it easier to review changes and track commits.

# GitHub Pull Requests and Issues
Description: Allows me to review and manage GitHub pull requests and issues directly within VS Code.

# Live Server
Description: Launches a local development server with live reload feature for static and dynamic pages.
Docker

By installing these extensions, I enhanced VS Code’s functionality, making it a powerful and efficient development environment. Each extension helps streamline various tasks, from code writing to version control, improving overall productivity.

I did not attach any image since it was (Optional)


