# SauceScraper

This is a collection of media scrapers for various websites.

These scrapers were intiallty written for my Discord bot, but I have uploaded them separatley here

# Usage
These files cannot be run on their own without some modification. They are designed to be a backend for other usage.

Import this package into your project and use the designated functions for each as described below

Gelbooru 
  - Uses an image search with image_search(keywords)
  - Spaces between words will be replaced with '+'
  - To do multi word searches use '_' between words
  
HentaiHaven 
  - Uses both a category search with category_search(categories) and random search with random()
  - Spaces marks a separation between two different categories use '-' for multi word categories
  
PornHub
  - Uses a video search with video_search(keywords)
  - Spaces are allowed
  
Rule34
  - Same rules as Gelbooru
