# Clone Repsoitory
git clone  https://github.com/hemaprabham/recipe.git

# Navigate to project directory
cd foodrecipe

# Install Dependencies
pip install -r requirements.txt
# Set up Database:
# Run migrations
python manage.py migrate

# (Optional) Create a superuser
python manage.py createsuperuser

# Run the development server
python manage.py runserver

This will start the Django development server, and you should be able to access the project in your web browser at http://127.0.0.1:8000/.Internet connection is mandatory for running the projects
