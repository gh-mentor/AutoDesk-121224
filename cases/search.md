
```
Case Study: Plan Python Search Engine Service
```

```
I need a project plan to build a service that will hook into the Bing public search engine. The service will be written using Python 3.14. The service will support indexing internal content, and will process search queries through a dispatch using the 'requests' library. The service will use threads to handle different tasks concurrently and include the dispatch logic to route queries to either Bing or an internal indexer, depending on the query type. The service will adhere to SOLID principles and properly handle errors and exceptions. The service will be built using TDD with DocTest. Provide a breakdown high-level steps to accomplish this goal. Include examples of how to use DocTest to test the service.
```

```
Case Study: C++ Build Search Engine Service
```

```
I need to build a C++ service that will hook into the Bing public search engine.   
Requirements:
- Use GNU C++ 17
- separate the design into classes 
- the API must support the GET and POST protocols over HTTPS
- all requests must be logged
- adherence to SOLID principles 
- proper handling of errors and exceptions
Details:
- The service will be written using GNU C++ 17.
- support indexing internal content
- processes search queries through a dispatch using 'libcurl'
- uses threads to handle different tasks concurrently 
- includes and implements the dispatch logic to route queries to either Bing or an internal indexer, depending on the query type 
Edge Cases:
- The service must handle the case where the Bing API is down

```

```
Next demonstrate how to perform a GET request using libcurl and handle the response data.
```

```
Next I would like to use TDD with DocTest to create the tests first, then the service itself. What are the steps to accomplish this goal? Provide examples.
```

