
### Usage Instructions for Linux

To use the "Abstract Cleaner" tool on Linux, follow these steps:

1. **Download the File:**
Save the file `abstract_cleaner.html` to a folder on your Linux system (e.g., your Desktop or a dedicated folder).
2. **Locate the File:**
Open your file manager (such as Nautilus, Thunar, or Dolphin) and navigate to the folder where you saved the file.
3. **Open the File in a Browser:**
    - Right-click the `abstract_cleaner.html` file and select "Open With" → choose your preferred web browser (e.g., Firefox, Chrome, Brave).
    - Alternatively, open a terminal, navigate to the file’s directory, and run:

```
xdg-open abstract_cleaner.html
```

This command opens the file in your default browser.    
4. **Use the Tool:**
Once the file is open in your browser, you will see the "Abstract Cleaner" interface. Paste the abstract or text you want to clean, click "Fix," and review the cleaned text. You can copy the cleaned output using the button provided.    
5. **Editing the File (Optional):**
To edit the script, open the `.html` file in a text editor like Gedit, Kate, or Visual Studio Code. Save your changes and reopen the file in the browser to see the updated version.    
6. **Local Server Option (for advanced users):**    
If you encounter issues with local file access, you can run a local server in the terminal:

```
python3 -m http.server 8000
```

Then open your browser and go to `http://localhost:8000` to access the tool.

### Important Notes

- The script works offline and does not require an internet connection.
- Always check the cleaned text against the original PDF to ensure paragraph structure and formatting are preserved.

