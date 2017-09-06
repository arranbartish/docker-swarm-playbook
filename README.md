### Run with an existing ansible container


```
$ docker run -it -v ~/.ssh:/ssh -v ~/dev/docker-swarm-playbook:/files arranbartish/provisioning "ansible-playbook /files/playbook.yml -i /files/hosts --ask-sudo-pass" 
```
