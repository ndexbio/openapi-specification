# Instructions for Use
Folders are associated with each major version of the NDEx REST API, 
and are named accordingly.  For example, "V22" represents the 
NDEx 2.2 REST API.

Each folder contains a YAML definition file and its counterpart JSON definition file.

```
YAML files are more easily understood by humans, and thus are maintained as a source code representation
of the OpenAPI document. JSON files, on the other hand, are more easier processed by computers.
```

The [ndextools/openapi-reader](https://github.com/ndextools/openapi-reader) uses the JSON 
formatted file for its input. The YAML file is used within a custom editor when the OpenAPI document
is being developed. 

A number of code editors exist to create OpenAPI documents using YAML. The Open-source 
[swagger-api/swagger-editor](https://github.com/swagger-api/swagger-editor) 
was used to develop these OpenAPI document files. Specifically, the YAML file is used when editing the 
document, and and the JSON file is output and subsequently added to the openapi-reader's *dist* directory. 

