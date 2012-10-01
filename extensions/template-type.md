# Template Type

Support a template type field that instructs the client with which content-type to submit the template.

```json
{ "collection" :
  {
    "version" : "1.0",
    "href" : "http://example.org/photos",

    "template" : {
      "type": "multipart/form-data",
      "data" : [
        {"name" : "title", "value" : "", "prompt" : "Title"}
      ]
    }
  }
}
```

### References
1. https://groups.google.com/forum/#!topic/collectionjson/Mk7M1w35XSs
