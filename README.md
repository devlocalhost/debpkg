# debpkg, a python script to retrieve information for a package from debian repos

using [sources.debian.org](https://sources.debian.org/api)

![img1.png](img1.png)

# why 2 files?

one file (debpkg) has color support, and the other (debpkgnc) doesnt have colors. the colors dont show anything about the package by the way, its based on the distro/repo type (red for experimental, yellow for testing and so on)

# requirements
+ requests, pip3install requests
+ colorhex (**IF** using debpkg), pip3 install colorhex