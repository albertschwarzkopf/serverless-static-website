For deploying static websites with the serverless framework do the following:

<ol>
<li>If not installed, then install serverless framework: </li>
<code>npm install -g serverless</code>

<li>Create the service. The Github-repo has to be public!:</li> 
<code>serverless create -u https://github.com/albertschwarzkopf/serverless-static-website -n serverless-static-website-yourname</code>

<li>Go in the new directory

<li>Install the S3 sync plugin:</li>
<code>serverless plugin install -n serverless-s3-sync</code>

<li>Put your static files and folders into the static directory
  
<li>Deploy your Stack:
  <code>serverless deploy -v</code>
