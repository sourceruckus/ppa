This is the PPA repository for the Source Ruckus project.

To add it to your system:

    wget -qO- https://sourceruckus.github.io/ppa/sourceruckus.key | sudo apt-key add -
    source /etc/os-release
    echo "deb https://sourceruckus.github.io/ppa ${VERSION_CODENAME} main" \
        | sudo tee /etc/apt/sources.list.d/sourceruckus.list
