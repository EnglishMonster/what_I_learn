There are two way to deploy to AWS lambda from gitlab.  
One is to install dependant libraries in the repository in advance.  
Another is to install dependant libraries under gitlab-ci with the installation command in yml file it is written in the repository as hidden file.  
The latter is better because the repository don't have to retain heavy libraries and the commit log is kept clean.
