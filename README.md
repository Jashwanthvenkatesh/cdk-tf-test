# Welcome to your CDK TypeScript project

This is a blank project for CDK development with TypeScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `npx cdk deploy`  deploy this stack to your default AWS account/region
* `npx cdk diff`    compare deployed stack with current state
* `npx cdk synth`   emits the synthesized CloudFormation template
Setup Instructions

Clone the repository:
git clone https://github.com/PetruV26/cdk-tf-test.git
cd cdk-tf-test
Install dependencies:
npm install
Build the project:
npm run build
Deploy the stack:
npx cdk deploy
Structure:
bin/: Contains the entry point of the CDK application.
lib/: Contains the infrastructure stacks and constructs.
test/: Contains unit tests for the CDK application.
cdk.json: Tells the CDK Toolkit how to execute your app.
