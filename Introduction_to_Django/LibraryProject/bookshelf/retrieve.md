# Retrieve Book

```python
from bookshelf.models import Book

# Retrieve and display all Book records
books = Book.objects.all()
for book in books:
    print(book.title, book.author, book.publication_year)

# Expected Output:
# 1984 George Orwell 1949
