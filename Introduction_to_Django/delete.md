```python
# Open the Django shell
python manage.py shell

# Import the model
from bookshelf.models import Book

# Retrieve the specific book (assuming title is "Nineteen Eighty-Four")
book = Book.objects.get(title="Nineteen Eighty-Four")

# Delete the book
book.delete()
