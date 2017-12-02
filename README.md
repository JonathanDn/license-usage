# license-usage
A project license usability scanner with user friendly reports

To use the scanner all you need to do is clone this repository, take the licenseUsability.js file and put it within a shared folder in your root directory --> this is the desired spot for the scanner to work properly.

Within your scripts key in package.json you can write a custom script named "scanLicenses" for example and when run, execute the licenseUsability.js file to receive a colorful and user friendly report of your package.json, dependencies & devDependencies licenses status.

In this report you will get a recommendation according to the licenses recognized by the software by the following rules:
- green - This is a license you can use for a commercial software.
- red - Either you did not enter a license to your repository package.json or a dependency's license is not recommended to use as part of commercial efforts.
- yellow - The system was not able to recognize the license --> this is your time to open an issue if there is a license you want me to classify and add to the scanner or any other issues you find with the software.

If you encounter any issues, have any feature suggestions feel free to open an issue, whenever I get the time I will improve this library :)
