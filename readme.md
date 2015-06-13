#Deployment Plan

##Set up a server with digital ocean

1. Go to digital ocean select ubuntu 12.04 x64 server image.

2. Activate server and get prodServer live IP address.

##Sign into server with root and add user and give user sudo permission

1. Update and upgrade packages.

2. Install git to commit and push to live server

3. Install and set up Apache 2

##Set up a repository on server

1. Make repo directory

2. Make site directory

3. Change directory to site directory and initialize git --bare

4. Create post-receive file to set up git work tree

5. Give permissions for post-receive file

##Configure local development

1. Make project directory and site directory

2. Change directory to site directory

3. Initiallize git and add staging server and production Server

##Create website files

1. Create index.html file

2. Create css and image directories

3. Create css files

4. Add images

##Start adding to staging server 

1. git add -A

2. git commit -m 'message'

3. git push staging server master

4. git status

##Start adding to live production server

1. git push production server master

2. View live site



