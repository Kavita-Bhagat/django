# django

# Create and activate virtual environment 
py -m venv myproject
.\myproject\Scripts\activate

# Install Python dependencies
pip install -r requirements.txt 
# Create SQLite databse, run migrations 
django manage.py migrate 

# Run Django  server 
django manage.py runserver
