# Senior Design - 4th United States Circuit Court of Appeals Scan Inventory

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Senior Design Project Number CS 21-326, developed by Benjamin Bricker, Rohit Morabkar, and Spencer Kinsey-Korzym under the guidance of Faculty Advisor Robert Dahlberg, Ph.D. and Mentor Bob Smith for the 4th United States Circuit Court of Appeals.

The 4th United States Circuit Court of Appeals requested a native iOS application to be developed to improve the functionality of their existing inventory web application on mobile devices. The existing web application was difficult to navigate on mobile devices and did not have a public API for interacting with the existing database. Therefore, the project aimed to provide a native application tailored for mobile devices, with an API that could be consumed by future applications.

The application's objective was to provide Court employees with a user-friendly method of looking up and verifying the status of inventory items. The app also integrated with the mobile device's built-in cameras to scan barcodes and reduce the need for additional devices.

The solution is a native iOS application written in an established web framework and translated into native code, which could later be deployed to Android devices or as a traditional web application. The middle tier, which provides access to the existing database, was designed to be consumed by multiple applications while providing security on all HTTP endpoints. The modular design of both elements leaves open the possibility of extending functionality in the future.

## Technologies

- iOS
- Angular
- Node
- REST

## Features

The Scan Inventory app has two major components:

### RESTful API

- Shares a similar language and file structure as the iOS app
- Provides secure authentication with the use of tokens
- Provides secure database interaction
- Interactive documentation of all endpoints
- Automated tests for all endpoints allow alterations with less chance of regression
- Automatically sends emails to the Custodial Officer when an asset update is requested or made
- Allows users to search for assets by a wide array of parameters

### iOS Application

- Allows pre-existing users to log in
- Users can search for specific items by barcode or filter queries by many asset properties
- Assets can be updated through the app
- One or more assets can be verified by use of the user interface or by scanning barcodes
- Users are notified in the app if the location of an item being verified has changed

## Installation/Usage

The Scan Inventory app is not publicly available for usage.

## License

This project is licensed under the terms of the MIT license. See the [LICENSE](https://github.com/huhu72/senior-design/blob/main/LICENSE) file for details.
