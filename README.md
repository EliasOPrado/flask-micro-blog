# Flask Micro-blog project

## tasks that need to be fixed:

- Section 5: Forms
  - Needs to be well tied with other pages.
  
  errors that needs to be fixed:
  

```
[2019-08-01 18:01:57,203] ERROR in app: Exception on /login [GET]
Traceback (most recent call last):
  File "c:\program files\python37\lib\site-packages\flask\app.py", line 2446, in wsgi_app
    response = self.full_dispatch_request()
  File "c:\program files\python37\lib\site-packages\flask\app.py", line 1952, in full_dispatch_request
    return self.finalize_request(rv)
  File "c:\program files\python37\lib\site-packages\flask\app.py", line 1967, in finalize_request
    response = self.make_response(rv)
  File "c:\program files\python37\lib\site-packages\flask\app.py", line 2097, in make_response
    "The view function did not return a valid response. The"
TypeError: The view function did not return a valid response. The function either returned None or ended without a return statement.
127.0.0.1 - - [01/Aug/2019 18:01:57] "GET /login HTTP/1.1" 500 -
```

PS: Stopped on Section 6 [Profile Pages and Avatars](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-vi-profile-page-and-avatars).
  