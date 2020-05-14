# heroku-node

[Heroku](https://www.heroku.com/): Cloud Application Platform
[Getting Started on Heroku with Node.js](https://devcenter.heroku.com/articles/getting-started-with-nodejs)

`$ git clone https://github.com/heroku/node-js-getting-started.git`
`$ cd node-js-getting-started`

`$ heroku login`  
`$ heroku create`
Creating app... done, ⬢ evening-scrubland-89876
https://evening-scrubland-89876.herokuapp.com/ | https://git.heroku.com/evening-scrubland-89876.git

heroku create `<project-name>`  

`$ git push heroku master`  
The application is now deployed. Ensure that at least one instance of the app is running:  
`$ heroku ps:scale web=1`  
`$ heroku open`  
https://evening-scrubland-89876.herokuapp.com/

`$heroku logs --tail`

[The Procfile](https://devcenter.heroku.com/articles/procfile)

JavaScript Template `ejs`

Run the app locally
`$ npm install`  
`$ heroku local web`  
http://localhost:5000/

## Deploy using Heroku Git

Install the Heroku CLI
`$ heroku login`

Create a new Git repository
`$ cd my-project/`  
`$ git init`  
`$ heroku git:remote -a vue-ele-server` 

`$ git add .`  
`$ git commit -am "make it better"`  
`$ git push heroku master`  

ex: https://vue-ele-server.herokuapp.com/api/seller

## Access-Control-Allow-Origin

Access to XMLHttpRequest at 'https://vue-ele-server.herokuapp.com/api/seller' from origin 'https://jacobhsu.github.io' has been blocked by CORS policy: No 'Access-Control-Allow-Origin' header is present on the requested resource.  

npm `cors`  

## references

npm [cool-ascii-faces](https://www.npmjs.com/package/cool-ascii-faces)
npm pg [node-postgres](https://www.npmjs.com/package/pg)