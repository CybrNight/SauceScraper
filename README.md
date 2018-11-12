# SauceScraper

This is a collection of media scrapers for various websites.

These scrapers were intiallty written for my Discord bot, but I have uploaded them separatley here

# Usage
These files cannot be run on their own without some modification. They are designed to be a backend for other usage.

Import this package into your project and use the designated functions for each as described below.
Make sure to rename downloaded folder to fit your liking

# Code Examples
Gelbooru
```python
  from saucescraper import *

  gb = Gelbooru()

  # Use '_' between words for multiwords search phrases
  # Any spaces are converted to '+' for adding search tags
  keywords = input("Enter search term")

  video = gb.image_search(keywords)
  print(video)
```

HentaiHaven
  ```python
    from saucescaper import *

    hh = HentaiHaven()

    # Category types are seprated by spaces. Multiwords categories
    # Use '-' between words
    keywords = input("Enter categories")

    video = hh.category_search(keywords)
    print(video)
  ```

PornHub
  ```python
    from saucescaper import *

    ph = PornHub()

    # Just feed it a search string
    keywords = input("Enter search term")

    video = ph.video_search(keywords)
    print(video)
  ```

Rule 34
  ```python
    from saucescaper import *

    r34 = Rule34()

    # Category types are seprated by spaces. Multiwords categories
    # Use '-' between words
    keywords = input("Enter search term")

    video = r34.category_search(keywords)
    print(video)
  ```
