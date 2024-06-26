# LenoxGlobe Security Policy

## Supported Versions

LenoxGlobe utilizes a "rolling-release" model, in which the latest improvements, bug fixes and security improvements are incorporated into the latest version of the software, with these updates occasionally being rolled into a "stable" channel with a numbered version that follows semantic versioning rules.

We expect that all users of the software, if they are interested in taking advantage of the latest bug and security fixes, remain up-to-date with the latest version of the software. Older versions of either release channel of the software are not officially supported or maintained.

| Version | Supported          |
| ------- | ------------------ |
| Latest Stable Version   | :white_check_mark: |
| Latest Rolling Release Version   | :white_check_mark:                |
| Older Versions   | :x: |

## Reporting a Vulnerability

LenoxGlobe utilises code scanning via GitHub Actions and various checks from our development team to keep our software as secure as possible for our users, however, no software is perfect.

We do not have a formal bug bounty program. We recommend sending an email to [security@lenoxglobe.com](mailto:security@lenoxglobe.com) to disclose any security vulnerabilities you discover in LenoxGlobe.

## In Scope

LenoxGlobe uses several pieces of upstream software as part of our project's operation. If the security issue being reported is relevant to one of those tools, you should contact the maintainers of that piece of software directly to work toward a resolution, then follow up with our team to inform us when a fix is available that we should incorporate into our software.

You can report any vulnerabilities directly to us if they relate to the core LenoxGlobe application or any of the repositories we maintain here: https://github.com/orgs/LenoxGlobe/repositories

## Out of Scope

LenoxGlobe is not responsible for the development or maintenance of several pieces of "upstream" software that we incorporate into our own product. This list of software includes, but is not limited to:
 - GoLang
 - Caddy
 - PostgreSQL
 - Redis
 - VueJS and several frontend dependencies

If you identify a security issue with any of those pieces of software, we encourage you to report it to them directly. If the issue also affects LenoxGlobe's implementation of the software, please let us know if and when a resolution is available so that we can update our own software to incorporate the fix.
