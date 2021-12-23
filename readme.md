### E-Learning

### Fixures
```
Python3 manage.py dumpdata courses --indent=2
```
###Fixutures to json </br>

``mkdir <dir(fixtures)>``

```
python3 manage.py dumpdata courses --indent=2 --output=<appdir>/fixtures/<filename.json>
```

### Load data from fixtures
```
python3 manage.py loaddata <filename.json>
```

so

