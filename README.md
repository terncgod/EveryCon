
Description
=======
It is possible to visually connect anything to anything or anyone to anyone. This project is intended to create a simple interface for that.

The connection core could be a simple point, continuing with two, three..etc. With four there is possibility for 3D already.

Pre-Alpha version, 0.2


Specs v0.2
=======

Target specifications for client side code
  - HTML5
  - CSS
  - Canvas or SVG (avoid if possible)
  - JavaScript (avoid if possible)

Target specifications for server side code / db
  - Python
  - Flask
  - sqlite3


Notes and to do
=======
  1. Create database schema and python code for it:  id, title, content, connected
      id is uniq and identifies entries
      title can be text, max 128 characters
      content can be text (yet)
      connected is a list of topics connected, with distance, eg. running -> "sport", 1, "health", 2, "running shoes", 3
  2. Split the database code into the Flask calls
  3. Make it visual with SVGs and integrate the calls through SVGs
  4. Make sure all input is limited to minimum needed and recheck everything.

