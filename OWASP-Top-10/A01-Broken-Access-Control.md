# Broken Access Control

## Description
Occurs when users can perform actions outside their intended permissions.

## Example
User changes:

/profile?id=123

to

/profile?id=124

and accesses another user's data.

## Prevention
- Server-side authorization checks
- Role-based access control
- Principle of least privilege
