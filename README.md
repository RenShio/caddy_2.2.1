
 ```
  curl -fsSL https://get.docker.com -o get-docker.sh  && \
  bash get-docker.sh
 ```
```
sudo docker run -d --rm --name v2ray -p 443:443 -p 80:80 -v $HOME/.caddy:/root/.caddy  pengchujin/v2ray_ws:0.11 YOURDOMAIN.COM V2RAY_WS 0890b53a-e3d4-4726-bd2b-52574e8588c4 && sleep 3s && sudo docker logs v2ray
```
```
sudo docker logs v2ray
```
```
sudo docker stop v2ray
```
