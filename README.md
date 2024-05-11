This is the PPA repository for the Source Ruckus project.

To add it to your system:

    wget -qO- https://sourceruckus.github.io/ppa/sourceruckus.key \
        | sudo tee /etc/apt/keyrings/sourceruckus.asc
    source /etc/os-release
    echo "deb [arch=amd64 signed-by=/etc/apt/keyrings/sourceruckus.asc] https://sourceruckus.github.io/ppa ${VERSION_CODENAME} main" \
        | sudo tee /etc/apt/sources.list.d/sourceruckus.list
