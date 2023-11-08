# Command line for the win

the steps i followed to use the SFTP command-line tool in my project:

1: Open the terminal on your local machine.

2: Use the SFTP command. You will need the hostname, username, and password.

`sftp username@hostname` then enter the password when prompted to authenticate password.

3: Once connected, navigate to your directory.

`cd alx-system_engineering-devops/command_line_for_the_win`

4: Use the SFTP put command to upload the screenshots from your local machine to the sandbox environment.

`put path_screenshots\*.jpg`

5: Confirm that the screenshots have been successfully transferred.

`ls`

![Alt Text](command.jpg)
