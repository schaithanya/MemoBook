<h3>Idea!!</h3>

<p>Build an app to maintain memories in private include pics, videos with comments.<br>
Should be easy to create posts and also easy to view and filter.</p>

<h3>Programming Languages/Tools</h3>
Angular js <br>
WebApi<br>
Visual Studio Code<br>
Visual Studio <br>

<h3>Installation</h3>

<h4>Angular js </h4>

Install Node js from the following links : https://nodejs.org/en/download/

Follow the angular CLI installation from the following link : https://angular.io/guide/quickstart --> Do not use node js command prompt

Some installation issues :<br>
Issue 1 : Some common error ssl-error-cert-untrusted-while-using-npm-command<br>
Solution: bypass https using below commands<br>
npm config set strict-ssl false<br>
or <br>
set the registry from https to http like below : npm config set registry="http://registry.npmjs.org/"<br>

Issue 2 : Unable to verify the first certificate
Solution: by pass the restriction by setting the environment variable 
From the terminal type the below command:

set  NODE_TLS_REJECT_UNAUTHORIZED=0
