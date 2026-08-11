# Contributing to PAN-OS Unused Object Analyzer

Thank you for your interest in contributing to this project. 

## How to Contribute
* **Bug Reports:** Please open an issue detailing the unexpected behavior. Include the browser version and a sanitized snippet of the configuration that caused the issue. Do not post sensitive firewall configurations.
* **Feature Requests:** Open an issue to discuss the feature before submitting a pull request.
* **Pull Requests:** Ensure your code is contained within the single `pan_analyzer.html` file to maintain the zero-dependency architecture.

## Code Standards
* Maintain vanilla HTML, CSS, and JavaScript.
* Avoid adding external libraries (no jQuery, React, etc.).
* Ensure the Web Worker logic remains intact to prevent main-thread blocking on large configurations.