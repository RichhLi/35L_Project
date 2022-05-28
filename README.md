# 35L_Project

**Group Members**
* Ryan Jackson
* Riley Bruins
* Dharma Shah
* Richard Li
* Hayden D'Souza


<h1>Running Locally</h1>

<h3>This assumes NPM is already installed</h3>
<p>To clone the repository locally, run</p>

```
git clone https://github.com/ryanjackson10/35L_Project.git
```
and switch into the project's root directory by running
```
cd 35L_Project
```
to install the frontend dependencies, change into the client directory and npm install
```
cd client
npm install
```

switch back to the root and do the same on the server directory to install the backend dependencies
```
cd .. // switches back to the root
cd server
npm install
```
we now must create an environment file to keep track of our environment variables, including the database connection string. 

While still in the server directory, run
```
npm start
```
this should log a message that Node is listening on Port 8000

now, in a new terminal window, switch back to the project root directory, then to the client, and run the same command
```
cd ..
cd client // or however you can get to the client directory
npm start
```
the project should now be running on localhost:3000! (beware of UCLA-WEB, our server doesn't respond properly on UCLA-WEB)
