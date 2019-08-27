# Lemon One Engineer Recruitment Test

Thank you for taking the time to do our technical test.

We appreciate your time and we hope you don't need more than 2 hours on this exercise. We don't intend to evaluate a fully production ready solution but a simple proof of concept. We'll focus on how you structure your code and what trade-offs you choose within the time constraints of this exercise.

Please make this a single zip file named `{yourname}-{role-applied-for}.zip` and send us by email. The zip file must follow this structure:

- All in one folder with the whole exercise

- Provide a `README` file with:

  - Short description on your approach to solve the exercise.

  - Explaing how to execute the solution and any other relevant command.

  - How will you improve your solution if you would have more time.

## Platform/Toolset Choice

You can use any tools you feel confortable and productive using. Just as a reference this is the tech stack we use here at Lemon One:

- [ReactJS](https://reactjs.org/) to build our user interfaces.

- [Jest](https://jestjs.io/) to unit test our code.

- [Cypress](https://www.cypress.io/) to perform end-to-end testing.

- [GraphQL](https://graphql.org/) API to fetch and manage the data requests from our user
  interfaces.
- [Node.js](https://nodejs.org/) to write the server side code.

- [AWS services](https://aws.amazon.com/) like AWS Lambda, S3 buckets, DynamoDB, AppSync, etc.

- [MongoDB](https://www.mongodb.com/) to store our data.

- [CircleCI](https://circleci.com/) to run our CI/CD pipeline.

## Exercise

Build a simple interface where we can create, view, edit and delete photographers.

That's the photographers properties:

- Name
- Email
- Cameras: _list with all different camera models that the photographer owns_.

And the cameras properties:

- Name
- Resolution

### Photographers API

To perform queries to create, view, edit and delete any data you can use the mock API provided in this repository.

It is a GraphQL API using [json-graphql-server](https://github.com/marmelab/json-graphql-server) to get a full fake GraphQL API with zero coding in less than 30 seconds.

You can start it like this:

- `yarn install`
- `yarn start:graphql`

Then you can query this API at `http://localhost:3001/`

> Remember that the goal of this exercise is not a pixel perfect UI, but a functional one. We'll focus on the code structure and good practices when evaluation your soulution.
