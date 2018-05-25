# Intro to GraphQL

## Overview

* What is GraphQL?
* See an Example GraphQL API
* Build a Simple TODO GraphQL API (with an array)
* **Use mongo instead of array... 
* **Build a GraphQL API on top of an existing REST API

## Intro to GraphQL

* [ ] What is GraphQL?
  * GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data.
  * GraphQL provides a complete and understandable description of the data in your API
  * Gives clients the power to ask for exactly what they need and nothing more
  * Enables powerful developer tools.
  * While typical REST APIs require loading from multiple URLs, GraphQL APIs get all the data your app needs in a single request.
  * GraphQL APIs are organized in terms of types and fields, not endpoints.
* See an Example
  * Github
    * REST API https://developer.github.com/v3/
    * GraphQL API https://developer.github.com/v4/explorer/
* Server Side Libraries
  * http://graphql.org/code/#javascript
* Client Side Libraries
  * http://graphql.org/code/#javascript-1
* Schemas and Types
  * The GraphQL query language is about selecting fields on objects
  * Object Types and Fields
    * http://graphql.org/learn/schema/#object-types-and-fields
  * Arguments: Arguments are named! No specific order needed.
    * http://graphql.org/learn/schema/#arguments
  * Query and Mutation Types
    * http://graphql.org/learn/schema/#the-query-and-mutation-types
    * Every GraphQL service has a query type and may or may not have a mutation type. 
  * Scalar Types
    * http://graphql.org/learn/schema/#scalar-types
    * Int: A signed 32‐bit integer.
    * Float: A signed double-precision floating-point value.
    * String: A UTF‐8 character sequence.
    * Boolean: true or false.
    * ID: The ID scalar type represents a unique identifier
  * Enumeration Types
    * http://graphql.org/learn/schema/#enumeration-types
    * Also called Enums, enumeration types are a special kind of scalar that is restricted to a particular set of allowed values. 
  * Lists and Non-Null
    * http://graphql.org/learn/schema/#lists-and-non-null
    * Mark something as Non-Null by adding an exclamation mark, ! after the type name.
    * We can use a type modifier to mark a type as a List, which indicates that this field will return an array of that type. []
* Queries and Mutations
  * Fields
    * At its simplest, GraphQL is about asking for specific fields on objects.
    * http://graphql.org/learn/queries/#fields
  * Arguments
    * In GraphQL, every field and nested object can get its own set of arguments
    * Arguments are a complete replacement for making multiple API requests
    * http://graphql.org/learn/queries/#arguments
* Build a simple TODO GraphQL API (in memory array)
  * Create node app/install graphql-yoga
  * Define Todo Type
  * Define Query Type
    * Get All Todos
  * Define Query Resolver
    * Get All Todos
  * Define Create Mutation
  * Define Create Resolver
  * Define Delete Mutation
  * Define Delete Resolver
* Build a simple TODO GraphQL Client
  * Create client app/install nanographql
  * Query for all on page load
* **Use mongo instead of array... 
* **Build a GraphQL API on top of an existing REST API

## Resources

* [GraphQL Services](http://graphql.org/code/#services)
* [Zero to GraphQL in 30 Minutes – Steven Luscher](https://www.youtube.com/watch?v=UBGzsb2UkeY)