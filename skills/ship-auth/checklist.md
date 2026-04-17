# ship-auth checklist

Use this checklist after generating or updating the authentication flow.

## Core pages
- sign up page exists
- sign in page exists
- forgot password page exists
- email verification flow exists
- protected page example exists

## Flow quality
- navigation between auth pages is clear
- success and error states are shown
- protected routes are actually protected
- auth state is handled consistently

## Project safety
- unrelated pages were not broken
- missing environment variables are clearly marked
- provider credentials are not hardcoded
- manual setup steps are documented

## Final review
- explain what was added
- explain what still needs manual setup
- explain how to test the auth flow
