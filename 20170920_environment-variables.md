Environment variables is used in shell.  
when kernel start, shell read the configuration file like .bash_profile, .bashrc and so on.  
To use some command in shell, we have to tell shell the path by writing like this "export PATH=$PATH:/usr/local/bin".  
Then, execute "source .bash_profile" to rehash the path for example.  
We can confirm the primary path with "which" command, and confirm all the path with "printenv" command.  

