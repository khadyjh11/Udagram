1.GitHub
the developer push the code to the GitHub repository the link with CircleCI.

2.CircleCI
CircleCI reads the .circleci/config.yml file . and the service have to do the 2 job (serve and frontend) to run by CircleCI.

On the frontend it runs the script in package.json and then uses the AWS CLI to access S3
And in the server it runs the build script. And export all variables from CircleCI to an .env file, and then upload the archive to S3.
