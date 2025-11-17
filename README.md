# pihole-llistabloquejos
Llista de bloquejos per Pi-Hole de serveis de IA

  30  sudo service pihole-FTL stop
   31  sudo mv /etc/pihole/gravity.db /etc/pihole/gravity.db.BUIT
   32  sudo cp gravity.db /etc/pihole/gravity.db
   33  sudo chown pihole:pihole /etc/pihole/gravity.db
   34  sudo service pihole-FTL start
   35  pihole -g -r
   36  sudo pihole -g -r
   37  sudo pihole -g -r recover
   38  sudo sqlite3 /etc/pihole/gravity.db "select * from adlist;"
   39  sudo apt install sqlite3
   40  sudo sqlite3 /etc/pihole/gravity.db "select * from adlist;"
   41  sudo sqlite3 /etc/pihole/gravity.db "select * from domains;"

