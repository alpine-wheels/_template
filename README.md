# Alpine Wheels template repository

Use this repository as a starting point for a new package that you want to include in the Alpine Wheels package index.

### Usage

1. Update `requirements.txt` with the package name and version of the package you want to build.
2. Update `build.sh` to include any OS packages that are required for the package to build.
3. Run `docker-compose up` to verify that the package builds correctly.

If everything went well, there will be a single `*.whl` file in the repository directory.
