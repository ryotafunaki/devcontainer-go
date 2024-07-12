# Go Dev Container Repository

This repository is a Dev Container for Go.

## Overview

| Type | Summary |
| --- | --- |
| Base image and tags | golang:*tag* |
| Target platform | linux/x64, linux/arm64 |
| Container registry's URL | https://hub.docker.com/r/ryotafunaki/devcontainer-go/ |
| Installed packages | .NET SDK 8.0, Kiota[^1] |

[^1]: Kiota supports version Golang 1.20 and later.  
      See https://learn.microsoft.com/en-us/openapi/kiota/quickstarts/go#required-tools

## How to use

Run it on the following platforms:
- Visual Studio Code
- GitHub Codespaces

> [!IMPORTANT]  
> This image is a personal dev container.  
> You can take a look at the Dockerfile and use it if you think it suits your use.
