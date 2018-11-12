# SauceScraper

This is a collection of media scrapers for various websites.

These scrapers were intiallty written for my Discord bot, but I have uploaded them separatley here

#Requirements
Python 3.6.6
It should work on future versions of Python and future versions of the dependencies.

```
pip install requirements.txt
```

# Usage
The scrapers are not designed to run on their own, but rather are an addon package for your project
Import this package into your project and use the designated functions for each as described below.

# Code Examples
Note:"saucescraper" is whatever you named your extracted folder
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
