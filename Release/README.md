========================================================================

    Eclipse 0.25
    Encrypt / Decrypt any text with a simple hotkey
        
    Danny Ben Shitrit (Sector-Seven) 2017
    db@sector-seven.net
    
    Uses MySecret.exe (copyright DI Management Services Pty Ltd)
    http://sector-seven.net/software/eclipse
    
    This work is licensed under a 
    Creative Commons Attribution 3.0 Unported License.
    http://creativecommons.org/licenses/by/3.0/
        
========================================================================

  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, 
  EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF 
  MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT 
  OF THIRD PARTY RIGHTS. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT 
  HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER 
  IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR 
  IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE 
  SOFTWARE.
  
========================================================================

  Eclipse lets you encrypt and decrypt any text "in place".
  It uses a little command line utility called MySecret to do the actual 
  encryption.
  
  For information about MySecret go to 
  http://www.di-mgt.com.au/mysecret.html
  
------------------------------------------------------------------------
  Usage
------------------------------------------------------------------------

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

------------------------------------------------------------------------
  REVISION HISTORY
------------------------------------------------------------------------
  2017 11 26 - 0.25
    Changed: License from CC to MIT
    Changed: Code released on GitHub

  2011 12 27 - 0.24
    Changed: Password is now enclosed in quotes, allowing spaces.
    Added  : About dialog.

  2011 11 25 - 0.23
    Added  : Password window will now be Always on Top (configurable)
    Added  : Password window will now have taskbar icon (for alt-tabbing)
    Added  : Checking the Remember checkbox will still keep password in focus

  2011 03 04 - 0.22
    Added  : Configuration (INI only) to set the default state of the 
             Remember checkbox. Changed default to unchecked.

  2011 02 02 - 0.21
    Added  : Configuration dialog to select hotkeys
    Added  : Hotkey for the "Foprget Password" function
    Added  : Ability to hide the tray icon through INI file configuration. 
             (thanks Randal).

  2010 12 08 - 0.20
    Changed: Now using MySecret.exe for encryption/decryption
  
  Some time ago - 0.10
    First public release (as open source on Autohotkey forum)

========================================================================
