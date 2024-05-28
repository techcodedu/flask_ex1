# Flask Project Exercise

## Objective
Create a Flask web application with a consistent layout by extending a base template. You will create multiple pages: Home, Class, and DTR (Daily Time Record).

## Instructions

### Step 1: Set Up Your Project
1. Create a new project directory for your Flask application.
2. Within your project directory, set up a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install Flask using pip:
   ```sh
   pip install Flask
   ```

### Step 2: Create the Flask Application
1. Initialize your Flask application.
2. Create a file to define the routes for your application.
3. Ensure you have an `__init__.py` file to initialize the application and import routes.

### Step 3: Create the Templates
1. Create a `base.html` template that includes a common layout for your pages (e.g., navigation bar).
2. Create `home.html`, `class.html`, and `dtr.html` templates that extend `base.html`.

### Step 4: Define Routes for Each Page
1. Create routes for the Home, Class, and DTR pages in your routes file.
2. Each route should render the corresponding template.

### Step 5: Include Static Files
1. Create a `static` directory to hold your CSS and image files.
2. Reference the CSS file in your `base.html` to apply styles across all pages.

### Step 6: Run Your Application
1. Create a script to run your Flask application.
2. Start the Flask development server and open your web browser to view the application.

### Step 7: Verify the Application
1. Ensure that navigating to each route displays the correct content with a consistent layout.
2. Verify that the CSS styles are applied correctly across all pages.

By following these steps, you will create a Flask web application with multiple pages and a consistent layout using template inheritance. This exercise will help you understand the basics of Flask and how to structure a web application project.
```
