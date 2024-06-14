# Point of Sale
A Point of Sale application for restaurant workers who want to receive orders, take seats, check bills, customize menus, see a wait list and sales report.

# Features
- Users can view the floor plan of the restaurant
- Users can view the table status of each table (paid, open, billed)
- Users can view a current check for a table
- Users can mark a current check for a table as paid
- Users can create, update, remove, edit guests on a wait list
- Users can see menu items avaliable to order
- Users can place an order to a table and create a check simultaneously
- Users can view a sales report
- Users can update/remove new menu items to the menu
- Users can change the table status of a table
- Users can view which orders for each table have been sent or not

# Technologies Used
- React.js
- React Router
- Material UI
- Node.js
- Express
- PostgreSQL
- Multer
- HTML5
- CSS3
- AWS EC2

# Getting Started
1. Clone the repository and navigate to the directory

git clone https://github.com/ArfaDevelopers/point-of-sale-React-Nodejs

cd point-of-sale

2. Install all dependencies

npm install

3. Make a .env file and customize its settings

PORT=3001

DEV_SERVER_PORT=3000

DATABASE_URL=postgres://{user}:{password}@localhost/{database-name}

SESSION_SECRET=secret

4. Start PostgreSQL and Import existing database

sudo service postgresql start

createdb {database-name}

npm run db:import

5. Compile project

npm run dev

6. Access application by entering https://localhost:3000 in the browser.
