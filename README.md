# Restart Windows into BIOS/UEFI Settings

This guide explains how to restart a Windows computer directly into the BIOS/UEFI firmware settings using a command in an administrator Command Prompt.

## Steps:

1.  **Open Command Prompt as Administrator:**
    * Search for "cmd" in the Windows search bar.
    * Right-click on "Command Prompt".
    * Select "Run as administrator".

2.  **Execute the Command:**
    * Type the following command and press Enter:
        ```cmd
        shutdown /r /fw
        ```

3.  **Computer Restart:**
    * The computer will shut down and restart, automatically booting into the BIOS/UEFI settings.
      
      ![image](https://github.com/user-attachments/assets/2f80c636-d827-4925-ba80-0cc625849870)


## Optional: Immediately Restart

To immediately restart into BIOS without a one-minute delay, use the following command:

```cmd
shutdown /r /fw /t 0
```

## Alternative Method (Creating a Shortcut):

You can also create a shortcut on your desktop to directly execute this command.

1.  Right-click on an empty area of your desktop.
2.  Select "New" > "Shortcut".
3.  In the "Type the location of the item" field, paste one of the following commands:
    * For a restart with a one-minute delay:
        ```
        shutdown /r /fw
        ```
    * For an immediate restart:
        ```
        shutdown /r /fw /t 0
        ```
4.  Click "Next".
5.  Enter a name for your shortcut (e.g., "Restart to BIOS").
6.  Click "Finish".

![image](https://github.com/user-attachments/assets/7689d1b5-f5e2-480b-bf27-ca4ef2868679)

![image](https://github.com/user-attachments/assets/f4226c29-088d-4f2a-962a-63041d54cdf0)

To use the shortcut, right-click on it and select "Run as administrator" for faster access.
