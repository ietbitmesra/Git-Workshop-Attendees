# Making a GitHub account

1. Go to https://github.com.
2. On the home page, click on ‘Sign Up’.
3. Choose a unique ‘username’ for yourself. Be careful to choose a username, as this cannot be changed in future. After that choose a free plan and follow the next instructions.

After these steps your account will be created and can be visited at https://github.com/username
Congratulations!!!!

# Configuring Git

### On Windows

1. Open Git Bash.

### On a Linux Distribution (Eg Ubuntu, Arch etc)

1. Open Terminal (`Ctrl + Alt + T`).

### On a Mac OS

1. [Open a terminal window](http://www.youtube.com/watch?v=zw7Nd67_aFw).

#### Then...

2. Enter the following command to check if git is properly installed or not:
   ```
   git --version
   ```
   The version of Git that is installed should appear. If not, then install again.

3. Enter the following to configure git:

   ```
   git config --global user.name "JohnDoe"
   git config --global user.email "johndoe@gmail.com"
   ```

4. Instead of "JohnDoe" and "johndoe@gmail.com", enter your "username" and the "email" respectively that you used to create the GitHub account. In the above example, the person's username on GitHub must be "JohnDoe".

5. Confirm that you have set the Git username and email correctly:
    ```
    git config --global user.name
    git config --global user.email
    ```

It should display the information you entered above.

**Your git setup is done :)**