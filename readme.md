## How to Run Backend

### Instructions

1. **Install the Requirements:**

   ```
   pip install -r requirements.txt
   ```

2. **Database Migrations:**

   ```
   python manage.py makemigrations
   python manage.py migrate
   ```

3. **Run the Application:**

   ```
   python manage.py runserver
   ```

4. **Create Superuser for Admin Account:**

   ```
   python manage.py createsuperuser
   ```

   Follow the prompts to set a username, email, and password for the superuser account.

---

## Frontend for React JS

To run the React JS frontend, follow these steps:

### Prerequisites

- Node.js installed on your machine. You can download it [here](https://nodejs.org/).

### Instructions

1. **Navigate to the Frontend Directory:**

   ```
   cd frontend
   ```

2. **Install Dependencies:**

   ```
   npm install
   ```

3. **Run the React Application:**

   ```
   npm start
   ```

   This will start the development server and open the React application in your default web browser.

### Build for Production

If you're ready to deploy your React application, you can build the production-ready version using the following command:

```
npm run build
```

This will create an optimized build in the `build` directory, which you can then deploy to your preferred hosting platform.

### Additional Frontend Configuration

- **Environment Variables:**

  - Modify the `.env` file to configure any necessary environment variables such as API endpoints, authentication keys, etc.

- **Customization:**

  - Customize the appearance and behavior of your React application by editing components, styles, and configurations in the `src` directory.

- **Testing:**

  - Run tests using:
    ```
    npm test
    ```

- **Linting:**
  - Ensure code consistency and style by running:
    ```
    npm run lint
    ```

---
