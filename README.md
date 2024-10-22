# Cypress Demo

This is a demo project showcasing the use of [Cypress](https://www.cypress.io/), a powerful end-to-end testing framework for web applications.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (version 12 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)

## Getting Started

Follow the steps below to set up and run Cypress for this project.

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/cypress-demo.git
cd cypress-demo
```

### 2. Install Cypress

To install Cypress and other dependencies, run:

```bash
npm install
```

This command will install Cypress along with any other dependencies specified in the `package.json` file.

### 3. Open Cypress Test Runner

To open the interactive Cypress Test Runner, use:

```bash
npx cypress open
```

This will launch the Cypress Test Runner, where you can select and run your tests in a browser.

### 4. Run Cypress in Headless Mode

To run Cypress tests in the command line (headless mode), use:

```bash
npx cypress run
```

This command will execute the tests without opening the Cypress Test Runner UI and output the results in the terminal.

## Folder Structure

The basic folder structure for Cypress tests is as follows:

```
cypress-demo/
│
├── cypress/
│   ├── downloads/     # Test files
│   ├── e2e/           # Test files
│   ├── fixtures/      # Test data
│   ├── plugins/       # Plugins for extending Cypress functionality
│   └── support/       # Custom commands and support utilities
│
├── node_modules/      # Installed dependencies
├── cypress.json       # Cypress configuration file
└── package.json       # npm project file (includes Cypress as a devDependency)
```

## Running Tests

To run specific tests or folders of tests, navigate to the `cypress/integration/` directory and modify or add `.spec.js` files for the tests you want to execute.

## Learn More

- [Cypress Documentation](https://docs.cypress.io/guides/overview/why-cypress.html)
- [Cypress GitHub](https://github.com/cypress-io/cypress)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
