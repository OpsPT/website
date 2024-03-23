# Get started

OpsPT is community-driven apt repository for sre/devops tools.

## Installation

To install OpsPT run the following commands:
```sh
sudo wget -O /etc/apt/trusted.gpg.d/opspt-pubkey.gpg https://opspt.org/opspt-pubkey.gpg
echo "deb https://pkgs.opspt.org/ $(lsb_release -cs) main" | sudo tee -a /etc/apt/sources.list.d/opspt.list > /dev/null
sudo apt update
```

## Usage

To use OpsPT run the following commands:
```sh
sudo apt install <package>
```

To get a list of available packages you can consult this page: [Available packages](/available-packages.md)
