## Quick Start

Start using this template following these steps:

- Clone the repository

```bash
git clone https://github.com/Zibait-it/landing-page-challenge.git
```

- Install proyect dependencies with npm

```bash
npm install
```

## Files Directory

- `styles.css` is the output file once you run the build scripts. This file needs to be linked in all the HTML files you create.

```html
<link href="css/styles.css" rel="stylesheet" />
```

- `index.html` is the starting file. You can create all the HTML files you need but don't forget to link the output css file.

## Live Changes

In order to see the live changes, I recommend to use the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension. Once you have a server running, you need to write `npm run watch` on your project terminal. This script is going to refresh the output css file to show the latest changes.

## Finish For Production

Once you finished your project, you can use the `npm run prod` script. This will minify your CSS file for production.
