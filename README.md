# e-commerce-back-end

## Description

Back end database for an e-commerce site, MySQL database which utilizes sequelize (ORM) and node.js and started through express.js, links in the [Contributing](#Contributing) section.

### Link to repository:

https://github.com/ATXiceman512/e-commerce-back-end

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Contributing](#Contributing)

## Installation

Clone or download program files

Open integrated terminal or CMD in root directory and 
run: "npm init" to create package.json file
run: "npm install" to install required dependecies
create: '.env' *IF NOT CREATED* in the root directory and set the following:

DB_NAME='ecommerce_db'  
DB_USER= "your MySQL username"  
DB_PW= "your MySQL password" 

To create the database , you must run the following command in the integrated terminal or CMD(from the root directory)
mysql -u "your MySQL username" - p
when prompted for your password, use the one indicated in the .env file (i.e.- "your MySQL password")

Once the database has been created and you are connected, you should see 'mysql>', then run: source ./db/schema.sql

In order to seed the database, run: "npm run seed" *Make sure you are not still in the SQL command line, if so, tpye: 'exit' to get back to main terminal and try again*

## Usage

Once that has been completed, type: "npm start" to start the application

As there if no front-end use Insomnia or Postman to interact with the program

here are the basic GET endpoints:
http://localhost:3001/api/categories,
http://localhost:3001/api/products,
http://localhost:3001/api/tags

Video Tutorial: https://drive.google.com/file/d/1X4Xgp8LHSeSbETNix0Bk2SchHNNE6b_o/view

## License

MIT License

Copyright (c) [2021] [ATXiceman512]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Contributing

### Express
[Link to site](https://www.npmjs.com/package/express)

### MySQL2
[Link to site](https://www.npmjs.com/package/mysql2)

### dotenv
[Link to site](https://www.npmjs.com/package/dotenv)

### sequelize
[Link to site](https://www.npmjs.com/package/sequelize)

  ## Questions
  For more information, contact  
  * [ATXiceman512 on GitHub](https://github.com/ATXiceman512)  
  * [jbeard1989.jb@gmail.com](mailto:jbeard1989.jb@gmail.com)


