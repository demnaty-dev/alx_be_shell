# Shell Permissions

## Table of Contents
1. [My name is Betty](#my-name-is-betty)
2. [Who am I](#who-am-i)
3. [Empty!](#empty!)
4. [Execute](#execute)
5. [Multiple permissions](#multiple-permissions)
6. [John Doe](#john-doe)

## My name is Betty
- **Goal:** A script that switches the current user to the user *betty*.
- **Script:** `alx_be_shell/shell_permissions/0-iam_betty`

## Who am I
- **Goal:** A script that prints the effective username of the current user.
- **Script:** `alx_be_shell/shell_permissions/1-who_am_i`

## Empty!
- **Goal:** a script that creates an empty file called *hello*.
- **Script:** `alx_be_shell/shell_permissions/4-empty`

## Execute
- **Goal:** a script that adds execute permission to the owner of the file *hello*.
- **Script:** `alx_be_shell/shell_permissions/5-execute`

## Multiple permissions
- **Goal:** a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file *hello*.
- **Script:** `alx_be_shell/shell_permissions/6-multiple_permissions`

## John Doe
- **Goal:** a script that sets the mode of the file *hello* to this:
```
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
```
- **Script:** `alx_be_shell/shell_permissions/9-John_Doe`
