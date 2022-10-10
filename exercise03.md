# Exercise 3 - Configuring your first repository

1. Enable color

        git config --global color.ui auto

2. Set your name

        git config --global user.name "John Doe"

3. Set your email address

        git config --global user.email "john.doe@somewebsite.com"

4. Why did we use the `--global` flag?  (What does that do?)
Configuring your global author information in GitHub Desktop will update the name and email address in your global Git configuration. This will be the default name and email address for all new local repositories you create in GitHub Desktop.
https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/configuring-and-customizing-github-desktop/configuring-git-for-github-desktop


5. Check your git config to show the changes you have made

        git config -l
        init.defaultbranch=master
user.name=Chris Floersch
user.email=chrisfchb@tradecustomslogistics.net


For more information, check out [Customizing Git Configuration](https://www.git-scm.com/book/en/v2/Customizing-Git-Git-Configuration)