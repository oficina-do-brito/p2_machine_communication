# machine_communication

### Technologies used

#### Vagrant

-   It is a technology used to simulate the behavior of an operating system, widely used by devops for OS construction and production environment training.
-   It has cli, compatibility with windows, linux and debian etc.
-   its command and functioning interface is similar to docker and docker compose

#### Install Vagrant

- it is prerequisite to have virtualbox installed on your system

```
    sudo apt install virtualbox -y && 
    sudo apt install vagrant -y
```

### How to run project

### Useful commands for using the cli

-   create instance based on box

```
    vagrant up
```

-   check id of machines that are available

```
    vagrant global-status
```

-   Destroy a running machine

```
    vagrant destroy id_maquina -f
```

-   View images/creation base box

```
    vagrant box list
```

-   Accessing virtual machine via ssh. Vangrant already provides a shortcut for this

```
    vagrant ssh
```
