[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15244838&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

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



//ANSWERS//

Task;
1. windows 11 installation
installation with Windows 11 Installation Media
This is a way to create a bootable USB drive that you can use to clean install Windows 11 on your current Windows 10 PC or on another device. Doing so will remove all of your files, you can get to this option by going to the Windows 11 Download Page. From there, choose the Create Windows 11 Installation Media option. Then, follow the steps below.

   Step 1: Agree to the terms and choose Accept. Let the Setup tool run, and choose Use the recommended options for this PC. Click Next, and choose USB flash drive.

Step 2: Choose your USB flash drive from the list and then click Next. You'll be prompted and Windows 11 will download to it. Once finished, the installer will switch to Creating Windows 11 Installation media. You'll know when it's finished, as you'll get a prompt that the drive is ready.

 

Step 3: Once your USB drive is ready, close the installer with the Finish button. Keep the USB drive plugged into your PC.

Step 4: Head back to the Windows 10 settings app, and choose Update & security. Then choose Recovery on the left side. Under Advanced startup, choose the Restart now option.

Step 5: In the pop-up prompt, choose Use a device. Your USB drive should appear listed. Choose it, and Windows will restart to your USB drive and Windows 11 installer. If you don't see this option, you'll need to head into your BIOS or UEFI to manually boot from the USB drive. Usually, you can do this by pressing F12 on boot as soon as you turn on your PC. Contact your PC maker for more information on this or consult online guides.

 
Step 6: Once in the Windows 11 installer, select a language, and click Next. Pick the version of Windows 11 that matches the version of Windows 10 on your PC. and click Next.

Step 7: Choose the Custom option and choose the drive to install Windows 11 on. You might have to click the Format button to erase all your files on the drive. When done, select the drive again and click Next.


Step 8: Windows 11 will install to your PC, and you can sit back. You'll then be taken to the out-of-box experience, and will be prompted to set up your PC again.

Task;
2. Visual Studio Code installation.
Visit the VS Code website and download the Windows installer. (If the Download for Windows message is not displayed on the large button, select the Stable Windows package using the dropdown arrow).
After the installer fully downloads, run it. On the Select Additional Tasks screen, be sure to select both Create a desktop icon and Add to PATH.
 
The Select Additional Tasks panel.
Once the installation finishes, you need to open the application and perform a few more steps.
Configure VS Code to Use Git Bash
You need to tell VS Code to use Git Bash instead of other Windows terminal programs like PowerShell:
1. Open VS Code.
2. Open the Terminal menu from the top of the app and select New Terminal.
 
Open the terminal panel.
3. A new pane opens at the bottom of the application window. This is a terminal window. From the small dropdown found in this pane, choose Select Default Profile.
 
Find the dropdown menu in the toolbar of the terminal panel.
4. This will open a tool called the Command Palette at the top-center of the application window. Type Git Bash into the Command Palette and hit Enter.
 
Type Git Bash in the command palette.
5. Close VS Code and reopen it. Open a Terminal panel again from the menu. Verify that you see bash in the dropdown menu in the terminal pane. Now every time you open the terminal, it will default to Git Bash!
 
Task;
3. Installing Git using the GUI

Download the Git installer: Go to the official Git website and download the latest version of Git for Windows.
Run the installer: Run the downloaded file and follow the installation wizard’s prompts.

Select the installation location: Choose the installation location for Git. The default location is fine, but you can change it if you prefer.

Select the components: Choose the components you want to install, such as Git Bash, Git GUI, and Git Credential Manager.

Configure the SSH client: Select the SSH client you want to use. Git comes with its own SSH client, so you can leave the default option.

Configure the PATH: Keep the default PATH setting or change it if you prefer.
Finish the installation: Click “Next” and then “Finish” to complete the installation.

Method 2: Installing Git using the Command Line

Open the Command Prompt: Open the Command Prompt as an administrator.

Download the Git installer: Run the following command to download the latest version of Git for Windows: curl -sS https://github.com/git-for-windows/git/releases/download/v2.38.1/git-2.38.1.2-64-bit.exe

Run the installer: Run the downloaded file and follow the installation wizard’s prompts.
Configure the installation: Configure the installation as desired, such as selecting the installation location and components.

Finish the installation: Click “Next” and then “Finish” to complete the installation.
Verifying the Installation

Open the Command Prompt: Open the Command Prompt and type git --version to verify that Git is installed correctly.

Check the Git version: You should see the version number of Git installed on your system.

Task:
4. Installing python.
Visit the link https://www.python.org/downloads/

to download the latest release of Python. In this process, we will install Python 3.8.6 on ourWindows operating system. When we click on the above link, it will bring us the following page.

Step - 1: Select the Python's version to download.
Step - 2: Click on the Install Now

Double-click the executable file, which is downloaded;

the following window will open.

Select Customize installation and proceed.

Click on the Add Path check box, it will set the Python path automatically.

Selecting “Customize installation” will allow you to select the features to install, the installation location and other options or post-install actions. To install debugging symbols or binaries, you will need to use this option.

To perform an all-users installation, you should select “Customize installation”. In this case:

You may be required to provide administrative credentials or approval

Python will be installed into the Program Files directory

The Python Launcher for Windows will be installed into the Windows directory

Optional features may be selected during installation

The standard library can be pre-compiled to bytecode

If selected, the install directory will be added to the system PATH

Shortcuts are available for all users

Task;
5. installing package manager (Pip);

get-pip.py

This is a Python script that uses some bootstrapping logic to install pip.

Download the script, from https://bootstrap.pypa.io/get-pip.py.

Open a terminal/command prompt, cd to the folder containing the get-pip.py file and run:
C:> py get-pip.py

Task;
6. Installing MySQL database.

Download MySQL Installer for Windows.git

Access your Windows server and download the MySQL Installer. A free Community edition MySQL Installer is available from the official page: https://dev.mysql.com/downloads/installer/

You are given the option to download either the Web Community version or the Full MySQL package.

Option to download full or web version of the MySQL Installer.

After selecting a version, you are provided with the option of signing up for a MySQL Community account. If you are not interested, select the No thanks, just start my download option at the bottom of the page.

Location of the link to download MySQL Installer.
By selecting this option, the download process starts immediately. Once the download is complete, you can execute the MySQL Installer file from the download folder.

It can take a few moments while Windows configures the MySQL Installer and prepares the installation and configuration process.

Set Up MySQL Installer for Windows
After accepting the Oracle license agreement terms, the first screen you encounter allows you to define which MySQL products are going to be installed. You can choose between several predefined options or create your custom setup type.

Note: Preconfigured setups can be customized later if necessary.

After accepting the Oracle license agreement terms, the first screen you encounter allows you to define which MySQL products are going to be installed. You can choose between several predefined options or create your custom setup type.

Developer Default installs all the tools you need to develop and micromanage your MySQL databases effectively.
Server Only is used to install an instance of the MySQL Server and forgo other MySQL products.
Client Only installs all products except the MySQL Server and associated tools.
The Full configuration installs all available MySQL products.
A Custom setup allows you to select the individual elements that are to be installed and alter predefined default settings.

In the example below, we select the Server Only option and click Next.

Dropdown allows you to select a MySQL installation configuration.
At this point, the system tries to resolve possible inconsistencies. It might inform you that additional packages need to be installed for the process to continue (e.g., Microsoft Visual C++ 2019 Redistributable Package). You can also run into Path installation inconsistencies if you have previous MySQL installations on your Windows Server.

Luckily the MySQL Installer auto-resolves issues and installs the latest binary compatible version of missing software. You are now ready to start the installation process in earnest. Click Execute to begin the installation process.

Location of Execute button to start the MySQL installation on Windows server.
Once the status of the installation status is labeled as Complete, you are ready to configure the MySQL database.

Configure MySQL Server on Windows
The MySQL Server 8.0.19 is now ready to be configured. Initiate the process by clicking Next.

Start the MySQL configuration process by clicking Next.
1. High Availability
The first configuration option affects database availability. It allows you to decide if you want to set up a Standalone MySQL Server or an InnoDB server cluster to improve availability. In this instance, we selected the classic, single server option.

High availablility allows you to choose between a Standalone Server or InnoDB cluster.
2. Type and Networking
The Type and Networking section is used to define several essential features.

The Config Type option lets you choose between three server configuration types. Development Computer, Server Computer, and Dedicated Computer define whether the server is dedicated solely to running your MySQL database or is going to share the underlying system with other applications.

In this example, we decided to create a dedicated MySQL server.

Define how much memory resources are being alocated to MySQL server.
The Type and Networking tab can also define the port the MySQL server is listening on. The default setting is port number 3306 and can be changed to suit your needs.

By checking the Show Advanced and Logging Option box, you can set additional logging options at a later stage.

Click Next once you’ve selected the options you feel meet your requirements.

Change port number or Show Advanced Options for MySQL configuration.
3. Authentication Method
It is possible to choose between two authentication methods, the recommended Strong Password Encryption, and the Legacy Authentication Method. Select the recommended Use Strong Password Authentication option.

Choose your prefered authentication method for your MySQL database server.
4. Accounts and Roles
You are now prompted to enter a password for your MySQL root user. You can also create additional roles for various users and purposes.

This is only an initial setup, and credentials can be edited once the installation is complete.

Define user accounts and roles for MySQL Server.
5. Windows Service
By defining MySQL as a Windows Service, it can now start automatically whenever the Windows system boots.

If you decide to start MySQL as an executable application, you would need to configure it manually.

How to define MySQL as a Windows Service.
6. Logging Options (Optional)
If you have selected the Show Advanced Logging option in the Type and Networking tab, you are now able to set up MySQL log preferences.

Logging options let you select the types of logs you want to activate and define the log directories.

Customize MySQL log directories.
Click Next to reach the Advanced Options section.

7. Advanced Options (Optional)
Advanced Options include setting a unique server identifier, and the type of case (Lower/Upper) to be used for Table Names.

These settings are only available if you have checked the Show Advanced Options box in the Type and Networking tab.

8. Apply Configuration
You have successfully configured the MySQL server and need to confirm for the MySQL Installer to apply the configuration.

An overview of the configurations steps appears on the screen. Click Execute to apply the configuration.

Click Execute to apply the settings from the previuos steps.
The system informs once the configuration process is completed. Select Next to continue the installation process.

The configuration process is complete, click Next to continue the installation.
Complete MySQL Installation on Windows Server
After clicking Next, you are given the option to copy the installation process log to the Windows Clipboard.

Copy log of installation process on Clipboard and finish MySQL installation on Windows.
Click Finish to complete the MySQL server installation on Windows.

Start MySQL Server on Windows
If you need to start the MySQL Server on Windows for the first time enter the following command in the Windows Command Prompt:

"C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqld" --console

The path in this command is the default installation folder. In case you have installed MySQL in a different folder, the command needs to reflect that to launch the mysqld executable file successfully.

The --console option displays output directly on your console. Omitting this option sends the output directly to the MySQL logs.

Stop MySQL Server on Windows
To shut down MySQL Server in Windows, type the following command in the Windows Command Prompt:

"C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqladmin" -u root shutdown

task:
7. Installing vmware workstation.
visit the official website of VMware and
Hover on the Downloads tab; here, you will find various products.

Step 2. Click on Free Product Trials & Demo >> Workstation Pro. You will be redirected to the download page. (Similarly, you can select any product you want to install.)

VMware Workstation pro for demo purpose
Click on Download Now according to your Operating System. We have chosen Workstation 15 Pro for Windows.

Step 3. Once the download is complete, run the .exe to install VMware Workstation. A popup will appear.

Step 4. Once Initialization gets completed, Click on Next.

Step 5. Accept the terms and click Next

Step 6. On the next screen, It will ask for additional features; it is not mandatory to check this box. Click on Next.

Custom setup
Step 7. On the next screen, some checkboxes are populated; check them as per your requirement.

Click on Next.

 
Step 8. At this step, VMware Workstation is ready to install. Click on Install.

ready to install
Step 9. At this step, you can see installation taking place. The installation will take some time; wait for it to install properly.

wait for it to properly install
Step 10. Once the installation gets completed, you will see the following dialogue box. Click on Finish. If you have purchased the product and have a license key, click on License to enter the key.

 VMware installation gets completed

Step 11. Upon Finishing, the window will close, and You can see VMware Workstation installed icon on your Desktop.

Double Click on the icon to open the application.

Step 12. For the first time opening, if you have not entered the License key in step 7, it will ask for a license key. You can go for the trial version, free for 15 to 30 days. Click on Continue. Make sure you have Admin rights for this in Windows.

License key
At this stage, you will get the final installation message. Click on Finish.

Task 8;
8. Exploring  Extensions.
Bring up the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of VS Code or the View: Extensions command (Ctrl+Shift+X).

Extensions view icon

This will show you a list of the most popular VS Code extensions on the VS Code Marketplace.

popular extensions

Each extension in the list includes a brief description, the publisher, the download count, and a five star rating. You can select the extension item to display the extension's details page where you can learn more.

Install an extension
To install an extension, select the Install button. Once the installation is complete, the Install button will change to the Manage gear button.

