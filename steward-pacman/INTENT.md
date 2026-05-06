Deploy the Pac-Man Node.js application.

- Namespace: steward-pacman
- Image: quay.io/rh_ee_cschmitz/pacman:green (Node.js 20, port 8080)
- Deployment named "pacman", 3 replicas
- Service: ClusterIP on port 8080
- Route: HTTPS with edge TLS termination, hostname pacman.apps.hh.cszevaco.com
- ArgoCD project: steward-pacman
