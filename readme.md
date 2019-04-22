# Simpson Says REST API
## For Live Server Usage
### [Documentation on Usage of Rest API](http://simpsonsaysapidocs.surge.sh)
## **For Running Locally**

All dependencies have been linked through packages attached
1. To link and install all dependencies
    * in root run `yarn install`
    
1. Add and link .env file
    * add `.env` file to root directory
    * add required enviorment variables:
        * `DB_ENV=development` to indicate Local DB used for development
        * `PORT=<port on local machine>` to indicate which port will be used to host the server on the local machine
        * `JWT_SECRET=<LONG string to be used for salting hashed passwords>` to create a unique secret string that is used to salt hashed passwords for security, and data integrity on token signatures

1. Fire up server
    * Migrate DB Tables:
        * run `yarn knex migrate:latest`
    * Seed Data to DB tables:
        * run `yarn knex seed:run`
    * Start server:
        * run `yarn server`
            * This by default will initiate the server to run locally on the hosted port using the server listener, and the development DataBase as Well as default seeded data.




# Get Help Guidelines
1. **RESEARCH**
    * You are not too sure whats going on and are mildly confused
        * Check the guided demo from lecture
        * Check other projects
        * Check the TK everything you need is in there
        * Ask the all mighty Stack-Overflow, MDN, or W3
        * Check the documentation online for whatever the issue happens to be.
        * Check other online resources at your finger tips
1. **Get Up and Away From the Code for 5-10 mins**
    * You have been stuck for 20 mins and am getting no where despite all the research.
1. **Ask the #web20_help** 
    * You have returned from your break 15 mins has gone by and You am still lost.
    * Other students may have had the same issue and resolved it, that is a good place to start.
    * Ask the channel 
        * Your amazing peers who may have the help You need are monitoring the help channel
        * PM's are on duty monitoring the help channel during all Lambda Hours (8:00am - 5:00pm PST *_excluding lunch 11:00am -                 12:00pm_*) and so are the rest of your amazing peers who may have the help You need.
1. **Ask your PM**
    * You have asked the help channel and just couldn't find the solution even with other students help
    * @ me `@OmarS` in #web20_omar with your question.
        * I will be notified right away and hopefully be able to help if one of your peers hasn't already.
1. **Bring in Our Section Lead**
    * You and I are still baffled by this anomaly of a bug
        * I will reach out to our SL about possibly getting the instructors eyes to squash that bug.
    