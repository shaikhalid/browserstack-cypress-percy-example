```bash
npm install --legacy-peer-dep
npm start

##In a new terminal
export PERCY_TOKEN=PERCY_PROJECT_TOKEN
percy exec -- browserstack-cypress run -s cypress/e2e/1-getting-started/todo.cy.js
```