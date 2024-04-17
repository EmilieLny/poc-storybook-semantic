# Semantic UI Storybook POC

## Overview

This repository contains a Proof of Concept (POC) project built with Storybook showcasing the usage of Semantic UI components within a Storybook environment. The project aims to provide a visual documentation and playground for Semantic UI components customized, allowing developers to explore and interact with them in isolation.

## Features

- **Storybook Integration**: Demonstrates how to integrate Storybook into a project for component-driven development.
- **Semantic UI Components**: Provides a collection of Semantic UI components organized as stories within Storybook.
- **Interactive Playground**: Allows developers to interact with individual components, adjusting props and viewing different states.
- **Documentation**: Serves as a visual documentation for Semantic UI components, making it easier to understand their usage and variations.

## Installation

1. Clone the repository to your local machine:

    ```
    git clone git@github.com:EmilieLny/poc-storybook-semantic.git
    ```

2. Navigate to the project directory:

    ```
    cd poc-storybook-semantic
    ```

3. Install dependencies using npm or yarn:

    ```
    npm install
    ```
    or
    ```
    yarn install
    ```

## Usage

To run Storybook locally, execute the following command:

```
npm run storybook
```
or
```
yarn storybook
```

This will start the Storybook server and open it in your default web browser. You can then navigate through different Semantic UI components and interact with them in the Storybook interface.

## Project Structure

The project structure is organized as follows:

```
semantic-ui-storybook-poc/
│
├── .storybook/
│   └── main.js
│
├── src/
│   ├── Button/
│   │   ├── Button.stories.js
│   │   └── Button.js
│   ├── Input/
│   │   ├── Input.stories.js
│   │   └── Input.js
│   └── ...
│   └── index.js
│
└── package.json
```

- **.storybook/**: Contains configuration files for Storybook.
  - **main.js**: Main configuration file for Storybook.
- **src/**: Directory for Semantic UI components organized as stories.
  - **Button/**: Example component directory.
    - **Button.stories.js**: Storybook stories for the Button component.
    - **Button.js**: Implementation of the Button component.
  - **Input/**: Example component directory.
    - **Input.stories.js**: Storybook stories for the Input component.
    - **Input.js**: Implementation of the Input component.
  - **...**: Additional Semantic UI component directories.
  - **index.js**: Entry point of the application.
- **package.json**: Configuration file for npm dependencies and scripts.

## Dependencies

- [Storybook](https://storybook.js.org/): An open source tool for building UI components and pages in isolation.
- [Semantic UI React](https://react.semantic-ui.com/): The official Semantic UI React integration.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
