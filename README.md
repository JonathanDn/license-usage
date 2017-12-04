# license-usage
A project license usability scanner with user friendly reports

<img src="https://media.giphy.com/media/3ohs7JGttrIkPgGuGc/giphy.gif" width="500px" height="500px">

## Usage:
1. Copy the licenseUsability.js file to project, within your root place it inside a folder(prefferably Shared or Public).

2. Create a new js file within your root, call it "testLicense.js" for example, within it you need to require the licenseUsability file, and invoke the function that returns with no arguments.

3. You can easily run "node testLicense" || "npm testLicense" || "yarn testLicense" according to your package manager.

## Conventions:
- green - This is a license you can use for a commercial software.
- red - Either you did not enter a license to your repository package.json or a dependency's license is not recommended to use as part of commercial efforts.
- yellow: The system was not able to recognize the license --> this is your time to open an issue if there is a license you want me to classify and add to the scanner or any other issues you find with the software.

### Notes & Feedback
Package.json in the project is just for quick testing

If you encounter any issues, have any feature suggestions feel free to open an issue, whenever I get the time I will improve this library :)

Disclaimer: Information represented by this package scanner is gathered from general sources. No information on licenseUsage is considered as legal advice.
