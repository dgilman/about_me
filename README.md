# David Gilman's personal projects and interests
## Software projects

### [Pro-Football-History.com](https://pro-football-history.com)
* Co-founder and full stack developer.
* Implemented the entire website. Used the Flask web framework, PostgreSQL database, lxml XML/HTML parser and GraphViz technologies.
* Implemented a novel content generation system that gives SEO-friendly, textual content to all pages.
* Implemented internal SEO best practices over the entire website and designed an internal SEO style guide.
* Implemented a spreadsheet-oriented data collection and review system built on a homemade application framework on top of Python's asyncio library. Wrote asyncio wrappers for the Google Spreadsheet API, PostgreSQL and internal REST APIs.

### [gspread-asyncio](https://pypi.org/project/gspread-asyncio/)
* Wrote a Python asyncio wrapper library around the gspread Google Spreadsheet API library.
* In addition to wrapping the existing API wrote lots of useful logic around managing credentials, rate throttling and error handling and retries.
* [Documented everything](https://gspread-asyncio.readthedocs.io/en/latest/).
* Published the package to PyPI and set up continuous integration and deployment with Travis CI.

### [pooptracker](https://poop.gilslotd.com/?city=omaha)
* Click anywhere on the map to see where your poop goes (the downstream flow of sewers from your location)!
* Scraped the city of Omaha's sanitary sewer data into a PostGIS database and built a Flask web app around it.
* Coming to a city near you soon! If your city has public sewer data let me know and I'll add it.

### Inger
* Link not available - ask for details!
* Written in Python with the Flask web framework, SQLite3 database and Leaflet.js mapping library.
* Project included a web scraping component, a data processing and statistical aggregation component and a growing, gigabyte+ SQLite database.
* Several interesting and educational experiences with performance tuning.

### [CLT Pet Watch](https://github.com/dgilman/petwatch)
* Implemented a web scraper for Charlotte-area animal shelters that tweets the newest pets in shelters. Used the Python, lxml and SQLite3 technologies.

### [berimbau](https://github.com/dgilman/berimbau)
* File system browser written in the Flask web framework. Has some neat features around bandwidth usage measurement.

### [echobot](https://github.com/dgilman/echobot)
* Python asyncio application that echoes group chat conversations between chat networks. 

### [Charlotte Python Meetup group](https://www.meetup.com/python-charlotte/)
* Organizer for the monthly, in-person Python meetup group in Charlotte, NC

### Other websites

* [Personal blog - Gil's LotD!](https://gilslotd.com/blog)
* [Academic Decathlon Scores and Information Center](https://acadecscores.gilslotd.com/wiki/Main_Page) - webmaster since its inception in 2007

## Packaging work
#### [MacPorts](https://www.macports.org/)
* Contributor and package maintainer to the MacPorts package manager.
#### [netatalk-debian](https://github.com/dgilman/netatalk-debian)
* Got the Debian packaging building and publishing to GitHub via travis.ci.
#### [aacgain](https://github.com/dgilman/aacgain)
* Resurrected the build, integrated patches got everything under version control.

## Miscellaneous work
* Moved some [number crunching](https://github.com/dgilman/pandas_stats) over to the Python Pandas library.
* Author of the Wikipedia articles on the [Ridgeway gold mine](https://en.wikipedia.org/wiki/Ridgeway_Mine) and [Runza sandwich](https://en.wikipedia.org/wiki/Runza)
