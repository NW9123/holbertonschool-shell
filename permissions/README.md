# permissions

| Script | Description |
| --- | --- |
| `0-iam_betty` | Switches the current user to the user `betty`. |
| `1-who_am_i` | Prints the effective username of the current user. |
| `3-new_owner` | Changes the owner of the file `hello` to the user `betty`. |
| `4-empty` | Creates an empty file called `hello`. |
| `5-execute` | Adds execute permission to the owner of the file `hello`. |
| `6-multiple_permissions` | Adds execute permission to the owner and group, and read permission to others, on the file `hello`. |
| `7-everybody` | Adds execute permission to the owner, group, and other users on the file `hello`. |
| `8-James_Bond` | Sets the file `hello` permissions to no access for owner and group, and full access for others. |
| `9-John_Doe` | Sets the file `hello` permissions to `rwxr-x-wx`. |
| `10-mirror_permissions` | Sets the mode of the file `hello` the same as the file `olleh`'s mode. |
| `11-directories_permissions` | Adds execute permission to all subdirectories of the current directory for owner, group, and others, without changing regular files. |
| `12-directory_permissions` | Creates a directory called `my_dir` with permissions 751 in the working directory. |
