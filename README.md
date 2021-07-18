# David Gilman's personal projects and interests
## Software projects

### [Pro-Football-History.com](https://pro-football-history.com)
* Co-founder and full stack developer.
* Implemented the entire website. Used the Flask web framework, PostgreSQL database, lxml XML/HTML parser and GraphViz technologies.
* Implemented a novel content generation system that gives SEO-friendly, textual content to all pages.
* Implemented internal SEO best practices over the entire website and designed an internal SEO style guide.
* Implemented a spreadsheet-oriented data collection and review system built on a homemade application framework on top of Python's asyncio library. Wrote asyncio wrappers for the [Google Spreadsheet API](https://github.com/dgilman/gspread_asyncio), PostgreSQL and internal REST APIs.
* Rewrote the entire front end on the [AMP Framework](https://amp.dev/) to optimize mobile performance, page size and search ranking.

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

### [ngxinger](https://github.com/dgilman/ngxinger/)
* A new Flask backend and Angular 9 frontend built over the old Inger database.
* Continuous deployment set up with GitHub actions to run frontend and backend tests and lints, create a [PEX](https://github.com/pantsbuild/pex) image and a Docker container, push the container to Google Cloud and deploy to a Google Cloud Compute Engine instances on every push to master.
* Solid test coverage on the Flask backend.

### [CLT Pet Watch](https://github.com/dgilman/petwatch)
* Implemented a web scraper for Charlotte-area animal shelters that tweets the newest pets in shelters. Used the Python, lxml and SQLite3 technologies.

### [xattr-compat](https://github.com/dgilman/xattr-compat)
* Python library providing a cross-platform API for file extended attributes. Works on MacOS X, Linux and FreeBSD.

### [SCOTUSwars](https://scotuswars.gilslotd.com/)
* SCOTUSwars is an interactive exploration of Supreme Court cases states have filed against one another.
* Implemented in Python and plain JavaScript.

### [py-wikimarkup](https://github.com/dgilman/py-wikimarkup)
* Co-maintainer. Did ongoing maintenance on the library including the Python 2 to 3 transition.

### [berimbau](https://github.com/dgilman/berimbau)
* File system browser written in the Flask web framework. Has some neat features around bandwidth usage measurement.

### [echobot](https://github.com/dgilman/echobot)
* Python asyncio application that echoes group chat conversations between chat networks.

### [Davy Crockett bot](https://github.com/dgilman/tmnt_wikipedia_bot)
* Fork of the [Wikipedia page titles singable to the Teenage Mutant Ninja Turtles Twitter bot](https://twitter.com/wiki_tmnt) to tweet Wikipedia page titles matching the syllable stress pattern of the [theme song to the 1950s-era Davy Crockett TV series](https://www.youtube.com/watch?v=txcRQedoEyY).

## Writing
* [Lessons learned porting from SQL Server to SQLite](https://gilslotd.com/blog/lessons_learned_porting_sql_server_sqlite)
* [Using SQLite with Python](https://dgilman.github.io/sqlite_python/) Presentation on SQLite internals and Python for the Charlotte Python Meetup
* [My criticism of dotdrop, a dotfile management system](https://gilslotd.com/blog/my_criticism_dotdrop_dotfile_management_system)
* Author of the Wikipedia articles on the [Ridgeway gold mine](https://en.wikipedia.org/wiki/Ridgeway_Mine) and [Runza sandwich](https://en.wikipedia.org/wiki/Runza)

## Other websites
* [Personal blog - Gil's LotD!](https://gilslotd.com/blog)
* [Academic Decathlon Scores and Information Center](https://acadecscores.gilslotd.com/wiki/Main_Page) - webmaster of a MediaWiki installation since its inception in 2007

## Packaging work
#### [aacgain](https://github.com/dgilman/aacgain)
* Converted the build system to CMake, got CI and CD working on Windows, MacOS X and Linux with TravisCI and Appveyor
#### [ngx\_brotli](https://github.com/dgilman/nginx/releases)
* Built Debian packages for ngx\_brotli in GitHub Actions and hosted on GitHub Releases
#### [MacPorts](https://www.macports.org/)
* Contributor and package maintainer to the MacPorts package manager.
#### [netatalk-debian](https://github.com/dgilman/netatalk-debian)
* Got the Debian packaging building and publishing to GitHub via travis.ci.

## Miscellaneous work
* Organizer for the monthly, in-person [Python meetup group](https://www.meetup.com/python-charlotte/) in Charlotte, NC
* Contributed a [bug fix](https://commitfest.postgresql.org/28/2568/) to PostgreSQL's pg\_restore utility.
* Removed six support from [astroid and pylint](https://github.com/PyCQA/astroid/pull/864)
* Moved some [number crunching](https://github.com/dgilman/pandas_stats) over to the Python Pandas library.
