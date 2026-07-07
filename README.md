# Secure Login Form Clone

## Overview
This repository contains a basic front-end login form designed to mimic the OWASP Juice Shop login interface. It was created to demonstrate secure coding practices, specifically focusing on input validation.

## Features
* **HTML5 Form:** Clean and accessible markup.
* **Client-Side Validation:** JavaScript intercepts form submission to ensure:
  * No fields are left empty.
  * The email address contains an `@` symbol.
  * The password is at least 8 characters long.

## Security Considerations
While this form includes client-side validation to improve user experience, **client-side validation is not a security boundary.** An attacker can easily bypass JavaScript checks using tools like Burp Suite or by simply disabling JS in their browser. Therefore, this front-end must be paired with robust **server-side validation** and parameterized database queries to prevent attacks like SQL Injection.
