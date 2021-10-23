<h2>Pull Requests in GitHub</h2>

<ol>
	<li>Fork this repository</li>
	<li>Clone your forked repository on your machine</li>
	<li>Run the following command using a bash terminal in your forked repository to download all branches

```bash
	for i in $(git branch -r | grep 'Task'); do git branch --track "${i#origin/}" "$i"; done
```
</li>
	<li>Create your own branch from master with your FN</li>
	<li>Add a text file, named after your FN that contains your name/nickname, in the participants directory on your branch</li>
	<li>Commit your changes</li>
	<li>Create a PR to the original's repo master branch</li>
</ol>
<h3 color='red'>!!! Do all other tasks on your forked repository and not on the original one !!!</h3>
