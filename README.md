# archive-cli
KISS extract/compress easy to learn function

### About
Extract/Compress easy to learn function.
I complained against all the CLI commands on linux to compress / decompress files and folders.
So I've write scripts.

- One command to compress :`archive-create` (only 2 parameters available)

- One command to decompress/extract: `archive-extract`

The script take care of the file extension to call the good command.

### Install
### With APT (recommended)
    echo "deb http://packages.azlux.fr/debian/ buster main" | sudo tee /etc/apt/sources.list.d/azlux.list
    wget -qO - https://azlux.fr/repo.gpg.key | sudo apt-key add -
    apt update
    apt install archive-cli

### Manually
    you can use a simple `git clone`
