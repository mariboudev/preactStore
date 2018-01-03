# Fake GraphQL server
`schema.faker.graphql` is the configuration file for running a [graphql-faker](https://github.com/APIs-guru/graphql-faker) server instance

## Starting the server
* From inside this directory `graphql-faker schema.faker.graphql`
* From elsewhere in the VM `graphql-faker /vagrant/graphql/schema.faker.graphql`

## Accessing the IDL Editor and GraphiQL UI
  
  ```
  ❯ Interactive Editor:	 http://localhost:9002/editor
  ❯ GraphQL API:	 http://localhost:9002/graphql
  ```

Updates saved via the editor will modify the `schema.faker.graphql` file. Commit/push these changes to share them.
