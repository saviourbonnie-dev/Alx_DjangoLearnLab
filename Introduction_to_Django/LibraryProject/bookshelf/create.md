# Create Book

```python
from bookshelf.models import Book

book = Book.objects.create(
    title="The Alchemist",
    author="Paulo Coelho",
    publication_year=1988,
    genre="Fiction"
)
print(book)
