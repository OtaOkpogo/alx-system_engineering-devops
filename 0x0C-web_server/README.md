0x0C. Web server

Requirements General Allowed editors: vi, vim, emacs All your files will be interpreted on Ubuntu 16.04 LTS All your files should end with a new line A README.md file, at the root of the folder of the project, is mandatory All your Bash script files must be executable Your Bash script must pass Shellcheck (version 0.3.7) without any error The first line of all your Bash scripts should be exactly #!/usr/bin/env bash The second line of all your Bash scripts should be a comment explaining what is the script doing You can’t use systemctl for restarting a process

Tasks 0. Transfer a file to your server mandatory Write a Bash script that transfers a file from our client to a server:

Requirements:

Accepts 4 parameters The path to the file to be transferred The IP of the server we want to transfer the file to The username scp connects with The path to the SSH private key that scp uses Display Usage: 0-transfer_file PATH_TO_FILE IP USERNAME PATH_TO_SSH_KEY if less than 3 parameters passed scp must transfer the file to the user home directory ~/ Strict host key checking must be disabled when using scp

Readme:

-y on apt-get command Web servers are the piece of software generating and serving HTML pages, let’s install one!

Requirements:

Install nginx on your web-01 server Nginx should be listening on port 80 When querying Nginx at its root / with a GET request (requesting a page) using curl, it must return a page that contains the string Hello World! As an answer file, write a Bash script that configures a new Ubuntu machine to respect above requirements (this script will be run on the server itself) You can’t use systemctl for restarting nginx

Setup a domain name mandatory .TECH Domains is one of the top domain providers. They are known for the stability and quality of their DNS hosting solution. We partnered with .TECH Domains so that you can learn about DNS.
.TECH Domains worked with domain name registrars to give you access to a free domain name for a year. Please get the promo code in your tools space. Feel free to drop a thank you tweet for .TECH Domains.

Provide the domain name in your answer file.

Requirement:

provide the domain name only (example: foobar.tech), no subdomain (example: www.foobar.tech) configure your DNS records with an A entry so that your root domain points to your web-01 IP address Warning: the propagation of your records can take time (~1-2 hours) go to your profile and enter your domain in the Project website url field
