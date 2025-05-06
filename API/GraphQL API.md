### Describe your data

```
type Project {  name: String  tagline: String  contributors: [User]}
```

### Ask for what you want

```
{  project(name: "GraphQL") {    tagline  }}
```

### Get predictable results

```
{  "project": {    "tagline": "A query language for APIs"  }}
```

GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data. GraphQL provides a complete and understandable description of the data in your API, gives clients the power to ask for exactly what they need and nothing more, makes it easier to evolve APIs over time, and enables powerful developer tools.

## Get many resources in a single request

GraphQL queries access not just the properties of one resource but also smoothly follow references between them. While typical REST APIs require loading from multiple URLs, GraphQL APIs get all the data your app needs in a single request. Apps using GraphQL can be quick even on slow mobile network connections.