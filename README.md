# Alpine Node MongoDB Docker Image

This is fork of [pitzcarraldo/alpine-node-mongo](https://hub.docker.com/r/pitzcarraldo/alpine-node-mongo) with specific modifications for use with [mongodb-memory-server](https://github.com/nodkz/mongodb-memory-server)

This image already has the **MONGOMS_SYSTEM_BINARY** environment variable set so that it will work with
mongodb-memory-server right out of the box.

Perhaps the greatest advantage of using the system binary is that even your first test run (with no cache) will be fast
since the binaries are already installed.
