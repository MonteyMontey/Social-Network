# Social-Network


## Features
- Registration & login
- Writing posts
- Seeing posts from other users
- Searching for users via search box
- Visiting profile pages of all users
- Sending friend requests to other users
- Receiving friend request notifications and the option to accept or decline it


## Instructions to run it locally

1. Install and run [MongoDB](https://www.mongodb.com/). Detailed installation instructions for all operating systems can be found [here](https://docs.mongodb.com/manual/administration/install-community/).
1. Install [Neo4j](https://neo4j.com/download/). Then create a graph database and run it. You also need to change the default password. Instructions can be found [here](https://neo4j.com/developer/neo4j-desktop/).
1. Clone this repository and cd into it.
1. Type `git submodule init` and `git submodule update` to fetch the submodules.
1. Now cd into the folder `social-net-back/`, open the `.env` file and insert your Neo4j database password. All other values should be fine, assuming you didn't change the defaults.
1. Then type `npm install` and then `npm start`.
1. Now cd into the other folder `social-net-front/` and type `npm install` and then `npm start` as well.
1. The social network should now be running at `localhost://3000`.

*tested with npm v6.12.1, MongoDB v4.2.1 and Neo4j v3.5.12*


## Live Demo

~~If you don't want to run it locally feel free to check out the [live demo](http://35.207.106.33:3000/).~~
