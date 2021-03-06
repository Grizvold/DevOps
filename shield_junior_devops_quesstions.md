## Linux
1. What is your experience with Linux?
1. Give 5 commands which are two letters long
1. What are hidden files/directories? How to list them?
1. What each of the following commands does?
    + pwd
    + cd
    + find
    + ls
1. How to rename the name of a file or a directory?
1. Explain piping. How do you perform piping?
1. Where system logs are located?
1. How to follow file's content as it being appended without opening the file every time?
1. What ssh-keygen is used for?
1. What is stored in ~/.ssh/known_hosts ?
1. How to check which disks are currently mounted?
1. How would you check what is the size of a certain directory?
1. How to list all the processes running in your system?
1. How would you split a 50 lines file into 2 files of 25 lines each?
1. How to check what is the hostname of the system?
1. How to create your own environment variables?

### Docker
1. What is a Container? What is it used for?
1. Describe in detail what happens when you run docker pull image:tag?
1. How would you transfer data from one container into another?
1. Explain what each of the following commands do:
    + docker run
    + docker rm
    + docker ps
    + docker pull  
    + docker build    
    + docker commit
1. What is Dockerfile
1. What is the difference between ADD and COPY in Dockerfile?
1. What is the difference between CMD and RUN in Dockerfile?
1. Explain what is Docker compose and what is it used for
1. Describe the process of using Docker Compose

### Terraform
1. Explain what Terraform is and how does it works
1. Explain each of the following:
    + Provider
    + Resource
    + Provisioner
1. Explain what the following commands do:
    + terraform init
    + terraform plan
    + terraform validate
    + terraform apply
1. What are output variables and what terraform output does?
1. Explain remote-exec and local-exec
1. Explain "Remote State". When would you use it and how?

### Jenkins
1. What is Jenkins? What have you used it for?
1. What plugins have you used in Jenkins?
1. What type of jobs are there? Which types have you used?
1. How did you report build results to users? What ways are there to report the results?
1. Have you used Jenkins for CI or CD processes? Can you describe them?
1. Have you written Jenkins scripts? If yes, what for and how they work?

==============================================================================================

## Answers:

### Linux
1. ...
2. **Give 5 commands which are two letters long** 
    + ps - Command line utility that is used to display or view information related to the processes running in a Linux system.
    + rm - Use the rm command to delete files and directories.
    + ls - Use the "ls" command to know what files are in the directory you are in. You can see all the hidden files by using the command ???ls -a???
    + vi - Installed text editors in the Linux command line. 
    + cp - Use the cp command to copy files through the command line. It takes two arguments: The first is the location of the file to be copied, the second is where to copy.
    + cd ??? Use the "cd" command to go to a directory.
    + mv ??? Use the mv command to move files through the command line. 
    + df ??? Use the df command to see the available disk space in each of the partitions in your system. 
3. **What are hidden files/directories? How to list them?** - Hidden files are usually system or application files, concealed to prevent accidental changes. To show those files: **ls -a**. In order to hide created files/directories type *.* at the beginning of the new filename, for example: **mv test.txt .test.txt**
4. **What each of the following commands does?**
    + **pwd** -  print working directory standing from the root. ($PWD environment variable which stores the path of the current directory)
    + **cd** - change directory. 
    + **find** - command-line utility that locates files based on some user-spesificaiton. 
        + find <dir> -name *.txt find all txt files in dir, **-iname** ignores capital or small latters. 
        + find <dir> -type f -name - find all files in working directory.
        + find <dir> -type f -perm - find files with spesific permissions.
    + **ls** -
