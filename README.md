# Node.js Rest APIs with Express & MySQL example


## Project setup
```
npm install
```

### Run
```
node server.js
```

### Set you Database configurations in this file

/app/db.config.js


### Create DB by running this command in MYSQL

---
CREATE TABLE IF NOT EXISTS `tutorials` (
  id int(11) NOT NULL PRIMARY KEY AUTO_INCREMENT,
  title varchar(255) NOT NULL,
  description varchar(255),
  published BOOLEAN DEFAULT false
) ENGINE=InnoDB DEFAULT CHARSET=utf8;

---


### Here is the link of postman collection
https://github.com/haxandev/Node-JS-CRUD---Express-MYSQL/blob/master/NodeJs%20CRUD.postman_collection.json