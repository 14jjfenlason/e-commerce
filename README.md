# E-commerce

## Description
The E-commerce back end application is a command-line application that allows users to view, create, update and delete products from the database.

## Technologies Used
- Node.js
- PostgreSQL
- Sequelize
- Insomnia

## Installation
1. Create a .env file with `DB_NAME='ecommerce_db` and your associated username and password
2. Install dependencies: `npm i`
3. Seed the database by running `npm run seed`
4. Activate the schema.sql file: `psql -U postgres` enter your password, `\i db/schema.sql`
5. Set up the database: `node index`

## Usage
Open the associated url in Insomnia and go to the desired directory (base url: http://localhost:3001/)
Video submission of use:
https://drive.google.com/file/d/1NhSHO2Y1G8eHexWDGlN1JQgLmJZvGDlZ/view

## Database Setup
- Ensure PostgreSQL is installed on your system.
- Set up a PostgreSQL database with the required tables and seed data. You can use the provided SQL files to create the schema and seed the initial data.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
MIT License

## Credits
Node.js: https://nodejs.org/ 
Insomnia: https://insomnia.rest/
PG package: https://www.npmjs.com/package/pg
Sequelize: https://sequelize.org/
All codes used as reference are from projects and activities within The Coding Bootcamp at The University of Texas at Austin. All guidance led by The Coding Bootcamp at The University of Texas at Austin. Created by Joshua Fenlason.
