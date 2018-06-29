MongoDB Blog 
========

This is a simple web-based blog that uses Flask, HTML, CSS, Bootstrap, Jinja2.

The blog requires MongoDB to be running without authentication enabled.

Once this is running, execute the app and navigate to the endpoint (default: `http://127.0.0.1:4995/`).

The available endpoints are:

- `/`
- `/login`
- `/register`
- `/blogs`
- `/blogs/new`
- `/posts/<string:blog_id>`
- `/posts/new/<string:blog_id>`
