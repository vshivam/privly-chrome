## About ##

Privly is a developing set of browser extensions and applications for usable internet content privacy. It allows users to view content on any website, without the host site being able to read the content. The Privly extensions support "Injectable Applications" (also known as Privly Applications), which are web applications viewed within the context of other web applications. These applications can be any web application, but they are generally oriented to supporting a privacy use case.

For more information on what Privly is, [read about us](https://priv.ly/pages/about).

## About this Repository ##

This repository is oriented to cross-platform development of "Injectable Applications," which are web applications viewed within the context of other web applications. Use cases of Injectable Applications include:

* **Injection into a host page:** When a user encounters a Privly-type URL on a web page, it is injected in-place.
* **Generation of a new link:** The extensions and content servers both provide the ability to generate a new link for posting to host pages.
* **View without an Extension:** Servers storing content for the applications will host the applications remotely for times when the user does not have an extension.

The two current injectable applications are found in the PlainPost and ZeroBin folders. They are currently bundled into the [Google Chrome Extension](https://github.com/privly/privly-chrome), but they have not been unified with the versions found in the [content server](https://github.com/privly/privly-web)  

Next steps for this repository: this repository is the exact same code as found in the injectable application direction of the Google Chrome extension. We are presently working to make these applications cross-platform so that they can more easily be imported into any extension framework or server platform.

**For more information** on developing for this repository, read development.md in this directory.

## Testing/Submitting Bugs ##

If you have discovered a bug, only [open a public issue](https://github.com/privly/privly-web/issues/new) on GitHub if it could not possibly be a security related bug. If the bug affects the security of the system, please report it privately at [privly.org](http://www.privly.org/content/bug-report). We will then fix the bug and follow a process of responsible disclosure.

## Developer Documentation ##

Discussion of system concepts and high level processes are found in the [central wiki](https://github.com/privly/privly-organization/wiki).

## Resources ##

[Foundation Home](http://www.privly.org)  
[Privly Project Repository List](https://github.com/privly)  
[Development Mailing List](http://groups.google.com/group/privly)  
[Testing Mailing List](http://groups.google.com/group/privly-test)  
[Announcement Mailing List](http://groups.google.com/group/privly-announce)  
[Central Wiki](https://github.com/privly/privly-organization/wiki)  
[Submit a Bug](http://www.privly.org/content/bug-report)  
[IRC](http://www.privly.org/content/irc)  
[Production Content Server](https://privlyalpha.org)  
[Development Content Server](https://dev.privly.org)  
[Download Extension](https://priv.ly/pages/download)  

## Contacts ##

**Email**:  
Community [the 'at' sign] privly.org  

**Mail**:  
Privly  
PO Box 79  
Corvallis, OR 97339 
 
**IRC**:  
irc.freenode.net #privly

**Issue Queue**:  
If you open a bug on this repository, you'll get someone's attention.
