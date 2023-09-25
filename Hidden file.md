# Changing file permission on a hidden file.
The research team has archived `project_x.txt`, which is why it's a hidden file. This file should not have write permission for anyone, but the user and group should be able to read the file.

![adding only read permission to user and group](https://github.com/elgunglzd/File-permissions-in-Linux/assets/144905791/9f206491-e3e3-46f0-b1ca-6e28207d7e58)

I did this operation with `chmod` command. After that I wrote `u=r--`. `u` stands for user and `r` means read permission. The hypens display that user doesn't have write and execute permissions. Then I wrote the same thing for goup (`g=r--`). At the end of the first line I mensioned the file that I want to modify. In the second line `ls-la` was used to displays the current permission system of files.
