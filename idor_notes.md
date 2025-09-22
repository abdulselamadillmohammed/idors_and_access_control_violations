# STARBUCKS SG IDOR TESTING

// https://www.starbucks.com.sg/

## Pointers (things to look into later on)

// Use burp suite and perform general query on entire domain
// Look for missing CSRF Token misuse/missing on different pages while tesing endpoints

// Check jwt token methodology -> HS256 could be configured with a bad key.. ie easy to brute force symeteric key

// Key vulnerability => Session token not containing an HTTP only flag
// -> XSS might be possible

// Check access_token's payload on burp and look for identifiers

## Accounts
