# Books

Books is a light web application to manage books and track ther state.  
It’s written in PHP, does not require a database and can be easily self hosted.


Version 2.0 is now available → [download the last version](https://github.com/Devenet/Books/releases) 🚀


Main features:  
- Simple & fast, intuitive & mobile first
- No database (data is saved in a file)
- Easy installation
- Search, best rated, readlist, and random book features
- Several optional metadata (publisher, publication year, page, note, review, genres, external information link, book cover)
- RSS feed for last books
- Export and import feature with JSON file
- Settings (title, author, robots, pagination)
- Custom themes supported


![Books](https://raw.github.com/Devenet/Books/master/Books.jpg)


Developed by Nicolas Devenet. Under MIT license.  
Code hosted on https://github.com/Devenet/Books.

Inspired by [Shaarli](https://github.com/sebsauvage/Shaarli).

---

## Migration from v1 to v2

Before migrating to v2:  

- If you want to keep your logs, you have to rename the file `/data/area-51.txt` into `/data/logs.txt`.  
  Otherwise, nothing to do.


After migrating to v2:

- You can delete the obsolete folder `/cache`.
