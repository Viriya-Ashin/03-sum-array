# HTML Setup for Sum Array Application Testing

This HTML document is configured for testing a sum array application using Mocha and Chai.

- **Meta Tags**:
  - Sets character encoding to UTF-8.
  - Ensures proper rendering and touch zooming on mobile devices.
  - Specifies compatibility with the latest rendering engine for Internet Explorer.

- **Title**:
  - Sets the title of the webpage to "Sum Array".

- **External Resources**:
  - Links to the Mocha CSS stylesheet for test result styling.
  - Includes Mocha and Chai JavaScript libraries for testing functionality.

- **Body Content**:
  - Contains a div with the ID "mocha" for displaying Mocha test results.
  - Configures Mocha for Behavior-Driven Development (BDD) using `mocha.setup("bdd")`.
  - Includes JavaScript files for sum array functionality and corresponding tests.
  - Runs Mocha tests with `mocha.run()` to execute the test suite.

# JavaScript Sum Array Function

This JavaScript code defines a function `sumArray` that calculates the sum of numbers in an array.

- **Function Logic**:
  - Takes an array of numbers as input.
  - Initializes a variable `result` to store the sum.
  - Iterates through the array and adds each element to `result`.
  - Returns the final sum of the array elements.

- **Example Usage**:
  - Calling `sumArray([3, 1, 5, 6])` will return 15, which is the sum of 3, 1, 5, and 6.
