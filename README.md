# deb-dhis2-tools
Files for building dhis2-tools.
Built using this [repo](https://github.com/dhis2/dhis2-tools).

##Requirements
* debian based distro
* packaging-dev (if building with debuild)

##How to run
### Debian Packaging
`debuild -us -uc` for unsigned deb.

`debuild -S` for signed deb.

