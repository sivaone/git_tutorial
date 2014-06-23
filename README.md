git_tutorial
============

practice git commands

Install git for windows and start git bash.
Commands to start ssh agent to connect to remote i.e. github in this case.

``$ eval `ssh-agent -s```

`$ ssh-add /c/Users/username/.ssh/id_rsa`

`$ ssh-add -l`

`$ git clone git@github.com:sivaone/git_tutorial.git`

`$ git add pom.xml`

`$ git commit -m "added initial pom file"`

`$ git push origin master`

`$ git branch task_1`

`$ git checkout task_1`

`$ git add .`

`$ git commit -m "added home servlet"`

`$ git push origin task_1`

`$ git rebase -i task_1~4`

`$ git rebase --abort`

`$ git checkout master`

`$ git pull origin master`

`$ git merge task_1`

`$ git push origin master`