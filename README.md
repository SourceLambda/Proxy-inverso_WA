# Proxy-inverso_WA


docker build -t sourcelamda_proxy_wa . 
docker run -p 80:80 sourcelamda_proxy_wa

Para correr el SSL toca con:
docker run -p 443:443 sourcelamda_proxy_wa
