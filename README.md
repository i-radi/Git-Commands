# **_Create a new repository on the command line_**

    echo "# Git-Commands" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/i-radi/Git-Commands.git
    git push -u origin main

# **_Push an existing repository from the command line_**

    git remote add origin https://github.com/i-radi/Git-Commands.git
    git branch -M main
    git push -u origin main

# **_Clone Repo_**

    git clone https://github.com/i-radi/LeetCode

# **_Pull Repo_**

    git pull origin master

# **_Remove files befor committed_**

    git reset --hard

# **_Get current branch_**

    git branch

# **_Change current branch_**

    git checkout -b newbranch

# **_Configuration_**

    git config -l
    git config --global user.name "i-radi"
    git config --global --unset user.name
    git config --global --edit

# **_Remove commit_**

    git reset --hard <hash_number_of_commit>
    git push origen main --force
