

# 15 Common File Operators in Bash

1. `-e file`: Checks if the file exists. This operator is used to determine whether a file with the specified name exists in the file system. If the file exists, this test returns true.

2. `-f file`: Checks if the file is a regular file. This operator checks if the given file is a regular, non-directory file. It returns true if the file exists and is a regular file.

3. `-d file`: Checks if the file is a directory. It checks if the specified file is a directory. If it is, this test returns true.

4. `-s file`: Checks if the file is not empty. This operator tests if the file exists and has a size greater than zero. If the file is not empty, it returns true.

5. `-r file`: Checks if the file is readable. This test checks if the file is readable by the current user. If the user has read permissions, it returns true.

6. `-w file`: Checks if the file is writable. This operator checks if the file is writable by the current user. If the user has write permissions, it returns true.

7. `-x file`: Checks if the file is executable. It checks if the file is executable by the current user. If the user has execute permissions, it returns true.

8. `-u file`: Checks if the file has the setuid permission. This operator checks if the setuid (set user ID) permission is set on the file. If it is set, it returns true.

9. `-g file`: Checks if the file has the setgid permission. Similar to `-u`, this operator checks if the setgid (set group ID) permission is set on the file. If it is set, it returns true.

10. `-L file`: Checks if the file is a symbolic link. This operator tests if the file is a symbolic link. If it is, it returns true.

11. `-h file`: Checks if the file is a symbolic link (alternative to `-L`). `-h` is an alternative to `-L` and is used to check if the file is a symbolic link.

12. `file1 -nt file2`: Checks if `file1` is newer than `file2`. This operator compares the modification timestamps of `file1` and `file2`. If `file1` is newer, it returns true.

13. `file1 -ot file2`: Checks if `file1` is older than `file2`. This operator is opposite of `-nt`, and checks if `file1` is older than `file2`. If it is, it returns true.

14. `file1 -ef file2`: Checks if `file1` and `file2` are hard links to same physical disk data (i.e., they are links to same inode). This operator tests if `file1` and `file2` are hard links, meaning they reference same physical disk data.

15. `-O file`: Checks if you own a particular filename.
These operators are essential for performing conditional tests on files and directories in Bash scripts.


File here in represents the name of the file.
