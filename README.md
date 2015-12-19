angularjs-couchdb-sample
========================

A simple sample that connect angularjs with couchdb by $resource

**You may need to have**:

 - CouchDB 1.3 or later installed in your local
 - Create a database named "projects":

```
curl -X PUT http://127.0.0.1:5984/projects
```

 - [enable CORS in CouchDB](http://wiki.apache.org/couchdb/CORS)

You can use Python's SimpleHTTPServer to run this sample.

```
python -m SimpleHTTPServer
```

Then point your browser to [http://localhost:8000/test.html](http://localhost:8000/test.html)
