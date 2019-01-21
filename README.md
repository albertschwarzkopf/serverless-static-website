For deploying static websites with the serverless framework do the following:

<ol>
<li>If not installed, then install serverless framework: </li>
<code>npm install -g serverless</code>

<li>Create the service. The Github-repo has to be public!:</li> 
<code>serverless create -u https://github.com/albertschwarzkopf/serverless-static-website -n serverless-static-website-yourname</code>
   
<li>Install the S3 sync plugin:</li>
<code>serverless plugin install -n serverless-s3-sync</code>
