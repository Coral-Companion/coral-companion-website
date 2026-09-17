# Coral Companion Website

## Build
Styles are built using Tailwind CSS v4 engine. This setup completely bypasses traditional JavaScript configuration files, keeping all custom themes inside native CSS.

Therefore, follow these instructions.
1. Make sure you have [Node.js](https://nodejs.org) installed on your machine (v20 or higher recommended).
1. Install Dependencies
Run the following command to download and install the required packages (like the Tailwind CLI): ```npm install```
1. While writing code, run this command. It tells Tailwind to watch your HTML files and your `src/input.css` file. It will instantly regenerate the output CSS whenever you save a change ```npm run dev```
1. When ready to release, run the build command. This compiles CSS and automatically minifies it ```npm run build```
