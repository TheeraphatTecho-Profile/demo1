# Email Validation Project

## Project Overview
This project contains a simple email validation function written in JavaScript. The purpose is to demonstrate basic email format validation using regular expressions.

## Files
- `validate.js` - Main JavaScript file containing the email validation function

## Functionality
The project includes:
- `validateEmail(email)` function that validates email format using regex pattern
- Test cases demonstrating the function with valid and invalid email addresses

## Last Updated
**Date:** March 23, 2026  
**Time:** 10:42 UTC+07:00

## How to Use
1. Open `validate.js` in a JavaScript environment
2. Call the `validateEmail()` function with an email string as parameter
3. The function returns `true` for valid emails and `false` for invalid emails

## Example Usage
```javascript
console.log(validateEmail("example@example.com")); // Returns: true
console.log(validateEmail("invalid-email"));      // Returns: false
```

## Update Log
- **March 23, 2026, 10:42 UTC+07:00** - Initial project setup with email validation function

## Future Enhancements
- Add more comprehensive email validation rules
- Include unit tests
- Add support for international email formats
