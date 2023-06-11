# Alphabet Position Converter

### [Kata Training]('https://www.codewars.com/kata/546f922b54af40e1e90001da/train/javascript)

## Description

This project is a JavaScript utility that converts a given text to its corresponding alphabet positions. It maps each letter of the English alphabet to its position in the alphabet (e.g., ```A = 1```, ```B = 2```, etc.) and returns the positions as a space-separated string. The utility handles both uppercase and lowercase letters.

This project was motivated by the need to convert text to alphabet positions in a simple and efficient way. It solves the problem of manually determining the positions of each letter in the alphabet by providing a convenient function.

## Tags

- Strings
- Fundamentals

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

To use this project, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the dependencies by running the command `npm install`.

## Usage

To convert text to alphabet positions, modify the `index.js` file and use the `alphabetPosition` function from the `solution.js` file. The function accepts a string as input and returns the corresponding alphabet positions as a space-separated string.

Here's an example usage:

```javascript
var alphabetPosition = require('./solution');

console.log(alphabetPosition(" j!}/-?:"));
console.log(alphabetPosition("?)_b/,q("));
```
The above code will convert the given texts to their corresponding alphabet positions and log the results to the console.

## Credits

This project was developed by [MysteriousMagenta]('https://www.codewars.com/users/MysteriousMagenta).

## License

This project is licensed under the MIT License.

## Badges

![badmath](https://img.shields.io/github/languages/top/lernantino/badmath)

## Features

    Converts text to alphabet positions.
    Handles both uppercase and lowercase letters.

## How to Contribute

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

    Fork the repository.
    Create a new branch for your feature or bug fix.
    Make the necessary changes and commit them.
    Submit a pull request describing your changes.

## Tests

To run the tests for this project, execute the command ```npm test``` in the project directory. The tests are defined in the solution.test.js file and use Jest as the testing framework.