# AndelaALCPH

Introduction to using Github in Android Studio

<p>Firstly, let&#8217;s login to <a title="GitHub" href="http://github.com" target="_blank">github.com</a> and create a new repository. From the top right corner of the screen, click the <em><strong>+</strong></em> sign and select <em><strong>New repository</strong></em>.</p>
<p> ![Alt text](./images/image (1).png "Github") </p>
<p>Now complete the form to create a new repository called <strong><em>testproject</em></strong>. Leave the <em>Initialize this repository with a README</em><em> <strong>unticked</strong></em>.</p>
<p> ![Alt text](./images/image (2).png "Github") </p>
<p>Next, open <strong><em>Android Studio</em></strong> and create a new project. Call your new application <strong><em>TestProject</em></strong>. Click <strong><em>Next</em></strong> to continue.</p>
<p> ![Alt text](./images/image (3).png "Github") </p>
<p>Leave the next page as default and click <strong><em>Next</em></strong>.</p>
<p> ![Alt text](./images/image (4).png "Github") </p>
<p>On the <strong><em>Add an activity to Mobile</em></strong> screen select <strong><em>Blank Activity</em></strong> and click <strong><em>Next</em></strong>.</p>
<p> ![Alt text](./images/image (5).png "Github") </p>
<p>In the next screen, leave the default activity name of MyActivity and click Finish.</p>
<p> ![Alt text](./images/image (5).png "Github") </p>
<p>Your new project will open in Android Studio. On the top menu, select <strong><em>VCS</em></strong> &gt; <strong><em>Import into Version Control</em></strong> &gt; <strong><em>Create Git Repository</em></strong>.</p>
<p> ![Alt text](./images/image (6).png "Github") </p>
<p>On the next screen, leave it all as default and click <strong><em>OK</em></strong>.</p>
<p> ![Alt text](./images/image (7).png "Github") </p>
<p>Now use Windows Explorer and navigate to the root of your projects folder. Right click and select <em><strong>Git Bash</strong></em> (If you do not see this option, then first install <a title="Git for Windows" href="http://git-scm.com/download/win" target="_blank">Git for Windows</a>).</p>
<p>When the Git bash screen appears, type:</p>
<pre class="brush: bash; title: ; notranslate" title="">

git remote add origin https://github.com/[username]/[project_name].git

</pre>
<p>An example of a Git repository URL is: <strong><em>https://github.com/markwint/testproject.git</em></strong></p>
<p> ![Alt text](./images/image (8).png "Github") </p>
<p>Then press enter. The GitHub remote will be added to your Git repository.</p>
<p>Next, jump back into Android Studio, right click your projects root directory and select <strong><em>Git</em></strong> &gt; <strong><em>Add</em></strong>. This will add all your project files to your Git repository.</p>
<p> ![Alt text](./images/image (9).png "Github") </p>
<p>It will seem like nothing has happened, but trust me, the project files are added.</p>
<p>Now right click the project name again and this time select <strong><em>Git</em></strong> &gt; <strong><em>Commit Directory</em></strong>.</p>
<p> ![Alt text](./images/image (10).png "Github") </p>
<p>In the next screen, type a <strong><em>Commit Message</em></strong> and select <strong><em>Commit</em></strong>.</p>
<p> ![Alt text](./images/image (11).png "Github") </p>
<p>If a Code Analysis warning appears, click <strong><em>Commit</em></strong>. (Unless it&#8217;s a real project, in which case review and fix the issue before committing!)</p>
<p> ![Alt text](./images/image (12).png "Github") </p>
<p>Now, right click the project name, select <strong><em>Git</em></strong> &gt; <strong><em>Repository</em></strong> &gt; <em><strong>Push</strong></em>.</p>
<p> ![Alt text](./images/image (13).png "Github") </p>
<p>Check the box <strong><em>Push current branch to alternative branch</em></strong> and leave the branch name as <em><strong>master</strong></em>. Then select <em><strong>push</strong></em>.</p>
<p> ![Alt text](./images/image (14).png "Github") </p>
<p>Now enter your GitHub <strong><em>Login</em></strong> (email address) and <strong><em>Password</em></strong>. Then click <strong><em>OK</em></strong>.</p>
<p> ![Alt text](./images/image (15).png "Github") </p>
<p>If it&#8217;s all good, you will see this message.</p>
<p> ![Alt text](./images/image (16).png "Github") </p>
<p>Now your code is pushed to your GitHub repository. Don&#8217;t believe me? Logon and check for yourself.</p>
<p> ![Alt text](./images/image (17).png "Github") </p>
