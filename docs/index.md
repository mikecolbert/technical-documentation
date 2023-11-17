# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).  
This site based on this Youtube video: https://github.com/james-willett/mkdocs-material-youtube-tutorial

## Commands

- `mkdocs new [dir-name]` - Create a new project.
- `mkdocs serve` - Start the live-reloading docs server.
- `mkdocs build` - Build the documentation site.
- `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Address in use error

First, run `sudo kill $(sudo lsof -t -i:8000)` from the terminal.  
Then, start the mkdocs server `mkdocs serve`.

## mdbook

https://github.com/rust-lang/mdBook

https://github.com/rust-lang/book

https://doc.rust-lang.org/book/

https://rust-book.cs.brown.edu/
