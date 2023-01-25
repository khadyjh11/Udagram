
# Hosting a Full-Stack Application

# Links for front end
- http://khadyjh-bucket.s3-website-us-east-1.amazonaws.com/
# Links for backend end
- http://udagram-api-dev.eba-yz3jsneq.us-east-1.elasticbeanstalk.com/


# Hosting a Full-Stack Application

# Udagram

In this project, we are hosting the udagram application, which is a site that uploads images that include the back and front end

### Getting Started

1.Clone this repo locally into the location of your choice.
2.Move the content of the udagram folder at the root of the repository as this will become the main content of the project.
3.Open a terminal and navigate to the root of the repo
4.follow the instructions in the installation step

The project can run but is missing some information to connect to the database and storage service. These will be setup during the course of the project

### Dependencies

Dependencies to run the project:

- Node 14.15.1 v
- npm 6.14.8 v
- AWS CLI V2
- S3 bucket for upload frontend
- RDS for running database Postgres

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License
[License](LICENSE.txt)