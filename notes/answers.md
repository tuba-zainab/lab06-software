# Difference between apt update and apt upgrade

The apt update command downloads the latest package information from the configured repositories. It does not install or upgrade software. 
The apt upgrade command installs newer versions of pacages that are already installed on the system. 
We should run sudo apt upgrade first so that the package manager has the latest information. 
After that, we can run sudo apt upgrade to apply the available upgrades. 
