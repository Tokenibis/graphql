# GraphQL

This is a shallow repository containing all of the GraphQL queries and
mutations that the frontend uses to communicate with the backend. Both
contain this repository as a submodule. The intention is to align the
django testing suite in the backend with all mutations and queries
that are actually unsed in the frontend. Queries and mutations are
stored as .gql files in Graphql/ and should contain exactly one
operation each with the same name as the file.
