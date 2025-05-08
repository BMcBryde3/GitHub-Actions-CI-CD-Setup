# GitHub-Actions-CI-CD-Setup

## Description

This application's puprose to test CI/CD actions with gitHub Actions utilizing YML files.

## Table Of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [License](#license)
4. [Contribution Guidelines](#contribution)
5. [Tests](#tests)
6. [Questions](#questions)

## Installation

1. Install the files, make sure you also have MongoDB installed.
2. Open the base file in a terminal and run "npm i", followed by "npm run build".
3. Add an .env file with the following values and appropriate links to your db:
   MONGODB_URI='mongodb://000.0.0.1:27017/questions'
4. Then start the program run "npm run start:dev".

## Usage

1. when pushing any update to the Develope branch, you should have GitHub run test on compents and E2E to esnure the application performs as epected.
2. When merging the Develope Branch changes with the Main branch, an addtional check should be made on the devlope applications. If successfull, this should push a deploy to render.

## License

MIT.

## Contribution Guidelines

None

## Tests

Render and Visual Studio Code

## Questions

Feel free to reach out to me if you have any questions, or if you'd like to find out what else I've worked on. My details are as follows:  
Github: https://github.com/BMcBryde3
Email: Brett.McBryde@yahoo.com
