# Wifi Extractor & Desktop Organizer

Welcome to the Wifi Extractor & Desktop Organizer! This tool helps you extract Wi-Fi passwords, organize your desktop files, change wallpapers, and capture keystrokes, all with ease. Below you'll find detailed information on how to use this script effectively.

## Features

- **Extract Wi-Fi Passwords**: View and export passwords for all saved Wi-Fi networks.
- **Organize Desktop**: Automatically organize files on your desktop into specified folders.
- **Change Wallpaper**: Randomly change the desktop wallpaper from a specified folder.
- **Capture Keystrokes**: Log keystrokes to a file.
- **Crack Zip File Passwords**: Attempt to crack password-protected zip files using a password list.

## Installation

- **Clone the Repository:** `https://github.com/cyberfantics/DesktopOrganizer.git`
- **Move Into Main Folder:** `cd DesktopOrganizer`
- **Run `main.exe` file


## Main Menu Options

1. **View passwords for all Wi-Fi devices**:
   - Displays saved Wi-Fi profiles and their passwords.
   
2. **Search for a password by device name**:
   - Allows you to search for the password of a specific Wi-Fi profile by name.
   
3. **Export passwords to a file**:
   - Exports all Wi-Fi passwords to a `wifi_passwords.txt` file.
   
4. **Start wallpaper and desktop organizer**:
   - Starts the wallpaper changer and desktop organizer. The organizer uses a configuration file (`file_types_config.json`) to determine how to categorize and move files on your desktop.
   
5. **Crack a zip file password**:
   - Attempts to crack a password-protected zip file using a specified password list.
   
6. **Exit**:
   - Exits the program.

### Additional Features

- **Keystroke Logging**:
  - Captures keystrokes and logs them to `logs.txt`.
  
- **Wallpaper Changer**:
  - Changes the desktop wallpaper every 60 seconds from a specified folder.

## Configuration

### Desktop Organizer Configuration

Create a `file_types_config.json` file in the script directory with the following format:

```json
{
  "Images": [".jpg", ".jpeg", ".png"],
  "Documents": [".pdf", ".docx", ".txt"],
  "Videos": [".mp4", ".avi"]
}
```

**Modify `json` file, as you want to `organize your desktop.`**

## Note

- **Logs**: The script generates a `logs.txt` file to store captured keystrokes. Remember to delete this file after exiting the program to maintain your privacy.
- **Exit**: Press 'q' to quit the wallpaper and desktop organizer function.

For more information, visit [cyberfantics on GitHub](https://github.com/cyberfantics).

## License

This project is licensed under the MIT License.

## Disclaimer

This tool is for educational purposes only. The author is not responsible for any misuse or damage caused by this tool.

---

Enjoy using the Wifi Extractor & Desktop Organizer! If you have any issues or suggestions, please open an issue on GitHub.
