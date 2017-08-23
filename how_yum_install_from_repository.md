Now, you know yum command - it is used in Red Hut type linux.
yum can install a lot of packeges like MongoDB, Flask, pyenv or virtualenv.
Once the command "yum install hogehoge", yum check the repository list that is registered in yum config.
yum visits the repositories and search the package on each repository. Then yum install the latest one.
A repository may contain specified package, but other repository may not contain the package, so it is useful to resister several repository.
But note that untrustfull repository may serve malice packages as it is legitimate one.
So you should not register untrustful repositories, then EPEL is trustful.
