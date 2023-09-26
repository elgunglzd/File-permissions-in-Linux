# Changing directory permission
the files and directories in the projects directory belong to the `researcher2` user. Only `researcher2` should be allowed to access the `drafts` directory and its contents. This means that no one other than `researcher2` should have execute permission.

![only researcher 2 should have access to the ](https://github.com/elgunglzd/File-permissions-in-Linux/assets/144905791/117fce8f-ce2c-40b0-be26-f86d73296914)

The first two lines of the code displays commands that I entered and the other lines display the output of the second command. Previously I determined that group has a execute permission so I used `chmod` command to remove it. The `researcer2` user has already execute permissions, so they did not need to be added.
