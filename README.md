# myDotnetDoc
A repo to store the commands that I use the most with dotnet.


## Comand to verify the dotnet version and to install it in Linux distro.
dotnet --version

### Download the script:
wget https://dot.net/v1/dotnet-install.sh -O dotnet-install.sh

### Grant the permisions:
chmod +x ./dotnet-install.sh

### Install the latest release:
./dotnet-install.sh --version latest

### Install the runtime:
./dotnet-install.sh --version latest --runtime aspnetcore

### Enable .NET on the command line:
export DOTNET_ROOT=$HOME/.dotnet
export PATH=$PATH:$DOTNET_ROOT:$DOTNET_ROOT/tools

### Check the sdk installed:
dotnet --list-sdks