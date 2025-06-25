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

- Using the ls to search for a directory, then the | command to pipe that into the grep command to filter for all files that have Q1 in their name.

![image](https://github.com/user-attachments/assets/9fcc2dd5-1396-4133-a72b-0610f9b15e5a)

- Using the ls to search for a directory, then the | command to pipe that into the grep command to filter for all files that have Access in their name.

![image](https://github.com/user-attachments/assets/d0d2f8a5-8670-45c3-8f72-f8722f4effc5)

- Using the Ls command to display files in the Users Directory.

![image](https://github.com/user-attachments/assets/78aecbfd-3126-4e0d-a1cf-4bde9c0e8160)

- Using the grep command to find jhill in Q2 deleted users file.

![image](https://github.com/user-attachments/assets/1cb2fdde-f21d-480c-930b-5d8a6fd255eb)

- Using ls to list the files in the user's folder again.

![image](https://github.com/user-attachments/assets/743ba398-67e5-4b33-b87b-ae3b98743386)

- Using the grep command to filter for human resource users in the Q4_added_users.txt file.



