# A few automation test examples using cypressio.

For work with tests you have to:
1. Clone repo TodoMVC repo:
- git clone https://github.com/cypress-io/cypress-realworld-testing-todomvc.git
2. Install Yarn:
- npm install -g yarn
3. Change directories into the repo:
- cd cypress-realworld-testing-todomvc
4. Install the dependencies with the following command:
- yarn install
5. Installing Cypress:
- yarn add cypress -D
6. Start the app:
- yarn start
7. In the new terminal window, during running app, run cypress:
- yarn cypress:open 
8. In the cypress window choose browser.
9. Add tests from this repo to your project:
- commands.js -> cypress-realworld-testing-todomvc/cypress/support
- tutorialTests.js -> cypress-realworld-testing-todomvc/cypress/integration/practice
- practice.spec.js -> cypress-realworld-testing-todomvc/cypress/integration/practice
10. Run tests.
