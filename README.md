
# Anifyy

The project is currently stopped because we have lost motivation. When we are ready to continue programming the project again, new updates will come. Basically, this is the first stable version.

Welcome to Anifyy! Here you can not only discover and rate exciting 
anime, but also immerse yourself in lively discussions with other fans. 
Immerse yourself in the fascinating world of animation, share your 
passion and find out important information about your favorite works.


## API Reference

```http
  GET api.Anifyy/animes
```

## Authors

- [@Oglis22](https://oglis22.github.io)
- [@lizhxro](https://github.com/lizhxro)


## Contributing

Developers are always welcome

Contact us <a href="">Here</a>

## Demo

https://www.anifyy.com/


## Documentation

[Documentation](https://documentation.anifyy.com)




## Installation

Install the project with npm

Deploay the Website

```sh
$ git clone https://github.com/Anifyy-com/Anifyy # or clone your own fork
$ cd Anifyy
$ npm install
$ npm start
```

## Usage/Examples

Set Mysql Connection mysql.json

```json
{
    "host": "localhost",
    "user": "root",
    "password": "",
    "database": ""
  }
```

sql commands


```json
{
CREATE TABLE users (
  id INT PRIMARY KEY AUTO_INCREMENT,
  username VARCHAR(255) NOT NULL,
  email VARCHAR(255) NOT NULL,
  passwordHash VARCHAR(255) NOT NULL,
  role VARCHAR(255) DEFAULT 'user'
);
CREATE TABLE ratings (
  rating_id INT AUTO_INCREMENT PRIMARY KEY,
  anime_id INT NOT NULL,
  user_id INT NOT NULL,
  username VARCHAR(255) NOT NULL,
  points INT NOT NULL,
  comment TEXT
);
CREATE TABLE animes (
  id INT PRIMARY KEY AUTO_INCREMENT,
  name VARCHAR(255) NOT NULL,
  keywords VARCHAR(255) NOT NULL,
  image VARCHAR(2550) NOT NULL,
  description VARCHAR(255) NOT NULL
);

  }
```


## Tech Stack

**Backend:** NodeJS, Express, Mysql

**Frontend:** EJS

**CSS Libarys:** Bootstrap, Material Design Lite

**JS Libarys:** Chart JS, JQuery

**NoeJS Modules:** 
    "bcrypt": "^5.1.1",
    "bootstrap": "^5.3.2",
    "ejs": "^3.1.9",
    "express": "^4.16.3",
    "express-session": "^1.17.3",
    "multer": "^1.4.5-lts.1",
    "mysql2": "^3.6.3",
    "request": "^2.85.0",
    "tape": "^4.9.0"

<br>
<br>

![Screenshot 2023-11-22 223712](https://github.com/oglis22/Anifyy/assets/119761510/7674c0e5-09d6-4a2d-a161-25a8bf85785d)



![ab67616d0000b2732f9084bc84f00ca01266460d](https://github.com/oglis22/Anifyy/assets/119761510/718eb526-58f6-450e-8d97-a356ed3dc9d2)



