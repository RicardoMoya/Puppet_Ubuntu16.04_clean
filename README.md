# Ubuntu 16.04

Modulo de puppet creado en la web:

https://puphpet.com/

### Prerequsitos

Hay que tener instalado:
1. Virtualbox
2. Vagrant

## Droplet

Este proyecto contiene un modulo de puppet para desplegar con Vagrant un Ubuntu 16.04 limpio (salvo vim y htop)

## Despliegue

Una vez intalado virtualbox y vagrant, nos vamos a la carpeta donde esta el fichero "Vagrantfile" y hacemos:

```
vagrant up
```

Tardara unos minutos en crearse la máquina.

Una vez creada podemos acceder por ssh con:

```
vagrant ssh
```
