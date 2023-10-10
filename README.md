# Fleming Society Web Page

## Table of Contents

- [Introduction](#introduction)
- [Development Guidelines](#development-guidelines)
  - [1. Use Bootstrap](#1-use-bootstrap)
  - [2. Create New Pages](#2-create-new-pages)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to the Fleming Society web page codebase! This README is designed to help fellow developers understand key practices and guidelines for developing within this project. Please make sure to follow these guidelines to ensure consistency and efficiency in our codebase.

## Development Guidelines

### 1. Use Bootstrap

Whenever possible, utilize Bootstrap to streamline the development process and maintain a consistent design across the project. When incorporating a new Bootstrap element, remember to update the linked version of Bootstrap in the HTML file. This ensures that we are always using the latest Bootstrap features and bug fixes.

Example of including Bootstrap in your HTML file:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js"></script>
```

Please make use of Bootstrap's CSS classes and components to maintain a cohesive and visually appealing user interface.

### 2. Create New Pages

When creating a new HTML page, it is recommended to start from the existing templates to maintain formatting consistency. Copy the layout.html and layout.css files into your new page directory and build upon them. This ensures that our project maintains a unified look and feel throughout.

Example of copying files:

```sh
Copy code
cp layout.html newpage.html
cp layout.css newpage.css
```

By following this practice, we can avoid unnecessary duplication of code and guarantee that styling and layout conform to our established standards.

## Contributing

We welcome contributions from all developers to improve and enhance this project. If you have suggestions, bug reports, or would like to contribute code, please refer to our CONTRIBUTING.md file for detailed instructions on how to get involved.

## License

This project is licensed under the MIT License.

### Thank you for contributing to Your Project Name! Happy coding!