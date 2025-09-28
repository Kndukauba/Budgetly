# Budgetly
Budgelty is a web application that helps users manage and track their finances, enabling them to make informed and responsible decisions. In a world where financial literacy is increasingly important for younger generations, Budgelty provides a modern tool to easily build wealth without the need to manually record anything. 

# Technologies Used:
The project leverages several key technologies:
  Python 3.x and Flask for backend logic
  PostgreSQL for database management
  HTML, CSS, and JavaScript for frontend design
  JSON for data communication

Additional libraries specified in requirements.txt

# Setup Instructions:
To run this project locally, follow these steps:

# Clone the repository:

git clone https://github.com/Kndukauba/Budgetly.git
cd Budgetly


# Create and activate a virtual environment:

python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate


# Install all dependencies:

pip install -r requirements.txt


Configure environment variables (if any) by creating a .env file in the project root. Example:

DATABASE_URL=postgresql://username:password@localhost/dbname
SECRET_KEY=your_secret_key


# Run the app:

python app.py


Open your web browser and navigate to http://127.0.0.1:5000 to access the application.

# Usage Instructions:
Once the app is running, users can:

Add financial accounts and record transactions

View summaries of income, expenses, and overall budget

Track trends to make informed financial decisions

# Project Structure:
The repository is organized for clarity:
  app.py – main Flask application
  requirements.txt – lists all project dependencies
  Procfile – necessary for deployment on Render
  static/ – contains CSS, JavaScript, and image files
  templates/ – contains HTML templates for the frontend
  .gitignore – ignores unnecessary files like __pycache__

# Acknowledgements:
Special thanks to the hackathon organizers and all the open-source libraries used in this project.
