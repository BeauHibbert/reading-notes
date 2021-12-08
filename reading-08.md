# Reading notes 08
Notes from :
https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design
https://regexr.com/
https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285
https://regex101.com/

## What does REST stand for?

Representational State Transfer

## REST APIs are designed around a ____.

REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.

## What is an identifer of a resource? Give an example.

It is a URI(uniform resource identifier) that uniquely identifies that resource.
An example would be a URL. 

## What are the most common HTTP verbs?

GET, POST, PUT, PATCH, DELETE

## What should the URIs be based on?

When possible, resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

## Give an example of a good URI.

A good URI is simple. “collection/item/collection” for example.

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

It is a web API that exposes a large number of small resources. The more web requests the bigger the load on the server so the slower it becomes.

## What status code does a successful GET request return?

It will return 200(ok) if successful.

## What status code does an unsuccessful GET request return?

It will return 404(not found) if unsuccessful

## What status code does a successful POST request return?

If it creates a new resource it will return 201(created). It can also return 200(ok) if it just does some processing

## What status code does a successful DELETE request return?

It will return 204(no content)
