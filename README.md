# docker nginx + php-fpm
A docker container to run sf2 apps under nginx and php-fpm


````
docker run -p 80:80 -p 443:443 --name sf2 -v /path/to/sf2/root:/var/app/current:rw -d sf2
````

The mounted volume expects to have a `/web` folder in the root, as it is in symfony 2 apps.

---

**Mac users:** Locate your guest IP address by running `docker-machine ls` or by opening *Kinematic*
