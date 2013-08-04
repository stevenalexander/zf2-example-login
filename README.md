## Zend Framework 2
# Login Example

## Introduction

This is an example application for testing login using the standard Zend AuthenticationService, slightly customised Zend\Authentication\Storage for session storage and Zend\Authentication\Adapter\DbTable for DB auth.

The code is based from [samsonasik's blog](http://samsonasik.wordpress.com/2012/10/23/zend-framework-2-create-login-authentication-using-authenticationservice-with-rememberme/), so all credit to him. Recommend you read this for details.

## Setup

1. `git clone https://github.com/stevenalexander/zf2-example-login.git`
2. `composer install` to get dependencies
3. Create db with table `users`, containing columns `username` and `password`, populate with test user rows
4. Update config/autoload/global.php and config/autoload/local.php with your db connection details
5. Go to /auth to login
