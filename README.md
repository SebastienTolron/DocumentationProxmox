# DocumentationProxmox
Command utiles pour proxmox

Commande générales 
vzctl enter 100
vzctl stop 100
vzctl start 100


OpenVpn

Si erreur de restart :
  Stop container 
  $ vzctl set 100  --devnodes net/tun:rw --capability net_admin:on --save
  Start container
  
  
