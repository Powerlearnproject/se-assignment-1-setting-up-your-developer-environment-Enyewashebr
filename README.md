[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15285901&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
## selected operating system (OS) is Windoww 11
Downloading Windows 11:

1. Go to the official Microsoft Windows 11 download page at https://www.microsoft.com/software-download/windows11
2. Click on the "Download now" button 
3. under the "Create Windows 11 installation media" section. This will download the Windows 11 Installation Assistant.
   
   
   Installing Windows 11:

Once the download is complete, run the Windows 11 Installation Assistant.
The assistant will first check if your computer meets the minimum system requirements for Windows 11.
Ensure your computer has a compatible processor, at least 4GB of RAM, and 64GB of storage.
The assistant will also check if Secure Boot and TPM 2.0 are enabled on your system.
If your computer is compatible, the assistant will provide two options:
          >>> Upgrade this PC now
          >>> Create installation media
4. Select "Upgrade this PC now" to perform an in-place upgrade.
5. Review and accept the license terms, then click "Next" to continue.
6. The assistant will download the necessary files and begin the installation process.
During the installation, your computer may restart a few times. Follow the on-screen instructions.
After the installation is complete, your computer will boot into the new Windows 11 operating system.
2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   Downloading Visual Studio Code:

1. Go to the official Visual Studio Code website at https://code.visualstudio.com/
2. Scroll down to the "Download" section and select the version for "Windows" under the "Systems" heading.
3. Click the "Download" button to start the download of the Visual Studio Code installer.


  Installing Visual Studio Code:

1. Once the download is complete, locate the installer file (usually named "VSCodeUserSetup-{version}.exe") and double-click to run it.
2. In the installation wizard, read and accept the license agreement.
3. Choose your preferred installation location. The default location is fine for most users.
4. Select any additional tasks you would like to perform during the installation, such as:
>>>>Create a desktop icon
>>>>Add "Open with Code" to Windows Explorer's right-click menu
>>>>Register Code as an editor for supported file types
5. Click "Install" to begin the installation process.
6. Wait for the installation to complete. This may take a few minutes, depending on your system's performance.



3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com


   Here is a summary of the key steps you took to set up a version control system using Git and create a GitHub account:

1. Downloading and Installing Git:
   - Visited the Git download page and selected the appropriate version for your Windows 11 operating system.
   - Launched the Git installer and went through the configuration options, accepting the default settings.
   - Ensured Git commands could be executed from the command line by selecting the option to "Use Git from the command line and also from 3rd-party software."
   - Configured the line ending conversions to "Checkout Windows-style, commit Unix-style line endings" for consistency.
   - Enabled the Git Credential Manager to simplify authentication with remote repositories.
   - Verified the successful installation by running the "git --version" command.

2. Creating a GitHub Account:
   - Visited the GitHub website and clicked on the "Sign up" button to create a new account.
   - Provided a valid email address, a unique username, and a secure password.
   - Verified the email address by clicking on the confirmation link sent by GitHub.
   - Completed the additional setup steps, including setting preferences and selecting topics of interest.
   - Explored the GitHub dashboard and configured the account settings, such as adding a profile picture and bio.

3. Generating an SSH Key:
   - Opened the Git Bash terminal and ran the "ssh-keygen" command to generate an SSH key.
   - Followed the prompts to save the key and enter a passphrase for added security.
   - Copied the contents of the public key file (id_rsa.pub) and added it to the GitHub account's SSH and GPG keys section.

By completing these steps, you have successfully set up a version control system using Git, created a GitHub account, and configured the necessary SSH key for secure communication with the remote repository. This setup will allow you to effectively manage your project versions, collaborate with other developers, and leverage the powerful features of Git and GitHub in your development workflow.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.




To ensure I had the necessary programming language for my project, I proceeded to install Python.

I started by visiting the Python download page to access the latest version compatible with Windows. Once on the page, I downloaded the installer corresponding to my operating system. During the download, I made sure to select the appropriate version based on my system architecture (64-bit) and Python version (Python 3.12.3 which is recommended for most modern projects).

After the download completed, I launched the Python installer. The installer welcomed me with a setup wizard, which I followed step-by-step. One critical step during the installation was to ensure that the "Add Python to PATH" option was checked. Enabling this option allows Python to be recognized and executed from the Command Prompt or terminal, simplifying the process of running Python scripts and managing Python packages.

Throughout the setup wizard, I opted for the default installation settings, which included selecting the standard libraries and tools provided by Python. These defaults are sufficient for most development tasks and ensure a smooth installation process without unnecessary complications.

Once all the necessary options were selected, I initiated the installation process and patiently waited for it to complete. Depending on the system's performance, the installation typically takes a few minutes.

To verify that Python was installed correctly and accessible from the command line, I opened the Command Prompt and typed the following command:

python --version
This command returned the installed Python version, confirming that Python was successfully installed and added to the system's PATH environment variable.

With Python installed and configured, I was equipped to write and execute Python scripts, develop Python-based applications, and leverage the extensive ecosystem of Python libraries and frameworks for my project requirements.

  







5. Install Package Managers:
   If applicable, install package managers like pip (Python).


As pip is a crucial package manager for Python, I ensured it was installed alongside Python. Here's a detailed account of the pip installation process:

Since pip comes bundled with Python, there was no need for a separate download or installation process. However, I verified its installation to confirm its availability and functionality for managing Python packages.

To verify the presence and functionality of pip, I opened the Command Prompt and typed the following command:

pip --version
Executing this command returned information about the installed version of pip,(24.0),confirming that it was successfully installed and accessible from the command line.

In the event that pip was not installed or needed to be updated, I would have followed these steps:

Download get-pip.py from the official Python website or directly from this link. With the get-pip.py file downloaded, I would navigate to its location using the Command Prompt.
I would then run the following command to install pip: python get-pip.py This command would execute the get-pip.py script, which installs or updates pip to the latest version available.
Fortunately, since pip was already installed with Python, I did not need to perform the additional steps outlined above. The successful verification of pip's installation ensured that I could easily manage Python packages and dependencies for my project using pip commands. This command would execute the get-pip.py script, which installs or updates pip to the latest version available.

Fortunately, since pip was already installed with Python, I did not need to perform the additional steps outlined above. The successful verification of pip's installation ensured that I could easily manage Python packages and dependencies for my project using pip commands.



6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

 I started by visiting the MySQL Installer download page to obtain the MySQL Installer. Once on the page, I downloaded the MySQL Installer suitable for Windows. After the download completed, I launched the installer to begin the installation process.

During the installation, the MySQL Installer presented me with several options. I selected the "Server only" option since I only needed the MySQL server component for my project. This streamlined the installation by excluding unnecessary components.

As the setup wizard progressed, I was prompted to configure important settings, such as setting the MySQL root password and defining other necessary configurations like the server's port number and networking options. I ensured to set a strong and secure root password, which is essential for database security.

After completing the setup wizard and confirming my configuration choices, I allowed the installer to proceed with the installation process. This involved downloading and installing the MySQL server component along with any required dependencies.

Once the installation completed successfully, I verified the MySQL installation to ensure it was functioning correctly. I did this by opening the MySQL command line client from the Start menu and logging in using the root user credentials and the password I had set during installation. This allowed me to access the MySQL server and execute SQL commands to manage databases, tables, and data effectively.

The successful verification of MySQL installation indicated that the database system was ready for use. It provided me with a robust platform to store and manage data for my project, ensuring reliability, scalability, and security in handling database operations.





7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.



   To enhance the isolation of project dependencies and ensure consistent environments across different machines, I opted to set up development environments using virtualization tools like Docker.

Firstly, I visited Docker's website and downloaded Docker Desktop, a powerful tool for containerization and virtualization. The download was straightforward and accessible directly from Docker's official website.

After downloading Docker Desktop, I followed the installation instructions provided by the setup wizard. The wizard guided me through the necessary steps, including accepting the license agreement, selecting installation options, and configuring Docker's settings according to my preferences. This included options such as enabling WSL 2 (Windows Subsystem for Linux 2) for better performance and compatibility.

Once the installation completed, I tested Docker's installation to ensure it was set up correctly. I opened the Command Prompt and entered the following command:

docker --version
Executing this command returned information about the installed version of Docker, confirming that Docker was successfully installed and ready to use.

Additionally, I explored Docker's functionalities and capabilities, such as creating and managing containers, building Docker images, and working with Docker Compose for multi-container applications. Docker's ability to encapsulate dependencies and applications in containers provided me with a streamlined and consistent development environment, making it easier to share and deploy my projects across different systems.





8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.



   To enhance the functionality and capabilities of Visual Studio Code, I explored and installed several extensions and plugins. Here's a detailed account of the process:

I began by opening Visual Studio Code and navigating to the Extensions view by pressing Ctrl + Shift + X, which opened the Extensions Marketplace. From there, I explored various extensions categorized by functionality and purpose.

Python Extension: As Python was a primary language for my project, I installed the Python extension to enhance my Python development experience. This extension provided features such as code linting, debugging, IntelliSense for code completion, and Python environment management, making it easier to write, debug, and manage Python code within Visual Studio Code.

GitLens Extension: To enhance my version control capabilities, I installed the GitLens extension. GitLens provided advanced Git features directly within Visual Studio Code, such as Git blame annotations, commit history exploration, code authorship details, and real-time collaboration insights. This extension greatly improved my productivity when working with Git repositories.

Docker Extension: Since I had Docker installed for containerization purposes, I installed the Docker extension to integrate Docker functionalities directly into Visual Studio Code. This extension provided features such as managing Docker containers, images, and Docker Compose files, enabling seamless Docker integration and management within my development environment.

MySQL Extension: As I was using MySQL for database management, I installed the MySQL extension for Visual Studio Code. This extension offered features for connecting to MySQL databases, executing SQL queries, managing database objects, and visualizing database schemas directly from within Visual Studio Code. It provided a convenient way to work with MySQL databases without leaving the code editor.

By installing these extensions, I enhanced the functionality of Visual Studio Code, making it a powerful and versatile development environment tailored to my project's requirements. These extensions streamlined my workflow, improved code quality, and provided essential tools for effective development, version control, containerization, and database management within a single integrated environment.

Reflection on Challenges and Solutions

Throughout the setup process for my development environment, I encountered several challenges that required careful attention and problem-solving strategies. Here's a reflection on the challenges faced and the solutions employed:

Challenges:

Windows 11 Installation Issues: During the upgrade to Windows 11, I encountered compatibility issues with older hardware components. This resulted in unexpected errors and system instability during the installation process.

Python Path Configuration: Initially, Python was not recognized in the command line, which hindered my ability to run Python scripts and execute Python commands directly. This posed a significant obstacle to my development workflow.

MySQL Installation Errors: While installing MySQL, I encountered errors related to starting the MySQL service. This prevented me from using MySQL databases effectively within my development environment.

Solutions:

Windows 11 Installation Issues: To overcome the compatibility issues with older hardware, I took proactive measures to update hardware drivers and BIOS settings. This ensured that my system was compatible with Windows 11's requirements, allowing the installation to proceed smoothly without further complications.

Python Path Configuration: I resolved the Python path configuration issue by ensuring that the "Add Python to PATH" option was checked during the Python installation process. Additionally, I manually added Python to the PATH environment variable to ensure it was recognized and accessible from the command line, enabling me to execute Python commands seamlessly.

MySQL Installation Errors: To address the MySQL installation errors, I conducted a thorough investigation into potential causes, such as port conflicts and existing MySQL installations that could be conflicting with the new setup. By identifying and resolving these conflicts, I successfully started the MySQL service and integrated MySQL databases into my development environment.

Strategies Employed:

Documentation: I relied on official documentation provided by Microsoft, Python, MySQL, and other software vendors to troubleshoot issues and understand the setup requirements thoroughly. Documentation served as a valuable resource for step-by-step instructions, configuration guidelines, and troubleshooting tips.

Community Support: I leveraged community support platforms such as Stack Overflow, developer forums, and online communities to seek advice, solutions, and insights from experienced developers and technical experts. Engaging with the community provided diverse perspectives and innovative solutions to overcome challenges.

Incremental Setup: I adopted an incremental setup approach, breaking down the setup process into smaller, manageable steps. This allowed me to isolate and address issues effectively, minimizing the impact of any encountered challenges and ensuring a systematic and successful setup of my development environment.

By employing these strategies and actively seeking solutions, I was able to overcome the challenges encountered during the setup process and create a robust, functional, and efficient development environment tailored to my project's requirements.



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
