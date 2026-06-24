# SQL Injection

## Overview

SQL Injection (SQLi) is a web application vulnerability that allows attackers to interfere with the queries an application makes to its database.

## Impact

* Unauthorized data access
* Authentication bypass
* Data modification
* Remote code execution (in some cases)

## Types

### In-Band SQL Injection

* Error-Based
* Union-Based

### Blind SQL Injection

* Boolean-Based
* Time-Based

### Out-of-Band SQL Injection

## Example

Vulnerable Query:

SELECT * FROM users WHERE username='$user' AND password='$pass';

Example Payload:

' OR '1'='1

## Prevention

* Parameterized Queries
* Prepared Statements
* Input Validation
* Least Privilege

## References

* OWASP SQL Injection Guide

