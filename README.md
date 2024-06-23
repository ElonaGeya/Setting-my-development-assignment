# Setting-my-development-assignment
1 Downloading and installing windows 11

Before downloading windows 11 start
Processor: 1 GHz or faster, with at least 2 cores on a compatible 64-bit processor or system on a chip (SoC).
Storage: 64 GB+ in storage on device.
RAM: 4 GB+
Firmware: UEFI, Secure Boot capable.
Display: >9” with HD Resolution (720p).
TPM: Trusted Platform Module (TPM) version 2.0.
Graphics Card: DirectX 12 compatible graphics / WDDM 2.x.
Internet Connection: this is necessary to ensure that updates are and downloads are performed optimally, and to take advantage of some features.

These steps are in condition that one is doing a clean install of windows 11 i.e not an update.
They are:
- Make sure that any data on PC that you don't want to lose is backed up
- Insert USB Drive/ (should be 8GB +)
- Visit the https://www.microsoft.com/software-download/windows11 link .
- Click on "PC Health Check" to confirm that your PC meets the requirements for this download.
- If requirements are met go back to the first page the link directs you to. Then click on the "Download now" button under the "Create Windows 11 Installation Media" title.
- Once download is complete, open file, wait for to get ready.
- Accept terms and conditions.
- Uncheck the "use the recommended options for this PC", if you intend on using this download on other PCs. If, leave it untouched and click "next".
- Leave on checked sd card option, then click "next"
- See your drive and click "next"
-Once windows 11 is downloaded, created and verified, click "finish" when your USB flash Card is ready.
- Boot drive by changing the boot order in your BIOS.
- To enter BIOS restart pc and press the BIOS/UEFI key for your specific computer manufacturer. Options are:
-F2: Dell, Lenovo (desktop)
-F10: HP
-F12: Acer
-Esc: Asus, HP
-Delete: MSI, Asus, Gigabyte
- Click on "boot", choose your flash drive as desired first boot option, then click f10 when complete.
- After it boots, you will be directed to a plash screen, configure how you prefer, click "next" then "install now".
- Choose which version of windows 11 you would like to install for your product key.
- Accept all terms and conditions and continue.
- Select the custom install option. 
-  Select the USB drive option (ensure your drive is empty or it will be formatted).
- Wait as your pc restarts
- Set up your pc, then let it reboot.
- After the first reboot remove your USB drive to ensure that the installing process does not get repeated.
- Then lastly, set up your pc for personal use.

2. Downloading and installing Visual Studio Code.
This process is for downloading the text editor on a Windows OS.
Here are the steps:
- Click on the https://code.visualstudio.com/Download to enter official Visual Studio Code website.
- Click on windows button to get started with the download.
- Double click on the VSCodeSetup.exe file on downloads to open it.
- To setup, start by accepting license agreement.
- Proceed if you are content with the destination location of your file, click "browse" to find whre you would like to place it. 
- Click next when the Visual Studio Code folder is created.
- Suggestively, select all additional then proceed.
- Install, then Visual Studio Code is good to go.

3. Downloading and configuring Git on Windows, creating a Git Hub account and creating a Git repository
Here's how you download Git:
-Click on the https://git-scm.com link to enter the official Git website
- Click download for Windows (insert ss)
- Then download the latest version (insert ss).
- Click on file on downloads to open it. 
- To set up, click yes then allow all default options by clicking next on all stages of the  set up until you install.
- Use command prompt to check if git is installed. To do this click windows + r then cmd, type git then enter. if the following image appears you have successfully installed git. 
P.S git as an application appears as GitBash on your PC.

To configure:
- Click windows, type GitBash and run as administrator
- Type the command git config --global user.name "Your Name", Replacing "Your Name" with your actual name. This will serve as your Git Hub username.
- To set your email type the command git config --global user.email "your.email@example.com".  Replacing "your.email@example.com" with your actual email.

Here's how you create your GitHub account:
- Click on the https://github.com link to enter the official GitHub website.
- click "sign up" on your top right corner.
- Enter the email you used to configure your git
- Create a password.
- Enter the username you used to configure your git.
- Choose whether or not to receive emails from them. type "y" for yes and "n" for no.
- Take the "you are not a robot" test.
- Once your account is created, enter the code that will be sent to email.
- Answer on how you plan to use your account, if you want your experience personalised for you. Skip if not.
- Your account is set up.

 Creating a Git Repository.
- Click windows, type GitBash and run as administrator.
- Run the command cd path/to/your/project to change to the directory where your project is located.
- Run the command git status to see which files are in the project directory.
- Run the command git add . to add all files in the directory.
- Run the command git commit -m "Initial commit" to commit the files in the staging area to the repository.
-Run the command git log to view the commit history and verify your commit.
-Now you have initialized a Git repository for your project and made your first commit.

4. Downloading and installing Python on windows.
Here that the steps to follow:
-Click on the http://www.python.org link to enter the official Python website.
- Hover above the downloads button until you see OS options the click on windows.
- Under "Python Releases for Windows" click on the latest Python release to download.
- Open the file on downloads, to start the set up.
- Select "Add Python to PATH" then customize installation.
- Click next on optional features, leaving them ad defaulted.
- Check install python for all users then install.
- Click "yes" for administrative priviledges.
- Use command prompt to check if Python is installed. To do this click windows + r then cmd, type python --version, you should see the lastest installed version of it. 

5. Installing Python Package Manager, Pip.
- Open command prompt by clicking windows + r then cmd.
- Run command python --version to check python version.
- Run command curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
- Run command python get-pip.py
- Copy the directory pip is installed in. 
- Open start menu and open environment variables
- Click on "environment variables"
- On system variables, click on "path" then edit
- Click on new then paste copied directory, then okay until the dialogue is closed.
- Your Python Package Manager, is now installed.

6. Downloading and installing mySQL database on Windows.
Here's how you go about it:
- Click https://dev.mysql.com/downloads/windows/installer/5.7.html to be directed to MySQL community downloads page 
- Select version 8.0.37, then download on the second MSI installer
- Click on "no thanks, just start my download" to start download.
-  Open the file on downloads, to start the set up.
- Click "yes" for administrative priviledges.
- When at the MySQL installer, choose custom on setup type options then next.
- Click on all MySQL 
