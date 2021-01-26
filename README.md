# tavonius.de

Watch it at [Tavonius.de](http://www.tavonius.de).

## How to deploy

```bash
# change stuff
git push
rsync -v -zar -p --exclude=.git  . deploy@tavonius.de:/var/www/tavonius
```
