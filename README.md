# tavonius.de

Watch it at [Tavonius.de](http://www.tavonius.de).

## How to deploy

```bash
# change stuff
git push
rsync -v -zar -p --exclude=.git  . calamari@h2060497.stratoserver.net:/var/www/tavonius
```
