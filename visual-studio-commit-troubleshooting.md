# Visual Studio Code: Unable to Perform Commit Troubleshooting Steps

This document will help students troubleshoot errors that they run into when trying to perform a git commit in **Visual Studio Code**

## Error: "Please configure your git user name and e-mail"

You can fix this error by following these steps:

1. Go to the **Visual Studio Code Terminal** using the **View > Terminal** option from the menu.
2. The **Terminal** view will then open in a window pane.
3. At the prompt enter the following and be suer to replace **yourname** with your **GitHub username**. Place your name in single or double quotes: ```git config --global user.name yourname```
4. Press the **enter key** to run the command.
5. Next enter the following in and replace **youremail@address.com** with the email address that you use for **GitHub**: ```git config --global user.email youremail@address.com```
6. Press the **enter key** to run the command.
7. Now try and perform your **commit** again.