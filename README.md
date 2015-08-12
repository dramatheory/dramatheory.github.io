# DramaTheory.org

This is the source code for the http://dramatheory.org website.

## Contributions

This is a community managed website, and contributions are welcome.
Instructions can be found in the [wiki][1].

## Developers

This website is created with [Jekyll, and is hosted by GitHub Pages][2].


### Setup a local development environment.

To build the website:

First clone this repository:

```
git clone git@github.com:dramatheory/dramatheory.github.io.git
```

Then install the dependencies:

```
cd dramatheory.github.io
bundle install --binstubs --path=vendor/gems
```

Then run the development server:

```
./bin/jekyll serve
```

This will start a server at: http://localhost:4000/

Changes you make to the source code will be updated when you refresh the
browser page.

### Submit code changes

Please use the [Fork & Pull][3] method of submitting code changes to this
repository.


[1]: https://github.com/dramatheory/dramatheory.github.io/wiki/Contributing
[2]: https://help.github.com/articles/using-jekyll-with-pages/
[3]: https://help.github.com/articles/using-pull-requests/
