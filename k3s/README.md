# K3S 
https://k3s.io/

## Install
  
  curl -sfL https://get.k3s.io | sh -

## Install withouth Traefik
  curl -sfL https://get.k3s.io | sh -s - --disable=traefik

## tokens location

    /var/lib/rancher/k3s/server/node-token

## Install on worker

curl -sfL https://get.k3s.io | K3S_URL=https://myserver:6443 K3S_TOKEN=mynodetoken sh -

    --with-node-id