# Social-Network

## Instructions to run it locally

1. Install and run [MongoDB](https://www.mongodb.com/). Detailed installation instructions for all operating systems can be found [here](https://docs.mongodb.com/manual/administration/install-community/).
1. Install [Neo4j](https://neo4j.com/download/). Then create a graph database and run it. You also need to change the default password. Instructions can be found [here](https://neo4j.com/developer/neo4j-desktop/).
1. Clone this repository and cd into it.
1. Type `git submodule init` and `git submodule update` to fetch the submodules.
1. Now cd into the folder `social-net-back/`, open the `.env` file and insert your Neo4j database password. All other values should be fine, assuming you didn't change the defaults.
1. Then type `npm install` and then `npm start`.
1. Now cd into the other folder `social-net-front/` and type `npm install` and then `npm start` as well.
1. The social network should now be running at `localhost://3000`.
