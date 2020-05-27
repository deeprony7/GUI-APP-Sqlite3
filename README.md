# GUI-APP-Sqlite3
# Part Manager

> Python/Tkinter desktop GUI app to manage customer computer parts. This app uses Sqlite3 to store data

## Usage

```bash
# Install dependencies
pipenv install

# Run script
python part_manager.py


# Compile with Pyinstaller

# Windows
pyinstaller --onefile --windowed part_manager.py
# Linux
pyinstaller -F --add-data 'db.py:.' part_manager.py
```
Credits: Brad Traversy
