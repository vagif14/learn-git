Step 1

Donwload git app from [url](https://git-scm.com/download/win)

After install write comman below

    git config --global user.name "Your name"
    git config --global user.email "your github email"

## if we have local files and need to push github
1. Inside project open terminal after type `git init`
2. Go to repository url and find `### …or push an existing repository from the command line` text
below the text we have command copy first line of code and paste in terminal
3.  after `git add .`
4. `git commit -m 'your message`
5. When we start `git push` we get an error

    fatal: The current branch master has no upstream branch.
    To push the current branch and set the remote as upstream, use
    
        git push --set-upstream origin master
    
    To have this happen automatically for branches without a tracking
    upstream, see 'push.autoSetupRemote' in 'git help config'.



## if you have an error in red then you didn install git properly