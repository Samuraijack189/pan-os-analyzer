# PAN-OS Unused Object Analyzer

A purely client-side, browser-based utility designed to help network administrators identify and clean up unreferenced objects (addresses, services, groups) within Palo Alto Networks Panorama or NGFW configurations. 

## Features
* **Zero Dependencies:** Runs entirely in the browser using HTML, CSS, and vanilla JavaScript.
* **Dual Input Methods:** Supports uploading a Panorama `.xml` export file or pasting PAN-OS `set` commands directly.
* **Smart Detection:** Automatically ignores built-in PAN-OS objects (e.g., `any`, `trust`, `application-default`) to prevent false positives.
* **Actionable Output:** Generates exact CLI `delete` commands for unused objects.
* **Bulk Export:** Select specific unused objects and download their respective delete commands as a `.txt` file.
* **Privacy First:** All parsing and processing happen client-side. No configuration data is ever sent over a network.

## Quick Start
1. Download or clone this repository.
2. Open `pan_analyzer.html` in any modern web browser.
3. Upload your `.xml` configuration export or paste your `set` commands into the input area.
4. Click **Analyze** to generate a list of unused objects and their corresponding `delete` commands.
