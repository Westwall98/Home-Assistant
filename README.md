# Home-Assistant


# Docker

docker run -d --restart=always --name="home-assistants" -e "TZ=Asia/Shanghai" -v /data/homeassistant/config:/config --net=host homeassistant/home-assistant:latest

# Install HACS

docker exec -it homeassistant bash

wget -O - https://get.hacs.xyz | bash -
