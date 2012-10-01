# Template Upload

Support a field in a template to instruct the client to submit a file for the specified name.

This extension requires support for [template-type](template-type.md)

```json
{ "collection" :
  {
    "version" : "1.0",
    "href" : "http://example.org/photos",

    "template" : {
      "type": "multipart/form-data",
      "data" : [
        {"name" : "title", "value" : "", "prompt" : "Title"},
        {"name" : "image", "value" : "", "prompt" : "Image", "file": true}
      ]
    }
  }
}
```

### References
1. https://groups.google.com/forum/#!topic/collectionjson/Mk7M1w35XSs
