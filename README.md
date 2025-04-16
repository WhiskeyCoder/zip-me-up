#🗜️ ZipAllFolder.py
Bulk ZIP every folder inside a directory — one folder, one ZIP file — all in one go.

Perfect for backup tasks, sending structured data, or creating archives for each sub-project inside a parent folder. Clean, simple, and done in seconds.

## 📦 What It Does
- Scans a target directory for folders
- Zips each folder individually
- Names the ZIP file after the folder
- Drops them all in the same directory

Example:
```
C:\MyStuff\
├── Project1\
├── Project2\
├── Logs\
```
Becomes: 
```
C:\MyStuff\
├── Project1.zip
├── Project2.zip
├── Logs.zip
```

## 🚀 How To Use
Edit the directory variable in the script to the path you want to scan.
``` directory = r"C:\FOLDER\FOLDER\FOLDER" ```
🔥 Tip: Use r"" to make the path raw — this avoids Windows backslash issues.

Run the script:
```python ZipAllFolder.py```

## 🎉 Sit back and enjoy the line:
well... that was easy

## 💡 Requirements
```Python 3.x```

Built-in libraries only: os and zipfile
No dependencies, no pip installs.

##⚠️ Notes
Doesn’t check for existing ZIPs — running it twice will overwrite without warning.

Only zips folders — not individual files in the root.

Files are stored with full internal folder paths — if you want flat ZIPs, a tweak is needed.

## 🧠 Why Use This?
Because sometimes you don’t want a bloated backup solution.
You just want to zip the damn folders.

## 🧙‍♂️ Author
Crafted by WhiskeyCoder —
Coding at 3am with a hoodie, a mug of rage-fueled tea, and a dream.

## 📜 License
MIT — because code should be as free as your Friday nights.
