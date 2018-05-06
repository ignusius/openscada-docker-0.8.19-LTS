# openscada-docker-0.8-LTS
OpenSCADA is an open implementation of SCADA (Supervisory Control And Data Acquisition) and HMI (Human-Machine Interface) systems.

http://oscada.org

# Install  
```docker pull iritoasutp/openscada-docker-0.8-lts```

# Run
```docker run -d --name openscada --publish 10002:10002  --restart=always -v ~/.openscada/:/root/.openscada/ iritoasutp/openscada-docker-0.8-lts```

where **~/.openscada** is you project.

# Contacts
Maintainer: Alexander Komarov ignusius@gmail.com
