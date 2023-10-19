# React-Node Recipe App 🍲

Welcome to the React-Node Recipe App! This application allows users to view, add, and manage their favorite recipes. It's built using React for the frontend and Node.js with Prisma for the backend.

## Getting Started 🚀

### Prerequisites:

- Node.js and npm installed on your machine.
- An account on [ElephantSQL](https://www.elephantsql.com/) for the database.
- A [Spoonacular API key](https://spoonacular.com/food-api) for the recipe API

### Setting Up:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/chrisblakely01/react-node-recipe-app.git
   cd react-node-recipe-app
   ```

2. **Setting up the Backend**:

   - Navigate to the backend directory:
     ```bash
     cd backend
     ```

   - Install the necessary packages:
     ```bash
     npm install
     ```

   - **Spoonacular API**:
     - Add the api key to the API_KEY variable in the .env file   

   - **ElephantSQL Setup**:
     - Create a new database instance on ElephantSQL.
     - Copy the connection string provided by ElephantSQL.

   - **Prisma Setup**:
     - Replace the `DATABASE_URL` in the `.env` file with your ElephantSQL connection string.
     - Initialize Prisma and generate the Prisma client:
       ```bash
       npx prisma init
       npx prisma generate
       ```

   - Start the backend server:
     ```bash
     npm start
     ```

3. **Setting up the Frontend**:

   - Navigate to the frontend directory:
     ```bash
     cd frontend
     ```

   - Install the necessary packages:
     ```bash
     npm install
     ```

   - Start the frontend development server:
     ```bash
     npm run dev
     ```
