# How to create git repo from the command line

I use hub. "hub is an extension to command-line git that helps you do everyday GitHub tasks without ever leaving the terminal"

- Read more in the [documentation](https://hub.github.com/) about what else you can do with this tool. 

You have to have Homebrew installed. The easiest way is to follow the install instructions on the website. [click here](https://docs.brew.sh/Installation)

```zsh
# install with Homebrew (macOS, Linux)
# or see other installation options
brew install hub
```

Command to get version of hub installed
```zsh 
hub version
```

How to start a new project on the command line
```zsh
# create a repo to host a new project on GitHub
git init
git add .
git commit -m "And so, it begins."
hub create
→ (creates a new GitHub repository with the name of the current directory)
git push -u origin HEAD
```


