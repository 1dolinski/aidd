# aidd

![aidd logo](https://i.imgur.com/P3AGHEp.png)

**AI Driven Development** (Test Driven, Benchmark Driven, Design System Driven, I/O Driven)  

---

## Overview

**aidd** empowers developers to focus on critical **requirements** while automating the rest. You provide **hard requirements**—whether they are **test requirements, benchmarks, design systems, or I/O specifications**—and aidd fills in the gaps. This system accelerates development by ensuring components and code are generated with precise input and output definitions.

---

## Key Features

- **AI-Driven Development**: Focus on defining requirements; let AI handle the implementation.
- **Test-Driven Development (TDD)**: Write tests, and aidd will generate code that passes them.
- **Benchmark-Driven**: Set performance goals, and aidd ensures the generated code meets or exceeds them.
- **Design System Integration**: Provide design system specifications for seamless UI component development.
- **Input/Output Requirements**: Define inputs and outputs to generate components or APIs with proper parameter handling.

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd aidd
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development environment:
   ```bash
   npm start
   ```

---

## How to Use

1. **Define Requirements**  
   Provide your requirements using one of these methods:
   - **Test Requirements**: Create unit tests or test suites for the intended functionality.
   - **Benchmarks**: Specify benchmarks that your code or components should meet.
   - **Design System Parameters**: Provide design system rules (like colors, typography, component structure).
   - **I/O Specifications**: Outline input and output parameter behavior for APIs or components.

2. **Run aidd**  
   Use aidd to generate the code based on your provided requirements:
   ```bash
   npm run aidd
   ```

3. **Refinement**  
   Review the generated code and make refinements if necessary. Rerun benchmarks or tests as needed.

---

## Example Usage

### Test-Driven Requirement Example:
1. Create a test file:
   ```javascript
   // test/sum.test.js
   const sum = require('../src/sum');
   test('adds 1 + 2 to equal 3', () => {
     expect(sum(1, 2)).toBe(3);
   });
   ```

2. Run aidd:
   ```bash
   npm run aidd
   ```

3. The `sum.js` function will be generated to pass the above test:
   ```javascript
   // src/sum.js
   function sum(a, b) {
     return a + b;
   }
   module.exports = sum;
   ```

---

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch:  
   ```bash
   git checkout -b feature-branch-name
   ```
3. Make your changes and commit them:  
   ```bash
   git commit -m "Add new feature"
   ```
4. Push your changes:  
   ```bash
   git push origin feature-branch-name
   ```
5. Create a Pull Request.

---

## Wishlist
[done] Create Open Source package
[done] Create logo and REAMDE
[ ] figure out the ideal flow for each

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For questions or issues, please open an issue on the repository or reach out to the project maintainers.

---

**AI development made easy: Focus on requirements, let aidd do the rest!**
