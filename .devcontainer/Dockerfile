FROM mcr.microsoft.com/vscode/devcontainers/dotnet:0-6.0

# Install Azure CLI
ARG INSTALL_AZURE_CLI="true"
COPY library-scripts/azcli-debian.sh /tmp/library-scripts/
RUN if [ "$INSTALL_AZURE_CLI" = "true" ]; then bash /tmp/library-scripts/azcli-debian.sh; fi \
    && apt-get clean -y && rm -rf /var/lib/apt/lists/* /tmp/library-scripts