# pihole-docker-compose-template

Docker-compose template for running pihole.  
Running pihole on a Raspberry Pi 4
- Have a seperate folder for the docker compose file 
- With the docker compose in the current directory run 
    - `docker-compose up -d` - this runs docker based on the `yml` docker-compose file parameters in detached mode 
- To access GUI, use `<IP Address of device>/admin`