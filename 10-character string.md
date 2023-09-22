# Explanation of each charecter in permission string
Let's look one of the permission string in more detail.

`drwx--x--- researcher2 research_team 4096 Sep 19 22:25 drafts`

First character indicates that it is a directory file. If it is `-` sign instead of `d` it means it is a regular file.

Next three character (`rwx`) belong to the user permissios. `r` means user of the file can read it. `w` means that the user can write the file and `x` means the user can execute file if it is an executable file.

After user we have group permissions (`--x`). `-` sign means that appropriate permission doesn't granted. In this case the group can not read or write the draft file but can execute it.

Last three chracter display other user's permissions (---) in the system. There are three `-` sign and means other users cannot read, write, or execute this file.
