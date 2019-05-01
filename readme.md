<h2>Setup local git repository and connect to GitHub</h2>

<p>
Steps to use git locally.
<ol>
<li>created directory in the terminal (mkdir gittest1)</li>
<li>cd into gittest1 and perform: git init.</li>
<li>touch some files (e.g. 'touch index.html')</li>
<li>add files to stage: git add . (dot is for all changed files)</li>
<li>commit changes: git commit -m "message between double quotes"</li>
</ol>
</p>
<p>
Steps to connect local repository on my computer with Github.
<ol>
<li>Go to Github.com and sign in.</li>
<li>Create a new repository on GitHub.com and perform the second option mentioned (in your terminal): 
<br /><br />
    <i>$ git remote add origin git@github.com:username/new_repo</i>
<br />
    <i>$ git push -u origin master</i></li><br />
<li>your local repository is now connected to github!</li>
</ol>
</p>
