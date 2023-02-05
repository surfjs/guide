# Configuration Files
Once you [create your folder](https://www.youtube.com/watch?v=l6Y6yDkLAEc), the next step is to start coding and create your program! Let's start by creating your package.json and main file for your application.

As we explained in ["What is `package.json`?"](https://github.com/surfjs/guide/blob/main/guide/basic-information/WHAT-IS-PACKAGE.JSON.md) section, package.json is essentially the central of your folder. It contains the name of your project, version, and the packages installed, hence the name "`**package**.json`". Same for "`**package**-lock.json`", when you install a package that file is added and will contain all information about the package(s) installed.

There's more information about packages [here](https://docs.npmjs.com/cli/v6/configuring-npm/package-json/).

## Creating package.json
The first step after creating your folder is to create your `package.json`, and the first step in doing that is opening your terminal and using npm
```js
// To go through the full process of developing the file do this
npm init
// If your wanting a pre-setup file do this
npm init -yes
```
Then, if your going to install a package (like Surf) `npm i surf`

Once you've finished the setup be sure to check your files in-case something didn't load correctly.
