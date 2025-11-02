# 🔵 Retrieve Operation

from bookshelf.models import Book

# Retrieve the book with title "1984"
book = Book.objects.get(title="1984")

# Display all attributes
print(book.id, book.title, book.author, book.publication_year)
