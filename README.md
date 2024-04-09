# SVGLogoMaker

## Description

This application was built as tool for anybody to create simple logos. It uses inquirer to prompt the user within the command line for how they would like their logo to look, allowing them to choose color, shape, and 3 characters to id their logo as a signature. Once all inputs are met, the user will be presented with an SVG file.

## Installation

1. Clone the repo:
   git clone https://github.com/Wormhole616/SVGLogoMaker.git

2. Open in VS Code. If you do not have VS code you must install it.

3. Using the terminal, install node.js v16. If you have homebrew, the command should look like the following (brew install node@16), however this may vary and the documentation should be consulted.

4. Once node.js v16 is installed, in the terminal, utilize the command npm init -y to initialize and create a package.json where project files will be stored.

5. Next, use the terminal to run the command npm i to install the dependencies associated with this application (developers may need to install inquirer and jest directly from the command line, to do so the command for inquirer will be npm i inquirer@8.2.4 to install v8.2.4 of the inquirer, and npm i jest to install the latest version of jest).

6. To run the application, within the terminal, type the command node index.js.

## Credits

Gustavo Duque

## Usage Information

To run this application, use the command line, install all dependencies-- then type the command node index.js. You will then be presented with a series of questions. Once all questions have been answered, a message will display indicating you that your logo has been generated.search for newly generated SVG file.



https://github.com/Wormhole616/SVGLogoMaker/assets/144727575/fa672ca3-c267-48df-96d2-cdbf3103caf0



For unit testing instructions, navigate to the Test Instructions section.


## Contribution Guidelines

Open to collaboration, if you choose to do so open an issue and modify any changes you would like to see on a feature branch and wait for approval before merging to the main branch.

## Test Instructions

To run unit testing, open the terminal, and use the command npm run test.

As of now there is one test suite with three tests. The test suite is checking for a render() method to return a string for the corresponding SVG file with the given shape color.
