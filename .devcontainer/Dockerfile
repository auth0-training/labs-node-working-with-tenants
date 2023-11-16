# See here for image contents: https://github.com/devcontainers/images/blob/22ce794a06cb34e12674d6aaf5e4549f6ab8ee4e/src/javascript-node/.devcontainer/Dockerfile

# [Choice] Node.js version: 18, 20
ARG VARIANT="latest"
FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:${VARIANT}

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>

# [Optional] Uncomment if you want to install an additional version of node using nvm
# ARG EXTRA_NODE_VERSION=10
# RUN su node -c "source /usr/local/share/nvm/nvm.sh && nvm install ${EXTRA_NODE_VERSION}"

# [Optional] Uncomment if you want to install more global node modules
 RUN su node -c "npm install -g --slient npm parcel-bundler concurrently eslint prettier"
