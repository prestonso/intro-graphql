# Introduction to GraphQL
"Introduction to GraphQL" presentation covering GraphQL origins, motivations, syntax, and schemas

## Abstract
GraphQL has been deemed everything from the death knell of RESTful architectures to the query language of the future. Created by Facebook to power its data fetching and [coming to Drupal 8](https://drupal.org/project/graphql) thanks to [Sebastian Siemssen](https://drupal.org/u/fubhy), GraphQL portends a dizzying shift in not only how client-side applications request and receive data but also how payloads are interpreted and formatted on the server side. What exactly is GraphQL, and what distinguishes it from the rest (no pun intended)? What are the weaknesses of REST that GraphQL aims to resolve? What differentiates GraphQL from plain old JSON?

The most compelling features of GraphQL come from its graceful yet simple matching between the request's structure and the response's. This means that the client sends a query whose shape mirrors that of the returned data -- no need for multiple views for a single resource, and no under- or overfetching of data. What are the impacts of this on Drupal and the REST layer now in core? Perhaps more intriguingly, what is the future of decoupled ("headless") Drupal in light of GraphQL?

This session will delve into the following subjects:

- The origins of GraphQL at Facebook
- Motivations for GraphQL
- Limitations of RESTful APIs
- GraphQL and REST
- Shared structure across server and client
- Syntactic features of GraphQL
- Queries and mutations
- Arguments and aliases
- Variables and directives
- Types and introspection
- GraphQL and Drupal 8
- Epilogue: GraphQL and decoupled Drupal

This session is intended for developers working with REST and Drupal 8, especially decoupled architectures.

## Presentations

- [BADCamp 2015](https://2015.badcamp.net/session/introduction-graphql); Berkeley, CA
