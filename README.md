# Cypress End-to-End Testing - Getting Started Course Resources

This project contains multiple sub-projects, each with its own set of end-to-end (E2E) tests using Cypress. The tests are organized into six different folders, each representing a different level or project.

## Prerequisites

Make sure you have the following installed on your machine:
- [Node.js](https://nodejs.org/en/download/)
- [npm](https://www.npmjs.com/get-npm)

## Running the Tests

Each set of tests is located in its own folder. To run the tests for a specific project, follow these steps:

### 1. Navigate to the Project Folder

First, navigate to the folder of the project you want to test. Replace `project-folder` with the actual name of the folder.

```bash
cd path/to/project-folder
```

### 2. Install Dependencies

Once inside the project folder, install the necessary dependencies.

```bash
npm install
```

### 3. Start the Project

Start the project to ensure it is running. This is necessary for the E2E tests to execute properly.

```bash
npm run dev
```

### 4. Run Cypress

Open Cypress to run the tests. This will open the Cypress Test Runner where you can select and run the tests.

```bash
npx cypress open
```

## Folder Structure

Below is the folder structure for the different levels and projects:

- `01-getting-started`
- `02-basics`
- `03-diving-deeper`
- `04-config`
- `05-stubs`
- `06-network-auth`

Navigate into each folder and follow the steps above to run the tests for that specific project.

## Additional Information

For more information on Cypress and writing E2E tests, visit the [Cypress Documentation](https://docs.cypress.io/).