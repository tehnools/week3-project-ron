#TEAM RON#
## Members ##
Anisha
Andre
Davidb
Jared
Joanna
Noel

## Links ##

### Trello Board ###
https://trello.com/invite/b/kuGHAF6i/06ec4ef1b367a4c7d082acdd085e34f7/spell-tutor-app

### Font ###
https://www.fontspace.com/fontomen/harry-potter

### Multer ###
https://www.npmjs.com/package/multer

## PLAN ##

* Init week3-project-ron
* Init boilerplate
`
git clone https://github.com/dev-academy-challenges/boilerplate-knex
mv boilerplate-knex week3-project-ron
cd  week3-project-ron
npm install
git remote set-url origin https://github.com/matai-2019/week3-project-ron
`
* Create new branch dev
* Install Additional Packages (should have)
    * DEV
        * nodemon
        * jest
        * supertest

    * RUNNING
        * express
        * express-handlebars
        * knex
        * sqlite3
    
    * OPTIONAL
        * multer (for image upload) 

* Plan User Stories


### Scripts ###
`
"scripts": {
    "knex": "knex",
    "dev": "nodemon index",
    "start": "node index",
    "test": "jest --watchAll --verbose",
    "rollback" : "npx knex migrate:rollback",
    "latest" : "npx knex migrate:latest",
    "seedrun" : "npx knex seed:run"
  },
`
# : exclaimation : Message Remember to git fetch then git pull before pull requeset to DEV branch#
After fetch and pull do a pull request to dev branch
`
git fetch
git pull
`
