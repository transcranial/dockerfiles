# postgresql-client

Adapted from [jbergknoff/postgresql-client](https://hub.docker.com/r/jbergknoff/postgresql-client). Modified to use latest alpine linux version.

Minimal environment with PostgreSQL client:

* built on top of `alpine` base image
* ~6 MB in size (5 MB base + 1 MB)

### Example usage:

```bash
$ docker run -it --rm transcranial/postgresql-client postgresql://user:pass@host:5432/db
```
