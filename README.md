### Running

```
bundle exec jekyll serve
```
or
```
rake build:dev
```

### Deploying

Make sure all assets are pushed to `gh-pages` branch

```
rake build:pro
rake commit
rake deploy
```

