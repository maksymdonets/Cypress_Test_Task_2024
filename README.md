## Cypress test task
- One of the test should be failed to trigger the report

## Requirements:
- npm >= 9.4.0
- node >= 16

## Installation:

1. Clone the project
2. Go to the root folder of the project
3. Install dependencies

   `npm install`

4. Install cypress

   `npm install cypress`

## Running Tests:

- Run web-server to execution test suites:

  `npm run open`

  `npx cypress open`

- Run tests in console:

  `npm run test`

- Run specific tests in console:
  `npm run test -- --spec "./cypress/e2e/YourTest.cy.js"`
