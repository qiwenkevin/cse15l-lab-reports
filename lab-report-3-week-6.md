# Lab Report 3

## Streamlining ssh Configuration

![ssh config](images/ssh-config.png)

This is my ssh config file. I simply edited my ssh config file with the default textedit prorgam, adding a new host ieng6 to make logging in via ssh much easier.

![ssh ieng6](images/ssh-ieng6.png)

As can be seen above, I am able to log in directly by using `ssh ieng6`.

![copy file](images/ssh%20copy%20file.png)

Then, with this config setup, I can also copy files much easier, using only `scp ~/Downloads/test.sh ieng6:~/` to copy my file over instead of the entire server name.

---

## Setup Github Access from ieng6

![github ssh](images/github%20ssh.png)

Here is the public key in my github account.

![ssh file](images/ssh%20file%20ieng6.png)

Here is the private key on my ieng6 account.

![git commit ieng6](images/git%20commit%20push%20ieng6.png)

Here I create a new file and commit it on my ieng6 account.

![git push](images/git%20push%20ieng6.png)

Here I am able to directly push the new update to github with the ssh keys.

[Here is the link for the actual commit](https://github.com/qiwenkevin/SkillDemo/commit/9dff0e9683efcf47faaa2fc19060d2d9d9778ac0)

---

## Copy whole directories with scp -r

![scp copy](images/scp-r-copy.png)

Here I can copy my whole markdown-parse directory into my ieng6 account. 

