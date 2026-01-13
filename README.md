# New-guideliness
# Trainin Content

# 1.0 Installation
## 1.1 Install NodeJS 21

Download **Node.js** from [Link Text](https://nodejs.org/en/download)
Select the **v21.7.3** version before download

## 1.2 Install VSCode

Download **Visual Studio Code** from [Link Text](https://code.visualstudio.com/download)

Follow the instruction to setup your VSCode
[Link Text](https://silverlakeaxisltd.sharepoint.com/:w:/r/sites/debiteam-Tech/_layouts/15/Doc.aspx?sourcedoc=%7B8BF8B546-585F-4D71-AFB9-C158EEEB67C4%7D&file=General%20Software%20Development%20Guideline%20.docx&action=default&mobileredirect=true)

**Part 1:** 
1. Go to the **File** -> **Settings** in your VS Code to setup of the settings
2. Search **EOL** in the search bar and set it to **\n**
3. Search **end of line** in the search bar and tick the **Files: Inser Final Newline** box
4. Search **format** and tick the **format on save** box
5. Search **indentation** change the Editor: Tab Size to **2**

**Part 2:** 
1. Go to **File** -> **Preferences** -> **Keyboard Shortcuts**
2. Search for **Fix All**, you can set it with a key binding set you like **(Ctrl + Alt + S)**. (you can remove other keybindings that are conflict with your key binding )

**Part 3:** 
1. Go to extension for find GitHub copilot and install it. It will be very useful when you are coding.

## 1.3 Install Git Bash and Setup SSH
Download **Git Bash** from [Link Text](https://git-scm.com/install/windows)

1. Open **Git Bash** (Please note that git bash command need to include the double quote “” for cd “path”, or any strings)
2. Add new SSH key to the laptop follow the guideline until **Adding your SSH key to the ssh-agent**,  [Link Text](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

- Paste the text in git bash, "ssh-keygen -t ed25519 -C "your_email@example.com"", keep press "Enter" until the end. *Don’t need to key in any password
- Copy the ssh key inside the file using this command, "clip < ~/.ssh/id_ed25519.pub" or simply open the id_ed25519.pub file and copy
-  Add the SSH key into GitHub settings > SSH and GPG keys
-  cd to the folder that you want to clone the project at. The commands in gitbash will be something like this cd "C:\Users\FEWJJASON.SLAKE\Desktop\Debi"
-  **In VSCode terminal**, Clone the project, by running command git clone git@github.com:fermion-labs/debi-app.git in terminal  

## 1.4 Install DBeaver
Download **DBeaver** from [Link Text](https://dbeaver.io/download/)

1. Open DBeaver, click **Database** -> **New Database Connection** -> **MariaDB**
2. Fill in the **Server Host, Username, Password** from AWS

# 2.0 Install TestFlight, DEBI
1. In TestFlight, Download DEBI SIT and Gain access from senior
