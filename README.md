express-nunjucks
================

Sample Node Express + Nunjucks app

[Express](http://expressjs.com) by default comes with the Jade templating engine. This app replaces Jade with [Nunjucks] (http://mozilla.github.io/nunjucks/).

Installation instructions (for RHEL/CentOS):

Install Node + Express: 

`curl -sL https://rpm.nodesource.com/setup | bash -`

`yum install -y nodejs`

`npm install -g express-generator`

Install git: 

`yum install -y git`

Clone this repository (will automatically create a subfolder called "express-nunjucks": 

`git clone https://github.com/ababra/express-nunjucks.git`

Install required dependencies (do this inside of the express-nunjucks folder): 

`npm install`

To launch the app: 

`DEBUG=express-nunjucks PORT=3000 ./bin/www`

Open a browser and navigate to http://hostname-or-IP:3000
