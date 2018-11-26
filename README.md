# ChromeExtensionTemplate

This is a simple Chrome extension template project in Visual Studio 2017.
It does not contain any refrences to 3rd party components and frameworks.
The project is intended as a basic starting point for a Chrome extension
if you are going to develop iot in Visual Studio.

## How to use the project

You can use the solution and its project directly and start adding code and references.
Or, you can create a template using it. To do that, build it and copy the 
`ChromeExtensionTemplate.zip` file from the `bin` folder into your 
`\Users\{your_user}\Documents\Visual Studio 2017\Templates\ProjectTemplates\` folder. 
From then on, you will have the Chrome Extension Template as an option in 
New Project dialog.

### Start using the template

After you create a new project using the template, you need to:
1. Change the `manifest.json` file.
2. Add your business logic to popup.html, popup.js, and baackground.js.
3. Add more files as needed.
4. To run the extension
    - Open Chrome and navigate to [chrome://extensions](chrome://extensions),
    - Enable `Developer mode`,
    - Click `Load Unpacked` and point to the folder with the manifest file.

## History

For changes in this project, check the Commits tab on GitHub.

## Contribute
Check out the [contribution guidelines](CONTRIBUTING.md)
if you want to contribute to this project.

For cloning and building this project yourself, make sure ...

## License
This software is provided under a [MIT License](LICENSE.md)

## Notes

This project uses ideas from Mads Kristensen's template for Visual Studio 2015.
Thank you, Mads!