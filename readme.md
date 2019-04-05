# mern

# How to run
This is a project I'm working on with Mongo, Express, React, and Node.  
You can login and create a profile and head to the dashboard route only if authenticated.

# You will need config/keys.js
keys.js will consist of  
<code>
module.exports = {
  mongoURI: '',
  secretOrKey: 'secret'
};  
</code>    
mongoURI will look like -> 'mongodb://username:password@ds189233.mlab.com:41wqww89/name'

# How to run

git clone git@github.com:iAmNawa/mern.git  
cd mern  
npm i  
cd client  
npm i  
cd ..  
npm run dev  
