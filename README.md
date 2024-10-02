# dns-bezan

`dns-bezan` is a simple command-line tool for changing DNS settings on Ubuntu systems. This tool is particularly useful for users in Iran who need to bypass restrictions imposed by sanctions on web services.

## Available DNS Servers

The script sets the DNS to well-known DNS servers that help users access web services that might otherwise be blocked or restricted:

- **electro**: 78.157.42.101, 78.157.42.100
- **403**: 10.202.10.202, 10.202.10.102
- **shecan**: 178.22.122.100, 185.51.200.2
- **begzar**: 185.55.226.26, 185.55.226.25

## Usage

To change the DNS settings, simply run the script with one of the predefined options:

```bash
sudo dns-bezan electro

