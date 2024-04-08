Update your package index:
```
sudo apt update
```

Install prerequisites:

```
sudo apt install apt-transport-https ca-certificates curl software-properties-common
```

Add Docker’s official GPG key:


```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```


Set up the Docker repository:

```
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
```

Update the package index again:

```
sudo apt update

```

Install Docker:
```
sudo apt install docker-ce
```

Check Docker version:
```
docker --version
```

(Optional) Add your user to the docker group: This allows you to run Docker commands without sudo, which can be more convenient.
```
sudo usermod -aG docker ${USER}
```


#Now we can start to install Solgraph:
