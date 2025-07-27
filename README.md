## ngx-cypress-test-master 
https://enbridge.udemy.com/course/cypress-web-automation-testing-from-zero-to-hero

## install and run
- npm install --force
- npm start
- visit http://localhost:4200/pages
## install cypress
- npm install cypress --save-dev --force
- should find "cypress": "^14.5.3" in package.json

## npm vs npx
- npm: a way for developers to install Node.js packages both globally and locally
- npx: Run a locally Node.js based executable package, like npx cypress open
  - choose E2E => Electron => Great! We added the following files to your project
  - match test case
    ![Test cases](Readme/MatchTestCase.png)

## multiple Config Files Example
```
cypress.config.angular.ts
cypress.config.react.ts
cypress.config.vue.ts
```
npx cypress run --config-file cypress.config.react.ts
