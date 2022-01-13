# Data-Engineering-Internship

My application will start working automatically once the
container is spun up. my application will not start making
api requests until it has automatically connected to the database.

First, we’ll take a look at running a database in a container and how we use volumes and networking to persist our data and allow our application to talk with the database. Then we’ll pull everything together into a Compose file which allows us to setup and run a local development environment with one command. Finally, we’ll take a look at connecting a debugger to our application running inside a container.
