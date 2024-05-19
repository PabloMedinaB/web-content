# Title

Web content used to deploy into an EC2 instance running Apache2 service.

## Install

```
#!/bin/sh

sudo apt update && sudo apt upgrade -y

sudo apt install -y apache2
sudo rm -f /var/www/html/index.html

sudo git clone https://github.com/PabloMedinaB/web-content.git /var/www/html/
```

## Usage

The following script must be copied when to User Data when deploying an instance or creating an EC2 template.

## Contributing

PRs NOT accepted.

## License

OS  @  Pablo Medina
