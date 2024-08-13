<h1>Git Commands</h1>

<h2>Table of Contents</h2>
<ul>
  <li><a href="#git-add">git add</a></li>
  <li><a href="#git-add-dot">git add .</a></li>
  <li><a href="#git-branch">git branch</a></li>
  <li><a href="#git-checkout">git checkout</a></li>
  <li><a href="#git-checkout-main">git checkout main</a></li>
  <li><a href="#git-clone">git clone</a></li>
  <li><a href="#git-commit">git commit</a></li>
  <li><a href="#git-config">git config --global user.email</a></li>
  <li><a href="#git-init">git init</a></li>
  <li><a href="#git-log">git log</a></li>
  <li><a href="#git-merge">git merge</a></li>
  <li><a href="#git-remote">git remote</a></li>
  <li><a href="#git-pull">git pull</a></li>
  <li><a href="#git-push">git push</a></li>
  <li><a href="#git-revert">git revert</a></li>
  <li><a href="#git-status">git status</a></li>
  <li><a href="#git-version">git version</a></li>
</ul>

<h2 id="git-add">git add</h2>
<p>Used to move changes from the working directory to the staging area.</p>
<pre><code>git add sample.md</code></pre>

<h2 id="git-add-dot">git add .</h2>
<p>Moves all changed files into the staging area.</p>
<pre><code>git add .</code></pre>

<h2 id="git-branch">git branch</h2>
<p>Allows you to create an isolated environment within the repository to make changes.</p>
<pre><code>git branch &lt;new_branch&gt;</code></pre>

<h2 id="git-checkout">git checkout</h2>
<p>Allows you to see and change existing branches.</p>
<pre><code>git checkout &lt;existing_branch&gt;</code></pre>

<h2 id="git-checkout-main">git checkout main</h2>
<p>Switch to the main branch.</p>
<pre><code>git checkout main</code></pre>

<h2 id="git-clone">git clone</h2>
<p>Creates a copy of the remote repository.</p>
<pre><code>git clone &lt;repo-url&gt;</code></pre>

<h2 id="git-commit">git commit</h2>
<p>Takes staged snapshots of changes and commits them to the project.</p>
<pre><code>git commit -m "your commit message here"</code></pre>

<h2 id="git-config">git config --global user.email</h2>
<p>Sets a global email configuration for Git.</p>
<pre><code>git config --global user.email "youremail@example.com"</code></pre>
<p>Sets a global username configuration for Git.</p>
<pre><code>git config --global user.name "Your Name"</code></pre>

<h2 id="git-init">git init</h2>
<p>Initializes a new Git repository.</p>
<pre><code>git init &lt;directory&gt;</code></pre>

<h2 id="git-log">git log</h2>
<p>Enables browsing of previous changes to a project.</p>
<pre><code>git log</code></pre>

<h2 id="git-merge">git merge</h2>
<p>Merges changes in the active branch into another branch.</p>
<pre><code>git merge &lt;branch_name&gt;</code></pre>


<h2 id="git-remote">git remote</h2>
<p>A command to manage a set of tracked repositories.</p>
<pre><code>git remote add upstream &lt;https://github.com/original/repo.git&gt; </code></pre>

<h2 id="git-remote-v">git remote -v</h2>

<p>Allows to view the remotes associated with the local repository</p>
<pre><code>git remote -v</code></pre>


<h2 id="git-pull">git pull</h2>
<p>Transfers changes from the remote repository to your local repository and merges them into a branch.</p>
<pre><code>git pull origin main</code></pre>

<h2 id="git-push">git push</h2>
<p>Pushes all committed changes into the remote repository.</p>
<pre><code>git push origin main</code></pre>

<h2 id="git-revert">git revert</h2>
<p>Used to undo the most recent commit.</p>
<pre><code>git revert HEAD</code></pre>

<h2 id="git-status">git status</h2>
<p>Shows the state of your working directory and the staged snapshot of the changes.</p>
<pre><code>git status</code></pre>

<h2 id="git-version">git version</h2>
<p>Displays the current Git version installed on your system.</p>
<pre><code>git --version</code></pre>
