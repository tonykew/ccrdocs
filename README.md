# CCR Research Computing Documentation

[![Documentation Status](https://readthedocs.org/projects/ubccr/badge/?version=latest)](https://ubccr.readthedocs.io/en/latest/?badge=latest)

This is the main repository for CCR's research computing documentation. 

https://docs.ccr.buffalo.edu

Find an error? Feel free to [submit an issue](https://github.com/ubccr/ccrdocs/issues).

## How to contribute

Contributions and PRs welcome! Follow the instructions below to learn how to
develop and make changes to the documentation source.

1. [Fork this repo](https://github.com/ubccr/ccrdocs/fork)

2. Clone your fork:
```
$ git clone https://github.com/YOURUSER/ccrdocs.git
$ cd ccrdocs
```

3. Create a python3 virtual environment and install dependencies:

```
$ python3 -mvenv venv
$ source venv/bin/activate
$ pip install --upgrade pip
$ pip install -r requirements.txt
```

4. Run mkdocs development server:

```
$ mkdocs serve
```

5. Point your browser at: http://localhost:8000

6. Start hacking on the markdown in the `pages/` directory

7. Submit a [PR](https://github.com/ubccr/ccrdocs/pulls)


## Coding style, tips and conventions

- Try to keep content organized in respective directories under `pages/`

- Remember to add any new pages to the nav config in `mkdocs.yml`

- For a nice overview of markdown syntax [see here](https://www.markdownguide.org/basic-syntax)

- Add notes (note, warning, danger, important) to your docs. [See here for markdown syntax](https://python-markdown.github.io/extensions/admonition/)

## License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/)
