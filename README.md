# preactStore

Example commerce store UI leveraging preact-cli and graphql-faker.

##Prerequisites

You will need the following installed on your host machine:
* git
* Virtualbox
* Vagrant

## Getting Started

1. Get the code
  * `git clone https://github.com/mariboudev/preactStore.git`
2. Create the VM with node, npm, preact-cli and graphql-faker installed
  * ```vagrant up```
3. SSH into the VM and install the dependencies
  * ```vagrant ssh```
  * ```cd /vagrant/webStore```
  * ```npm install```
4. Move into PWA directory to start serving the app
  * ```cd webStore```
5. Start up the dev server or build for prod using the [npm controls](webStore/README.md "npm commands")
6. [Start up the GraphQL server](graphql/README.md)
