# KeystoneJS on Heroku

MONGO_URI: mongodb+srv://keystonejs:Tq6fRb5dxe@cluster0-szafh.azure.mongodb.net/test?retryWrites=true&w=majority

- [ ] [Deploy scenarious](https://github.com/keystonejs/keystone/issues/1257).

## Apps

yarn create keystone-app starter -> ropaolle-starter
yarn create keystone-app todo -> ropaolle-todo
yarn create keystone-app blank -> ropaolle-blank


heroku login
git init
heroku git:remote -a ropaolle-?
git add .
git commit -am "initial commit"
git push heroku master