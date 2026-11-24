# Password Generator Application React

## Overview
This is a simple web application which can be used by a user to generate random strings that can be used as a password when signing up for a service.<br>
The user can change the desired password length using the slider and whether the password will include numbers and symbols using the checkboxes.<br>
The web application has a strength meter to evaluate the strength of the password output, along with a dialogue box recommending the user selects at least one of numbers or symbols to include if none are currently selected.<br>
There is also functionality to copy the generated password to the user's clipboard at the push of a button, with the program highlighting the text to show this has occurred.<br>
User experience was a key consideration when building this project.<br>
This project was made using the Vite framework with Tailwind CSS.<br>
A preview of what this project looks like when deployed can be viewed on Vercel at this link: https://password-generator-adam-woollett.vercel.app/

## Tech Stack
- React.js
- Vite
- HTML5
- Tailwind CSS

## Project Structure
```
Password-Generator-Application-React/
└─public/
├    ├─ favicon.svg
├    └─ icons.svg
└─src/                                        # Components used to build the page and make it functional.
├    ├─ App.css
├    ├─ App.jsx
├    ├─ PasswordGeneratorWithCustomHook.jsx   # React component that contains page HTML, calls the password generation component and contains copying to clipboard functionality.
├    ├─ index.css
├    ├─ main.jsx
├    └─ usePasswordGenerator.jsx              # Password generation component that contains the logic for generating the random password.
├─ README.md
├─ eslint.config.js
├─ index.html
├─ package-lock.json
├─ package.json
└─ vite.config.js
```
