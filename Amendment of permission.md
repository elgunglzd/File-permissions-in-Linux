# Changing permissions of the files using Linux command
 My organization doesn't allow other to have write acces to any files. So identified which files need to have its permissions modified. So i used `chmod` command to change files' permissions.

![image3](https://github.com/elgunglzd/File-permissions-in-Linux/assets/144905791/f089fcad-3af8-499b-9332-877ac28ffa4f)

I found that only other users only have write permission on `project_k.txt`. The first two lines of the screenshot displays the commands that I entered. After `chmod` I used `o-w` command. `o` means other and `w` is write. The hypen means that I take the write permission from other users. At the end of the file I mensioned the file that I want modify. Then I entered `ls-la` command to display the permissions of the files again.
