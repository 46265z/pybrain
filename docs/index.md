# Welcome to MkDocs


<!-- For full documentation visit [mkdocs.org](https://www.mkdocs.org). -->
## Проблем

* Long execution time

## Цели

* Тo minimize CPU time needed (ideally);
* To check the execution time of a given command or set of commands;
    * different methods/ways;
* To identify performance bottlenecks;
* Introduce optimization methods; discuss them.

## ?
...

## First try
As to begin with I ran all cells of [our target](https://example.com) notebook and I measured the time 'by hand'. It took 15 minutes considering that there was an error in the code at say 3/4 of its _execution length_. This quick test aims to frame very briefly what we will be dealing with in our work ahed.

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
