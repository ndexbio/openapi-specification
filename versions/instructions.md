# Instructions for Use
Folders are associated with each major version of the NDEx REST API, 
and are named accordingly.  For example, "V22" represents the 
NDEx 2.2 REST API.

Each folder contains a YAML definition file and its counterpart JSON definition file.

```
YAML files are more easily understood by humans, and thus are maintained as 
a source code representation of the OpenAPI document. JSON files,
on the other hand, are more easier processed by computers.`
```


The [ndextools/openapi-reader](https://github.com/ndextools/openapi-reader) uses a json 
formatted file for its input.

A number of code editors exist to create OpenAPI documents using YAML. Specifically,
the Open-source [swagger-api/swagger-editor](https://github.com/swagger-api/swagger-editor) 
 was used to develop the OpenAPI documents contained herein.