Configuration management

Puppet is a tool that helps you manage and automate the configuration of servers. When you use Puppet, you define the desired state of the systems in your infrastructure that you want to manage.

Obviously writing Puppet code for your infrastructure requires an investment of time and energy, but in the long term, it is for sure a must-have.

Project Requirements
All your files will be interpreted on Ubuntu 20.04 LTS
All your files should end with a new line
A README.md file at the root of the folder of the project is mandatory
Your Puppet manifests must pass puppet-lint version 2.1.1 without any errors
Your Puppet manifests must run without error
Your Puppet manifests first line must be a comment explaining what the Puppet manifest is about
Your Puppet manifests files must end with the extension .pp
Installing puppet and puppet-lint on ubuntu
A video says it all
Watch the video below to get a full grasp about tackling the project

Click the play video to watch video Play video

Commands on Terminal
$ apt-get update && upgrade -y

$ sudo apt-get install -y ruby=1:2.7+1 --allow-downgrades

$ sudo apt-get install -y ruby-augeas

$ sudo apt-get install -y ruby-shadow

$ sudo apt-get install -y puppet

#installs puppet linter
$ gem install puppet-lint
Follow the above instructions to install puppet and puppet-linter then watch the video to enable you understand how to get started with the task
