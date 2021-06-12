# Deployment - Travel Caribbean

<a href="https://github.com/DeannaCarina/travelcaribbean/blob/master/README.md">Back to README.md</a>

## Contents
<ul>
    <li>
        <a href="#PC">Project Creation</a>
    </li>  
    <li>
        <a href="#PD">Project Deployment</a>
    </li>  
    <li>
        <a href="#LD">Local Deployment</a>
    </li> 
</ul>
<hr>
<h2 id="PC">Project Creation</h2>
This project was created on GitHub and Edited in GitPod by carrying out the following:
<ol>
    <li>A new repository was created using 'Code-Instutute-Org/gitpod-full-template'</li>
    <li>A meaningful name was given to my new repository and I selected 'Create Repository'</li>
    <li>I then opened the repository on GitHub and clicked the 'Gitpod' button to build the GitPod workspace which would allow me to build and edit the code used to make the <em>Travel Caribbean</em> Website</li>
    <li>Version control was used throughout the project using the following commands in the terminal using Bash
        <ul>
            <li>git add . <strong>OR</strong> git add "file name" - to stage the changes and get them ready for being committed to the local repo.</li> 
            <li>git commit -m "Description of the update" - to save the change and commit the change to the local repo</li>
            <li>git push - to push all committed shanges to the GitHub repo associated with the GitPod workspace</li>
            <li>commit --amend - I am prone to typing errors, this command came in very handy for changing the wording or spelling of the most recent commit</li>
            <li>git reset "commit hash" - I only used this a couple of times when I decided to take certain sections in a different directions e.g. resize all images to a certain size, commit and push, but then decide I want them to be bigger/smaller.</li>
        </ul>
    </li>
</ol>
<br>
<h2 id="PD">Project Deployment</h2>
This project was deployed via GitHub pages by carrying out the following:
<ol>
    <li>Log in to GitHub</li>
    <li>In the repository section, select the repo to be deployed</li>
    <li>In the menu at the top of the page select 'settings'</li>
    <li>Select 'pages' in the left hand side menu</li>
    <li>In the source section, the 'Master' branch is selected and the save button selected</li>
    <li>The web page is then assigned it's URL which will appear in the source section*</li>
</ol>
*It can take some time for the site to be deployed when the 'save' button is pressed and a URL created.
<br>
<h2 id="LD">Local Deployment</h2>

#### Cloning the repo with GitPod
<ol>
    <li>Log in to your GitHub account</li>
    <li>Navigate to the Repository <a href="https://github.com/DeannaCarina/travelcaribbean"><strong>HERE</strong></a></li>
    <li>Select the 'Code' button above the file list on the right had side</li>
    <li>Ensure HTTPS is selected and click the clipboard on the right of the URL to copy it</li>
    <li>Open a new workspace in GitPod</li>
    <li>In the bash terminal type 'git clone [copy url here from step 4]'</li>
    <li>Press enter - the IDE will clone and download the repo</li>
    <li>You can then type 'python3 -m http.server' to host the website locally</li>
</ol>