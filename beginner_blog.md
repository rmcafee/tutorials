# Beginner Blog

## Installation

1. Setup account at <https://codeanywhere.com>

2. Run the following commands for ruby environment:

	```
	sudo apt-get update
	sudo apt-get install git-core curl zlib1g-dev build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev libcurl4-openssl-dev python-software-properties libffi-dev nodejs -y
	```
3. Now run the following commands to install Ruby using RVM ( Ruby Version Manager ) :

	```
	sudo apt-get install libgdbm-dev libncurses5-dev automake libtool bison libffi-dev -y
	
	gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
	
	curl -sSL https://get.rvm.io | bash -s stable
	
	source ~/.rvm/scripts/rvm
	
	rvm install 2.4.0
	
	rvm use 2.4.0 --default
	
	ruby -v
	```
	
4. Now that we have ruby installed let's install Rails and supporting gems!

	```
	gem install bundler

	curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash - 	
	sudo apt-get install -y nodejs

	gem install rails
	```
	
## Create Blog Application

	rails new blog

This is what the directory structure should look like:

![Directory Structure](http://rmcafee.tutorial.assets.s3.amazonaws.com/beginner_blog/00_directory_structure.png)

