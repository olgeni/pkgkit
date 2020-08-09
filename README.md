# Create package directories

    poudriere bulk -j 121amd64 -z   x11 -p default ports-mgmt/pkg
    poudriere bulk -j 121amd64 -z nox11 -p default ports-mgmt/pkg
