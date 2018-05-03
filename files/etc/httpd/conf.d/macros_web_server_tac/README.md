
Common macros for Apache.

More than a bit sparse for the moment, as a number of my web servers' macros use values have the following problems with immediate adaptation to a public repository:

* The macros currently contain sensitive hard-coded values. For example, my web server's LDAP authentication macro accepts an argument for different groups but contains hard-coded LDAP values that didn't need to vary between VirtualHost definitions.
* The macros may be better off left until I learn templates (at which point they may not even be macros).
