# apollo-server
GraphQL training 
## What is GraphQL?
GraphQL is an open source server-side technology which was developed by Facebook to optimize RESTful API calls. It is an execution engine and a data query language. This tutorial will introduce you to the fundamental concepts of GraphQL including −

### Implement GraphQL API using Apollo server

### Test GraphQL API using GraphiQL

### Build ReactJS (with Apollo Client library) and jQuery client applications to consume the API

## Difference between GraphQL and Rest.
A REST API is an architectural concept for network-based software. GraphQL, on the other hand, is a query language, a specification, and a set of tools that operates over a single endpoint using HTTP. In addition, over the last few years, REST has been used to make new APIs, while the focus of GraphQL has been to optimize for performance and flexibility.

## rite down about Schema and Resolvers.
### Resolver 
Resolver is a collection of functions that generate response for a GraphQL query. In simple terms, a resolver acts as a GraphQL query handler. Every resolver function in a GraphQL schema accepts four positional arguments 

### Schema
A GraphQL schema is at the core of any GraphQL server implementation. It describes the functionality available to the client applications that connect to it. We can use any programming language to create a GraphQL schema and build an interface around it.

The GraphQL runtime defines a generic graph-based schema to publish the capabilities of the data service it represents. Client applications can query the schema within its capabilities. This approach decouples clients from servers and allows both to evolve and scale independently.

In this chapter, we use Apollo server to execute GraphQL queries. The makeExecutableSchema function in graphql-tools helps you to bind schema and resolvers.