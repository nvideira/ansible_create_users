# ansible_create_users
A small playbook i made to add users to a VM and grant them access via rsa

The inventory and vars files are merely examples of how it should be structured.
Also, this is a task that requires elevation, so keep that in mind when running the playbook.

Edit: added a task to grant those users sudo permissions, without password.

Of course, the tasks can be separated i different files, in order to make the play more modular and flexible.
