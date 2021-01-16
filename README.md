# Node JS Authentications

## About repository-
These are code snippets of different authentication techniques in Node JS such as salting, hashing, encrypting using various packages from `npm`. Some of the packages used include:
- Bycrypt
- md5
- mongoose-encryption
- passport
- passport-local-mongoose
and more...

**Different techniques can be found on the different branches in the repository.** 

## Environment Setup-

* Drop a :star: on the GitHub repository.
<br/>

* Download and install a code/ text editor.
    - Recommended-
        - [Download VS Code](https://code.visualstudio.com/download)
        - [Download Atom](https://atom.io/)
<br/>

* Download [Node Js and npm(Node package manager)](https://nodejs.org/en/) (when you download Node, npm also gets installed by default)
<br/>

* Mongo DB community editition is free and a great software in order to work with MongoDB applications. [Download Mongo DB community editition](https://docs.mongodb.com/manual/administration/install-community/)
<br/>

* Robo 3T is a desktop graphical user interface (GUI) for Mongo DB. It can help to skip running all the Mongo DB commands manually every time we want to access the data. [Download Robo 3T](https://robomongo.org/download) **(optional)**
<br/>

* Clone the repository by running command
```
git clone https://github.com/Pranav016/Node-Authentications.git
```
in your git bash.
<br/>

* Run command `cd Node-Authentications`.
<br/>

* Run this command to install all dependencies for the project.
```
npm install
```
<br/>

* Run this command on your terminal/ bash to start the Mongo server on port 27017(default).
```
mongod
```
<br/>

* Run this command to start the project on local host 3000.
```
npm start
```
<br/>

* Open link to view the website in your browser window if it doesn't open automatically.
```
http://localhost:3000/
```
<br/>

* Now you are all set to use this project.

#### Some useful Mongo DB commands if you are using the terminal instead of the GUI-
```
show dbs
use db <db name>
show collections
<db name> .find()
```
