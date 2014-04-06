node-mysql-crud
===============

Simple Node.js app that can create, read, update and delete form a mysql database.


###Installation

#####Step 1
Create a mysql database  called nodejsmysql and add one table called nodej with two columns; fname and lname:

```sql
CREATE TABLE nodejs (fname VARCHAR(20), lname VARCHAR(20));
```


#####Step 2
Install express globally
```bash
npm install express -g
```
#####Step 3
Get this project
```bash
git clone git@github.com:AlexBezuska/node-mysql-crud.git
```
#####Step 4
Then use npm to get all dependancies
```bash 
cd node-mysql-crud
npm install
```
