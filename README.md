[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15277168&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Use the PC Health Check app provided by Microsoft to verify if your current Windows version is compatible with Windows 11.
Download Windows 11 Installation Media:

Visit the official Microsoft Windows 11 download page or use the Media Creation Tool.
Download the Windows 11 installation media as an ISO file.
Create Installation Media (if needed):

If you downloaded an ISO file, create a bootable USB drive using tools like Rufus or the Media Creation Tool.
Install Windows 11:

Insert the bootable USB drive into your PC.
Restart your computer and boot from the USB drive (typically by pressing a key during startup to access the boot menu).
Follow the on-screen instructions to install Windows 11, including selecting language, time, and keyboard preferences.
Choose the installation type (upgrade or clean installation) and follow prompts to complete the installation.
Set Up Windows 11:

After installation, customize settings such as region, account setup, and privacy preferences.
Install drivers and updates as needed.
Activate Windows 11:

If required, activate Windows 11 using a valid product key.
Update Drivers and Install Apps:

Update device drivers to ensure compatibility and functionality.
Install applications and software needed for your workflow.
Once setup is complete, explore the new features and enhancements of Windows 11.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Open your web browser and go to the official Visual Studio Code website.
Click on the "Download for Windows" button.
Run the Installer:

Once the download is complete, locate the downloaded VSCodeSetup.exe file (typically in your Downloads folder).
Double-click on VSCodeSetup.exe to run the installer.
Accept License Agreement:

In the installer window, you may be prompted to accept the license agreement. Click Next to proceed.
Select Destination Location:

Choose the destination location where you want to install Visual Studio Code. The default location is usually fine for most users. Click Next to continue.
Select Additional Tasks:

Choose any additional tasks you want the installer to perform, such as creating desktop shortcuts or adding VS Code to the PATH. Click Next.
Install:

Click on the Install button to begin the installation process. This may take a few moments to complete.
Launch Visual Studio Code:

Once the installation is finished, you can launch Visual Studio Code by clicking on the Finish button in the installer window. Alternatively, you can launch VS Code from your desktop or Start menu.
Optional: Configure Updates:

After launching VS Code, you can configure automatic updates by going to File > Preferences > Settings, searching for update mode, and choosing your preferred update mode (such as manual, automatic, or none).
Optional: Install Extensions:

Customize Visual Studio Code by installing extensions for languages, themes, and additional tools. Open the Extensions view (Ctrl+Shift+X) in VS Code and search for extensions to install.


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. 
   Initialize a Git repository for your project and make your first commit. https://github.com
   Download Git Installer:

Visit the Git official website and download the installer for your operating system (Windows in this case).
Run the Installer:
Double-click the downloaded .exe file (e.g., Git-2.x.x.x-64-bit.exe) to launch the installer.
Github account: https://github.com/oscarnyeba
sample project: https://github.com/oscarnyeba/First_project


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  Download Python Installer:

Visit the official Python website in your web browser.
Download Python:

Click on the "Downloads" menu at the top of the page.
Choose the appropriate Python version for your operating system (e.g., Windows, macOS, Linux).
Run the Python Installer:

Once the download completes, run the downloaded installer (python-3.x.x.exe for Windows, .pkg for macOS, or use package managers for Linux).
Configure Python Installation:

During the installation, ensure to select the option to add Python to PATH. This allows you to run Python commands from the command line.
Verify Python Installation:

Open a command prompt (or terminal on macOS/Linux).
Type python --version or python3 --version to verify Python is installed and the version is displayed.
Setting Up Visual Studio Code for Python
Install Visual Studio Code:

If you haven't already, follow the steps mentioned earlier to install Visual Studio Code on Windows or your respective operating system.
Install Python Extension for VS Code:

Open Visual Studio Code.
Open the Extensions view by clicking on the Extensions icon in the Activity Bar on the side or pressing Ctrl+Shift+X.
Search for "Python" in the Extensions Marketplace.
Click Install next to the "Python" extension offered by Microsoft.
Configure Python Interpreter:

Open a Python file (or create a new one) in VS Code.
At the bottom left corner of the VS Code window, click on the interpreter name (e.g., Python 3.x.x) and select Python: Select Interpreter.
Choose the Python interpreter you installed (usually located in the default Python installation directory).
Run Python Code:

Write your Python code in the VS Code editor.
Use Ctrl+S to save the file.
Press F5 to run the Python script. VS Code will use the selected Python interpreter to execute your code.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   Check if pip is Installed:

Open a command prompt or terminal.
Type pip --version or pip3 --version (on macOS/Linux) and press Enter.
If pip is installed, it will display its version number. If not, you'll see an error indicating it's not recognized.
Install or Upgrade pip (if needed):

If pip is not installed or you need to upgrade it, you can do so by running the following command in your command prompt or terminal:
python -m ensurepip --upgrade
This command ensures pip is installed or upgrades it to the latest version available.
Verify Installation:

After running the above command, verify pip installation by typing pip --version or pip3 --version again. It should now display the installed pip version without any errors.
Installing Packages with pip
Once pip is installed or upgraded, you can use it to install Python packages globally or within a virtual environment:

Install a Package:

To install a package globally, use:
pip install package_name
Replace package_name with the name of the package you want to install (e.g., numpy, requests).


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   Download MySQL Installer:

Visit the MySQL Community Downloads page.
Scroll down to find MySQL Installer for Windows. Click on "Download" for the MySQL Installer appropriate for your system architecture (32-bit or 64-bit).
Run the MySQL Installer:

Once the download completes, locate the downloaded installer file (e.g., mysql-installer-web-community-5.7.msi).
Launch the Installer:

Double-click the installer file to launch the MySQL Installer.
MySQL Installer Setup:

The MySQL Installer launches. Click Next to begin the setup process.
Choose Setup Type:

Select the setup type. For most users, choosing Developer Default is recommended, as it includes MySQL Server, MySQL Workbench, and other useful tools. Click Next.
Select Products:

Choose the MySQL products to install. Ensure at least MySQL Server is selected. Optionally, you can also install MySQL Workbench for graphical database management.
Click Next to continue.
Installation:

The installer will download and install the selected MySQL products. This process may take some time depending on your internet connection and system speed.
Configuration:

During installation, you will be prompted to configure MySQL Server. Set a root password for MySQL (ensure it's secure and memorable).
Choose the port number for MySQL Server (typically 3306).
Click Next to proceed with the configuration.
Complete Installation:

Once the installation completes, click Finish to exit the installer.
Verifying MySQL Installation
Verify MySQL Server:

Open MySQL Workbench from the Start Menu or desktop shortcut.
Connect to the MySQL Server using the root username and the password you set during installation.
Create a New Connection:

In MySQL Workbench, click on the + icon next to "MySQL Connections".
Enter the connection details (Connection Name, Hostname: localhost, Username: root, Password: [your_root_password]).
Click Test Connection to ensure the connection is successful.
Explore MySQL:

Once connected, you can create databases, tables, and perform other administrative tasks using MySQL Workbench.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
   Using Docker for Development Environments
Install Docker:

Visit the Docker website and download Docker Desktop for your operating system (Windows).
Run the installer and follow the prompts to complete the installation.
Run Docker Desktop:

Once installed, launch Docker Desktop from your desktop or Start menu.
Pull a MySQL Docker Image:

Open a terminal or command prompt.
Use the following command to pull the official MySQL Docker image:

docker pull mysql:5.7
This command downloads the MySQL 5.7 Docker image from Docker Hub.
Run MySQL Container:

Use the following command to run a MySQL container:
docker run --name mysql-container -e MYSQL_ROOT_PASSWORD=your_password -d mysql:5.7
Replace your_password with a secure password for the MySQL root user.
This command starts a MySQL container in the background.
Connect to MySQL Container:

Use MySQL Workbench or any MySQL client to connect to the MySQL server running inside the Docker container.
Use localhost as the hostname, port 3306, root as the username, and the password you specified during container setup.
Using Virtual Machines for Development Environments
Install Virtualization Software:

Choose a virtualization software such as VMware Workstation, VirtualBox, or Hyper-V (built into Windows Pro editions).
Download and install the virtualization software according to its installation instructions.
Create a Virtual Machine:

Create a new virtual machine with your chosen virtualization software.
Allocate appropriate resources (CPU, RAM, disk space) based on your project requirements.
Install Operating System:

Install a compatible operating system within the virtual machine. For example, you can install a Linux distribution like Ubuntu Server or CentOS, which are commonly used for web development.
Install MySQL:

Within the virtual machine, install MySQL using the package manager of the chosen operating system (e.g., apt for Ubuntu, yum for CentOS).
Configure MySQL:

Set up MySQL with the necessary databases, users, and permissions within the virtual machine.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   Essential Extensions for Visual Studio Code (VS Code)
Syntax Highlighting and Language Support:

Language-specific Extensions: Provides syntax highlighting, IntelliSense, and debugging for various programming languages like Python, JavaScript, Java, etc.
Example: Python, Java Extension Pack, JavaScript (ES6) code snippets.
Linting and Code Quality:

ESLint: JavaScript linter extension.
Pylint: Python linter extension.
TSLint: TypeScript linter extension.
HTMLHint: HTML linter extension.
Stylelint: CSS/SCSS/LESS linter extension.
Code Formatting:

Prettier: Code formatter for various languages including JavaScript, TypeScript, HTML, CSS, JSON, and more.
Python autopep8: Python code formatter extension.
Beautify: Code formatter for HTML, CSS, JavaScript, JSON, and more.
Version Control Integration:

GitLens: Enhances Git capabilities within VS Code, providing blame information, repository history, and more.
GitHub Pull Requests: Manage pull requests directly from VS Code.
Git History: View Git history of a file or repository.
Debugging:

Debugger for Chrome: Debug JavaScript in VS Code using the Chrome browser.
Python Extension: Provides debugging support for Python scripts.
Productivity and Utilities:

Bracket Pair Colorizer: Colorizes matching brackets in your code for easier identification.
Path Intellisense: Auto-completes filenames in your code.
Code Spell Checker: Identifies spelling errors in your code comments and strings.
Live Server: Launches a local development server with live reload capability.
How to Explore and Install Extensions in VS Code
Access Extensions Marketplace:

Open VS Code and go to the Extensions view (Ctrl+Shift+X).
Search and Install Extensions:

Use the search bar to find extensions by name (Python, GitLens) or category (Linting, Debugging).
Click Install on the extension you want to add to VS Code.
Manage Installed Extensions:

Disable, update, or remove extensions as needed from the Extensions view.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
    Table of Contents
Installing Visual Studio Code
Configuring Visual Studio Code
Installing Python
Setting Up MySQL
Using Docker for Virtualization (Optional)
Installing Essential VS Code Extensions
Customizing VS Code Settings
Troubleshooting Tips

1. Installing Visual Studio Code
Download VS Code:
Visit Visual Studio Code website and download the installer for your operating system.
Run the Installer:
Double-click the downloaded file (VSCodeSetup.exe for Windows) and follow installation prompts.
Launch VS Code:
Open VS Code from the desktop shortcut or Start menu.
2. Configuring Visual Studio Code
Extensions:
Install necessary extensions from the Extensions view (Ctrl+Shift+X).
Settings:
Customize settings like theme (Ctrl+, Ctrl- for font size), keybindings (Ctrl+K Ctrl+S), and file associations (Ctrl+Shift+P > Preferences: Open Settings).
3. Installing Python
Download Python:
Visit Python website and download the installer for Windows.
Run the Installer:
Double-click the downloaded file (python-3.x.x.exe).
Check "Add Python to PATH" during installation.
Verify Installation:
Open a command prompt and type python --version to verify Python installation.
4. Setting Up MySQL
Download MySQL:
Visit MySQL Community Downloads and download MySQL Installer for Windows.
Run the Installer:
Double-click the downloaded file (mysql-installer-web-community-5.x.x.x.msi).
Follow prompts to install MySQL Server and MySQL Workbench.
Configure MySQL:
Set root password and configure MySQL Server during installation.
5. Using Docker for Virtualization (Optional)
Install Docker:
Visit Docker website and download Docker Desktop for Windows.
Run the installer and follow prompts to complete installation.
Pull MySQL Image:
Open a terminal and run docker pull mysql:5.7.
Run MySQL container using docker run --name mysql-container -e MYSQL_ROOT_PASSWORD=your_password -d mysql:5.7.
6. Installing Essential VS Code Extensions
Extensions:
Install extensions for syntax highlighting, linting, code formatting, and version control integration (Ctrl+Shift+X).
7. Customizing VS Code Settings
Themes and Fonts:
Change theme and font size from Settings (Ctrl+,).
Keybindings:
Customize keybindings for commands (Ctrl+K Ctrl+S).
8. Troubleshooting 
Issues with Installation:
Checked system requirements and compatibility.
Ensured software versions are up-to-date.
Extension Errors:
Disabled conflicting extensions.
Checked  extension documentation for troubleshooting tips.
Environment Configuration:
Reviewed system PATH variables.



#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
