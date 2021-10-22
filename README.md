# Transfer A Project To A Different Repository
#### Author: <a href="https://tonmoy-talukder.netlify.app/">Tonmoy Talukder</a>
CS Undergrad, AUST, Dhaka 1208, Bangladesh

## Procedures:
> - Go to cmd and clone the existing repository to your desire path: `git clone --bare https://github.com/gitHubUserName/repositoryName`
> - Then write this command: `cd repository-name`
> - Create a new repository where to transfer
> - Copy the git link of the new repository like: `https://github.com/gitHubUserName/repositoryName.git`
> - Then back to the cmd again and write: `git push --mirror https://github.com/gitHubUserName/repositoryName.git`
> - Now, to check the the origin of the repository, write on cmd: `git remote -v`
> - Opps! It is showing the origin to the old repository. Have fix this.
> - Let's change the origin to the new repository, writing on cmd this line: `git remote set-url origin https://github.com/gitHubUserName/repositoryName.git`
> - Let's to check the origin again, write again on cmd: `git remote -v`
> - Yeah, now everything is okay. Let's reload the gitHub repository and check. If anything wrong follow the procedure again or email me for more assistance.

## NB: 
```diff
- Don't copy paste the code to cmd directly, firstly read the code line and understand what to put exactly by yourself. -
```
