# Sign In / Sign Up

Animated sign in / sign up page with a password recovery view and live form validation. Built with plain HTML, CSS and vanilla JavaScript, with no framework and no dependency.

## Features

- **Sign In / Sign Up** on one card, with a sliding overlay animation to switch between the two forms.
- **Live form validation** with clear error messages:
  - email format check
  - name: at least 2 characters
  - password: at least 8 characters, with a lowercase letter, an uppercase letter and a number
  - password strength label (acceptable, good, strong)
- **Forgot password view** with three recovery methods: email, phone number (SMS) or security questions. The matching input appears depending on the chosen method.
- **Dark theme** with a neon green accent.
- **Accessible details**: `aria-live` error messages, `aria-invalid` on invalid fields, visible focus outlines.

## Getting started

No installation needed.

```bash
git clone https://github.com/Amineloussif69/sign-in-sign-up.git
cd sign-in-sign-up
```

Then open `index.html` in your browser.

## Project structure

```text
sign-in-sign-up/
├── index.html   # markup and JavaScript (validation, view switching)
├── styles.css   # styles, animations and theme
└── README.md
```

## Important note

This is a **front-end demo**. There is no server: submitting a form only shows a message (`alert`), and no data is sent or stored. To use it in a real application, you would need a backend that checks the credentials and stores passwords as salted hashes.

## Ideas for improvement

- Connect the forms to a backend (Node.js, Flask, ...).
- Add a "show / hide password" button.
- Add a French / English language switch (the recovery view is in French, the rest is in English).
- Implement the "security questions" recovery step.
- Make the layout fully responsive on small phones.

## Author

Amin Loussif ([@Amineloussif69](https://github.com/Amineloussif69))
