# nexus-2
wget -O docker_installer.sh https://raw.githubusercontent.com/wibucrypto2201/Docker_install/refs/heads/main/docker_installer.sh && chmod +x docker_installer.sh && ./docker_installer.sh \

docker pull inanitynoupcase/nexus_2:1.2.0 \
docker run -d --name nexus_1 --restart unless-stopped -e NODE_ID=<số> -p 9000:80 inanitynoupcase/nexus_2:1.2.0 \
