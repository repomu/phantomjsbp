# phantomjsbp

A Heroku buildpack for phantomjs that always downloads the latest static build.
Unlike other build packs, I never compile anything and remove this git.

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/repomu/phantomjsbp.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/repomu/phantomjsbp.git
```
