Download Link: https://assignmentchef.com/product/solved-cs1xc3-assignment-10-git-and-github
<br>
<ul>

 <li>Use git to manage changes to a repository of code.</li>

 <li>Use GitHub to host a repository</li>

</ul>

<h1>Requirements</h1>

<em>Part A – Basics of Using GitHub</em>

Create a GitHub account.  Create a repository for storing the solution to Assignment #2 (it is posted underneath Assignment #2 on Avenue to Learn).  The solution file should be modified to contain a comment at the first line of the solution file with your name.  You do not have to provide any other information; for example you may not want to post your student ID publicly (I would not recommend this).

Provide a link to your GitHub repository in a plaintext file called <strong>as2_repos.txt</strong>.




<em>Part B – Using Git and Creating a Pull Request</em>

Using your GitHub account, fork the repository located at:

<a href="https://github.com/cs1xc3demo/lettercounter/">https://github.com/cs1xc3demo/lettercounter/</a>

Clone the repository on your local machine (i.e. your account on pascal server).

If you run <strong>git log –all –graph </strong>there will be two branches from the remote repository, origin/main and origin/feature.  Attempt to merge origin/feature into origin/main.  Resolve any conflict(s) that result and run git commit to commit the resolution.

Important: when you resolve conflicts, make sure that the changes made to BOTH branches are reflected in your new commit to the repository.  It’s not enough that you are <strong><em>able </em></strong>to commit a merged version of the branches, the <strong><em>purpose of the changes made on both branches</em></strong> needs to be reflected in your commit.  Look at the commit logs to see what was intended by each change.  You may need to modify more than the code identified by any conflict(s) in order to ensure the purpose of each change is correctly reflected in in the merge.

Your commit log message(s) should be descriptive of what was changed.

Once you have made the merge, push your local repository to the remote repository on your GitHub account (the one that you forked from the repository on cs1xc3demo).

<strong><u>DO NOT CREATE A PULL REQUEST FOR THESE CHANGES.</u> </strong>

After completing the above, provide a link to your fork GitHub repository in a plaintext file called <strong>fork_repo.txt</strong>.

<strong>Do not post solutions to other assignments on GitHub or other public spaces. </strong>

<h1>Bonus</h1>

There is a bug in the code of one of the repository branches for Part B.  If you identify it and fix it as part of your forked repository you will receive a 5 mark bonus.


