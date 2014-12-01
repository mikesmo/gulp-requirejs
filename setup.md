*** Install Node and npm using nvm ***
http://www.wenincode.com/installing-node-jsnpm-without-sudo/

1. Install NVM
> curl https://raw.githubusercontent.com/creationix/nvm/v0.12.1/install.sh | bash

2. Restart terminal

3. List Node versions:
> nvm ls-remote

4. Install the latest
> nvm install 0.11.14

*** Install global npm packages ***

1. Install Yeoman
> npm install -g yo

2. Install Bower
> npm install -g bower

3. Install Gulp
> npm install gulp -g

4. Install Bower generator:
> npm install -g generator-gulp-webapp

*** Generate scaffold ***

1. Run yeoman
> yo gulp-webapp

2. Run gulp
> gulp

BUG Fix: Error: Cannot find module 'pako/lib/zlib/messages'
> npm install pako

3. Run gulp serve
> gulp serve

