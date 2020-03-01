#mydoc : keep my notes and documents

<h2>init local project and push to remote github repository</h2>
<pre>
<b>create a new repository on the command line</b>
	echo "# mydoc" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git remote add origin https://github.com/hsiarock/mydoc.git
	git push -u origin master
</pre>

<b>…or push an existing repository from the command line</b>
	git remote add origin https://github.com/hsiarock/mydoc.git
	git push -u origin master
</pre>
