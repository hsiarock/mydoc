#mydoc : my notes and documents

<h1>init local project and push to remote github repository</h1>
<p>
<pre>
	<<h2>…or create a new repository on the command line</h2>
	echo "# mydoc" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git remote add origin https://github.com/hsiarock/mydoc.git
	git push -u origin master

	<h2>…or push an existing repository from the command line</h2>
	git remote add origin https://github.com/hsiarock/mydoc.git
	git push -u origin master
</pre>
