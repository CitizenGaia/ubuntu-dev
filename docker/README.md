
```
sudo apt-get update 
```

```
sudo apt install docker.io -y
```

# https://docs.docker.com/install/linux/linux-postinstall/#manage-docker-as-a-non-root-user 

Create the docker group.
```
sudo groupadd docker
```

Add your user to the docker group.
```
sudo usermod -aG docker $USER
```

Logout and Login again
```
docker version
```

Run docker hello-world to verify installation of docker and sudo-stuff
```
docker run hello-world
```


