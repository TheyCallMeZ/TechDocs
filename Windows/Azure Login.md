This was discovered when using JetBrains Rider and debugging an API that used Azure KeyVault.

This applies to MacOS and Linux as well.

Windows: [Install Azure CLI for Windows](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows?tabs=azure-cli)\
MacOS: [Install Azure CLI for MacOS](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-macos)\
Linux: [Install Azure CLI for Linux](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-linux?pivots=apt)

You will then want to perform an interactive Login:

``az login``

-OR-

for those Brave (or stupid) enough you can supply your credentials on the command line.

``az login --user <username> --password <password>``

There are better ways to do terminal based login as well, For that please see the guide on [Microsoft Docs](https://learn.microsoft.com/en-us/cli/azure/authenticate-azure-cli-interactively)

If you intend to use the Azure CLI for more than just a login Microsoft has an [Onboarding Cheat Sheet](https://learn.microsoft.com/en-us/cli/azure/cheat-sheet-onboarding).
