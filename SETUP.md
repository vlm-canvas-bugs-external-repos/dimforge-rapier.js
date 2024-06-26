# Setup Instructions for dimforge-rapier.js

This document guides you through the setup required to run the 2D demo for `dimforge-rapier.js`.

## Prerequisites

Ensure you have the following installed:

- Node.js (version 14.x or 16.x recommended)
- npm (Node package manager)
- nvm (Node Version Manager) - optional but recommended

## Steps to Setup and Run the 2D Demo

### 1. Setting the Node.js Version (Optional)

It's recommended to use Node.js version 16 for this project. If you have [nvm](https://github.com/nvm-sh/nvm) installed, you can use the following commands to install and use Node.js version 16:

```bash
nvm install 16
nvm use 16
```

### 2. Building `rapier2d`

Navigate to the `rapier2d` directory, install dependencies, and build the project:

```bash
cd dimforge-rapier.js/rapier2d
npm install
npm run build
```

### 3. Building and Running `testbed2d`

Navigate to the `testbed2d` directory, install dependencies, build the project, and start the demo:

```bash
cd ../testbed2d
npm install
npm run build
npm start
```

This will launch your default browser and navigate to `http://localhost:8080/` where you can see the 2D demo in action.

## Summary of Commands

```bash
# Building rapier2d
cd dimforge-rapier.js/rapier2d
npm install
npm run build

# Building and Running testbed2d
cd ../testbed2d
npm install
npm run build
npm start
```

## Troubleshooting

- If you encounter any TypeScript errors, ensure that all dependencies are correctly installed and that you are using a compatible Node.js version.
- If the demo does not start, check for any build errors in the console and address them as needed.

For further assistance, feel free to reach out or consult the documentation.

---
