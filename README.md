# Home-Assistant


# Docker

docker run -d -p 8123:8123 -v /root/homeassistant:/config homeassistant/home-assistant:latest

# Install HACS

docker exec -it homeassistant bash

wget -O - https://get.hacs.xyz | bash -
