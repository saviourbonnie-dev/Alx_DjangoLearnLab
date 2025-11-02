# Update Book

```python
from bookshelf.models import Book

book = Book.objects.get(id=1)
book.title = "The Alchemist (Updated)"
book.save()
