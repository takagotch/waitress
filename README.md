### waitress
---
https://github.com/Pylons/waitress

https://waitress.readthedocs.io/en/latest/

```py
// waitress/tests/fixtureapps/toolarge.py
def app(environ, start_response):
  body = b'abcdef'
  cl = len(body)
  start_response(
    '200 OK',
    [('Content-Length', str(cl)), ('Content-Type', 'text/plain')]
  )
  return [body]


```

```
```

```
```

