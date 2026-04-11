# Feature: User Login

## User Story

As a user, I want to log into the system, so that I can access my personal tasks.

## Acceptance Criteria

### AC1

Given a registered user
When valid email and password are provided
Then the system returns success

### AC2

Given a registered user
When incorrect password is provided
Then the system returns error

### AC3

Given login form
When input fields are empty
Then validation errors are returned
