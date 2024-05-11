This is the PPA repository for the Source Ruckus project.

To add it to your system:

    wget -qO- https://sourceruckus.github.io/ppa/sourceruckus.key \
        | sudo tee /etc/apt/trusted.gpg.d/sourceruckus.asc
    source /etc/os-release
    echo "deb [arch=amd64] https://sourceruckus.github.io/ppa ${VERSION_CODENAME} main" \
        | sudo tee /etc/apt/sources.list.d/sourceruckus.list
