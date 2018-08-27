# backend
1. VPS 
2. Docker + K8s (cf. https://ninetaillabs.com/setting-up-a-single-node-kubernetes-cluster/ )
3. Create Redis volume claim + Redis Pod 
4. Create Flask pod + service 
5. Ingress Controller - Traefik or Nginx --> the easiest
6. Create Tor proxy + python crawler pod 
7. Wait for tor, check logs to see
8. Run a redis-cli container inside redis pod and aliment the db
