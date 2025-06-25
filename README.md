![image](https://github.com/user-attachments/assets/09fb938b-03bf-4fb0-aca2-99b2b21024b0)


# Linux: Filtering with Grep
A Linux-based filtering project utilizing the grep command to search and extract specific patterns from large system log files and text-based datasets.

# Environments and Technologies Used</h2>
- Google Cloud Virtual Machines.
- Various Linux commands (e.g., grep and the pipe | operator).

# Operating Systems Used </h2>
- Linux.

# Actions and observations

- In this scenario, we need to obtain information contained in the server log and user data files. We also need to find files with specific names.

![image](https://github.com/user-attachments/assets/2a345f37-4306-4cad-9956-2f502e436b51)

- Using the PWD command to check what directory we are currently in.

![image](https://github.com/user-attachments/assets/df96bc20-1808-40fc-91c1-0da44d3d14b6)

- Using the ls command to see a list of the directories in the /home/analyst directory.

![image](https://github.com/user-attachments/assets/42ebd930-1787-4413-ad42-1330201108bb)

- Using the CD command to navigate to the logs directory.

![image](https://github.com/user-attachments/assets/01a8b5c3-6424-4ce3-9e36-565c7f3b5d0b)

- Using the ls command to list files inside the Logs directory.

![image](https://github.com/user-attachments/assets/b761b0a4-4cee-475c-b1c5-bb3c6fda4d48)

- Using the grep command to filter for the text string error inside the server_log.txt file.

![image](https://github.com/user-attachments/assets/923cf99b-7309-4b2c-b24c-fac535d76600)

- Using the ls to search for a directory, then the | command to pipe that into the grep command.
