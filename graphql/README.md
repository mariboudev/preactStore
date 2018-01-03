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

Alternatively it is possible to start the instance as a Docker container, but it would need to be run on a different port, because 9002 is allocated to the VM instance (for the GraphQL instance).
This would also require a change to the webStore configuration to point it at the correct port or a change to the vagrantfile so that the VM no longer claims the port.
