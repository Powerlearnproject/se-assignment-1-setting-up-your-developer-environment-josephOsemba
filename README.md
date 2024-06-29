[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15347969&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   Steps:
I Visited the Windows 11 download page.
Clicked on "Download Now" to get the installation media.
Then followed the on-screen instructions to create an installation USB drive or directly upgrade my current system.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download 
Steps:
I went to the Visual Studio Code download page.
Selected the appropriate version for my OS and downloaded it.
I then runned the installer and followed the setup wizard to complete the installation.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Steps:
Download and install Git from the provided link.
Open Git Bash (installed with Git) and configure your Git username and email:

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Create a GitHub account if you don't have one.
Create a new repository on GitHub.
Clone the repository to your local machine:

git clone https://github.com/yourusername/your-repo.git
Initialize a Git repository and make your first commit:

cd your-repo
echo "# My Project" >> README.md
git add README.md
git commit -m "Initial commit"
git push origin main

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Steps:
Go to the Python download page.
Download the latest version of Python.
Run the installer and make sure to check "Add Python to PATH" during installation.
Verify the installation by opening a command prompt and typing:

python --version

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

Steps:
Pip is installed by default with Python. Verify by typing:

pip --version
If not installed, download and run get-pip.py from the official site.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Steps:
Visit the MySQL installer page.
Download the MySQL installer.
Run the installer and follow the setup wizard to install MySQL Server and MySQL Workbench.
Configure MySQL with a root password and ensure it is running.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

Steps:
Download and install Docker Desktop.
Follow the installation instructions.
Verify the installation by running:
bash
Copy code
docker --version

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   Steps:
Open Visual Studio Code.
Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window.
Search for the desired extensions and install them.

10. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.

    I had all the softwares installed prior to these classes.
    ![image](https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-josephOsemba/assets/118556308/e23cfc11-25c2-40cd-9034-21069c179254)


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
