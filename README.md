# README

This application goes along with the Deploy Rails API with React to Heroku Tutorial. Instructions on building this app are at:

https://www.techandstartup.com/tutorials/rails-react-heroku

This app conists of two parts:

1) The Ruby on Rails API-only back end application.

2) The React front end app, which is in the client directory.

To run this app locally first start the Rails server on port 3001: rails server -p 3001

Then run the Node server to start React: yarn --cwd client start

The app will launch on port 3000.

If you have the foreman gem installed you can run both servers with one command:

foreman start -f Procfile.dev
