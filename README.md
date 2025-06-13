
# Red Hat Enterprise Linux 9 Administration - RHCSA


## Basic Commands and Simple Shell Scripts


### Changing users with the su command.

    su tool can help us act as several users in one session

    su = Substitute User

    whoami shows which user is logged in.

    su user

    su root

## Understanding users, groups, and basic permissions


> Multi-user environments are defined by being able to handle more than one user simultaneously. But to be able to administer the system resources, two capabilities help with the tasks:


    Groups: Can aggregate users and provide permissions for them in blocks. Each user has a primary group. By default, a group is created for each user and assigned to it as a primary with the same name as the username.
    

    Permissions: Assigned to files, determining which users and groups can access each file.Standard Linux (and UNIX or POSIX) permissions include user, group, and others (ugo).

The whole system comes with a set of permissions assigned by default to each file and directory. Be careful when changing them.


    in linux everything is a file

# # Users