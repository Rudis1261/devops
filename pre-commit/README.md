# SVN Pre-Commit Hook

-------
### Pre-commit hooks are used to perform some sort of action proir to allowing the commit to continue. 

### So what does this one do? 

------

- It ensures that the commit message is not blank, by checking that it's at least 5 characters in lenght
- It also ensures that the comment contains a Mantis Ticket Number in the format of **#ticket number**


The code itself should be quite self explanatory, and if you don't understand a particular portion. You can always google that portion. 

Most of the code was adapted from the following page http://blog.grimsy.net/2008/07/a-few-svn-pre-commit-hooks/ Props to **Geoff** for his excellent blog entry. 
