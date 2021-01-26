# Pupilfirst API Docs

This repo generates & holds documentation for the Pupilfirst LMS API.

View documentation here: https://pupilfirst.github.io/pupilfirst-api-docs

## How to generate

```
$ yarn run build
$ mv public docs
```

## Known issues

The `dociql` package seems to have a bug which causes it to ignore most, if not all of its command line options. According to the docs, we should be able to run `dociql -c config.yml -t docs -l logo.png`, but all the command line options are ignored.

Related issue: https://github.com/wayfair/dociql/issues/20
