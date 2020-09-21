# PiMOS

### Universal Monitoring System

1. Clone Clone Raspberry Pi OS to SD Card
   https://www.raspberrypi.org/downloads/

1. Set up headless Pi
   https://desertbot.io/blog/headless-raspberry-pi-4-ssh-wifi-setup

1. Install Docker & Docker Compose
   https://devdojo.com/bobbyiliev/how-to-install-docker-and-docker-compose-on-raspberry-pi

1. Update config file

    - ddclient / ddclient/config/ddclient.conf

    ```conf
    # /ddclient/config/ddclient.conf

    daemon=300
    protocol=dyndns2
    use=web
    server=domains.google.com
    ssl=yes
    login=username
    password='password'
    yourdomain.com
    ```

1. docker-compose up --build -d
