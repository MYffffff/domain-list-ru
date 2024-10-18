# GEOSITE.DAT

Geosite.dat generator

**Syntax:**

> The following types of rules are **NOT** fully compatible with the ones that defined by user in V2Ray config file. Do **Not** copy and paste directly.

* Comment begins with `#`. It may begin anywhere in the file. The content in the line after `#` is treated as comment and ignored in production.
* Inclusion begins with `include:`, followed by the file name of an existing file in the same directory.
* Subdomain begins with `domain:`, followed by a valid domain name. The prefix `domain:` may be omitted.
* Keyword begins with `keyword:`, followed by a string.
* Regular expression begins with `regexp:`, followed by a valid regular expression (per Golang's standard).
* Full domain begins with `full:`, followed by a complete and valid domain name.
* Domains (including `domain`, `keyword`, `regexp` and `full`) may have one or more attributes. Each attribute begins with `@` and followed by the name of the attribute.