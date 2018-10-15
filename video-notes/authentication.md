# Authentication

## Steps you take to access a system
- identification
  - make a claim
    - provide a username
- access control
  - authentication 
    - proof that you are who you claim to be
  - authorization
  
## Factors
- knowledge - something that you know
  - password
  - question
- token - something that you have
- biometrics - something that you are
  - fingerprint
  - iris

**Two/Multi factor** authentication is when methods from 2 *different* factors are used.

Sometimes, password + one time password can be better than 2-factor. Google authentication system has some a bug that allows you to get future codes on your phone if you change the time.

## Passwords

### The password problem

Humans are not particularly good at remembering lots of different passwords so they end up doing some of the following:
- reuse passwords
- use easily guessable passwords
- share passwords (with someone?)
- modified a password for re-use (i.e. when a service asks you to change it you just slightly change it?)
- write a password down (ok this is pretty bad)

### How secure is it?

A secure password has:
- min length
- special chars
- lowercase + uppercase
- numbers
- is not a common word
