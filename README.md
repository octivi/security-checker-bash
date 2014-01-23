Octivi - Security Checker
======================================

Simple bash tool for Sensio Security Advisories Checker.

Fits great with your Continous Integration as it returns exit code 1 if security check fails.

## Usage

    $ security-checker [composer_lock_path] [sensio_checker_url]
    
The basic way to use is just simple:

    $ security-checker
    
which assigns:

* `composer_lock_path` to composer.lock
* `sensio_checker_url` to https://security.sensiolabs.org/check_lock