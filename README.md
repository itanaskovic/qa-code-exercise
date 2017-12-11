# QA Code Exercise

## Objective

Demonstrate a variety of skills that are needed to be successful at DataScience:

* coding with Python, JavaScript, or Go
* writing automated tests
* writing, reading, and using documentation
* understanding of how APIs work
* using Git


## Where to Start
GitHub's API docs are located at [https://developer.github.com](https://developer.github.com). You can build your test suite against v3 which is a REST API. For bonus points you can build against v4 which is a GraphQL API.

## Exercise

The test suite should be committed to a public repo. Provide a README with instructions on how to run the tests.

You'll need a GitHub repo to target your tests against and may reuse an existing one or make a new one.

Write tests for the following:

### Git Data Operations

* List the tree contents
* Return the contents of a file
* Create a file

### Repo Operations

* List the branches
* Change the repo description
* Add a new issue
* Create a pull request

## Extra Credit

* Containerize the test suite with a Dockerfile
* Run the test suite in a CI server like Travis
* Instead of testing the REST API (v3), test the GraphQL API (v4)