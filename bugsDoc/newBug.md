# Bug Report: Login button unresponsive on mobile

## Summary
The "Log In" button on the sign-in page does not respond to taps on mobile browsers.

## Environment
- Device: iPhone 14
- OS: iOS 26
- Browser: Safari

## Steps to Reproduce
1. Open the app's sign-in page on a mobile browser
2. Enter a valid email and password
3. Tap the "Log In" button

## Expected Result
The user is logged in and redirected to the dashboard.

## Actual Result
Nothing happens. No error message is shown and the page does not change.

## Severity
High: mobile users cannot log in.

## Possible Cause
A transparent overlay element may be covering the button on smaller screens.