# C - For those in Hurry!

This is a sandbox development environment to follow the course on C. This repo is to be used in the form of GitHub Codespaces.

The idea is that the codespaces will have all the right tools already installed and we can thus focus on learning C and skip the hassle that comes as a result of environment setup.

# Local Development

Although, we encourage creating codespace using this repo and work within that, we understand that you may like to develop locally.

To be able to locally run the examples, we recommend using our docker image that already has all the tools installed as part of it.

Assuming you have docker desktop installed and docker command available as part of the commandline, use the following commands to get started:

```
docker run -it -v ~/Downloads/workspace:/home/pyjamacafe/workspace --name lab pyjamacafe/sandbox
```

This will pull the docker image and map the `~/Downloads/workspace` on your host to the `/home/pyjamacafe/workspace/` directory in the docker environment.

# Starting Docker

To start the container created above, use:
```
docker start lab
```

Once you have the container started, you can attach a terminal to it by using the following command:
```
docker attach lab
```

# Note:
- These commands are known to work on Mac and Linux.
- Windows users are on their own if they run into issues :)

# Copyrights
```
All rights reserved
```
