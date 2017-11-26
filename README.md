Eclipse - Encrypt any text with a hotkey
==================================================
        
Eclipse lets you encrypt and decrypt any text "in place".
It uses a little command line utility called MySecret to do the actual 
encryption.
  
Eclipse uses [MySecret][1] command line utility for encryption.

Usage
--------------------------------------------------

- Run Eclipse.
- Select any text and press Ctrl+Shift+E.
- You will be prompted for a password.
- After entering the password, the text will be encrypted and pasted
  back in place.
- Repeat the action to decrypt the text.
- Use the system tray menu to exit or forget the password.
- You may modify the shortcut key by selecting Modify Hotkey from the 
  menu. This will create Eclipse.ini in the program's folder with 
  letting you change your hotkey.   
   
Note: The encrypted / decrypted text is also stored in the clipboard
so you may paste it anywhere else.
 
You may hide the tray icon by setting HideIcon=1 in the INI file.

---

[1]: http://www.di-mgt.com.au/mysecret.html