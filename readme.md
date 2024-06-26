# Linkki-web

Repository of [linkkijkl.fi](https://linkkijkl.fi).


## Getting started

To compile and open locally:
1. Install [Hugo extended edition](https://gohugo.io/) and [Git Large File Storage](https://git-lfs.com)
2. Clone this repository, i.e. `git clone https://github.com/linkkijkl/linkki-web`
3. Initialize git submodules `git submodule init && git submodule update`
4. Run `hugo server` and you should be good to go 🎉

Or optionally, on some supported Unix based environments _(currently MacOS, Debian and Fedora)_, you can just run `startup.sh`.

## Building and running with [Docker](https://www.docker.com/)

```shell
docker build -t linkkijkl/linkki-web:latest .
docker run -p 127.0.0.1:8080:8080 linkkijkl-web
```


## FAQ

### How do I submit changes I want to contribute with?

Make a pull request with your changes so we can get them online 🙂

### I have spotted an error, how do I report it?

Make a new issue detailing the problem.

### I want to contribute but don't know what to do, where should I start?

Take a look at open issues. From there you should find something to do.

### `hugo server` fails after git pull:

Try running `git submodule init && git submodule update` and make sure
you have the extended edition of Hugo installed.
