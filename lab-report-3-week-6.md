# Lab report 3, Week 6!

## Group Choice Options from Lab 5.

> 1. Streamlining ssh Configuration
    
To begin streaming lining the SSH configuration process, we had to first make an SSH file.
* My .ssh/config file: ![sshFIle](sshConfigFileImage.png)  


* This .ssh/config file was edited using notepad as shown here:
![usingSSHAlias](updatedConfigAlias.png)


With our SSH file created with the appropriate login information, we can simply use the ssh command along with the alias chosen to log into our remote account and to copy
* Utilizing the ssh command to log into my account: ![sshToLogin](uppdatedSSHUsingAlias.png)

* Copying a file into my account using an Alias ![copyingFileUsingAlias.png](copyingFileUsingAlias.png)  


> 2. Setting up Github Access from ieng6
We can provide access to Github from our ieng6 account via a SSH key which not only allows us to access Github from our ieng6 account but also eliminate the need to enter our password when sshing into a client.

* Public key made and stored on Github:
![sshGitHub](sshKeyOnGit.png)

*  Key in ieng6 account:
![linuxKey](linuxDirectoryOfKey.png)

* Running git commands whilst logged into ieng6 account
![ssOfRemoteCommit](ssOfRemoteCommitting.png)

* Link to resulting commit [title](https://github.com/JZ0ro/markdown-parser/commit/dc4a279d07887ae1233ede566a3de5d6787fe54f)

> 3. Copying whole directories with scp -r

We can copy entire directories with scp-r. This command allows us to recursively copy a directory and its subsequent files. In the case of the current directory: markdown-parse, we are capable of copying the entire directory 

* Screenshot of copying markdown directory
![Image](ssOneOfCopyRepo.png)

* Compiling and running markdwn-parser tests on ieng6 account
![Image](ssOfTesterRunOnRemote.png
)

