# Form Validator README

![Form Validator Logo](https://sonnymay.github.io/Form-Validator/assets/images/form-validator-logo.png)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Form Validator is a lightweight, easy-to-use JavaScript library designed to simplify form validation tasks. It aims to provide a seamless user experience and improve the overall quality of form submissions by validating user inputs before they are sent to the server.

Visit the [official website](https://sonnymay.github.io/Form-Validator/) for more information and documentation.

## Features

- Built-in validation for common input types, such as email, phone numbers, and URLs
- Support for custom validation rules
- Asynchronous validation for server-side checks
- Highly customizable error messages and styling
- Easy integration with popular front-end frameworks and libraries

## Getting Started

Follow these steps to set up and use Form Validator in your own projects.

### Prerequisites

Before using Form Validator, ensure that you have the following software installed on your system:

- A modern web browser that supports ECMAScript 6 (ES6) or later
- A text editor or IDE for editing HTML, CSS, and JavaScript files

### Installation

To install Form Validator, simply download the latest release from the [official website](https://sonnymay.github.io/Form-Validator/download) or the [GitHub repository](https://github.com/sonnymay/Form-Validator/releases).

Include the Form Validator script in your HTML file, preferably before the closing `</body>` tag:

```html
<script src="path/to/form-validator.min.js"></script>
```

Replace `path/to` with the actual path to the Form Validator script.

## Usage

To use Form Validator, first create an HTML form and add the `data-validate` attribute to the input fields you want to validate:

```html
<form id="my-form">
  <input type="email" data-validate="email" />
  <input type="password" data-validate="password" />
  <button type="submit">Submit</button>
</form>
```

Next, initialize the Form Validator in your JavaScript file:

```javascript
const form = document.getElementById("my-form");
const validator = new FormValidator(form);
```

That's it! Form Validator will now validate your form inputs and display appropriate error messages when needed.

For more detailed instructions and examples, check out the [official documentation](https://sonnymay.github.io/Form-Validator/docs).

## Customization

Form Validator offers several customization options, including custom validation rules, error messages, and styling. Check out the [customization guide](https://sonnymay.github.io/Form-Validator/docs/customization) in the official documentation for more information.

## Contributing

Contributions to Form Validator are welcome! Please read the [contributing guidelines](https://github.com/sonnymay/Form-Validator/blob/master/CONTRIBUTING.md) to learn how to get started.

## License

Form Validator is released under the [MIT License](https://github.com/sonnymay/Form-Validator/blob/master/LICENSE).

## Contact

If you have any questions, suggestions, or feedback, please feel free to reach out to the project maintainers through the [official website](https://sonnymay.github.io/Form-Validator/contact) or by opening an issue on the [GitHub repository](https://github.com/son
