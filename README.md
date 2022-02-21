# CNI-plugin-from-Scratch

Este repositorio muestra como emular el funcionamiento del network plugin bridge, utilizando bash y comandos de linux.

Esta implementacion es meramente una demostracion con fines didacticos y no es una solucion real.


## Tecnologias

### CNI

CNI es una implementacion que permite la abstraccion e implementacion de distintos plugins de red.

### CRI-O

CRI-O es un container runtime que integra el concepto de CRI (container runtime interface) con el concepto de OCI (Open Container Initiative) para su implementacion en Kubernetes.


### Kubeadm

Kubeadm es una herramienta que permite la creacion de un cluster de Kubernetes.


## Referencias

Esta demo hace uso del codigo y conceptos compartidos en:

- https://github.com/s-matyukevich/bash-cni-plugin
- https://github.com/mmirecki/cnidemo
- https://github.com/eranyanay/cni-from-scratch
- [Writing a CNI - as easy as pie Write you own CNI (Container Network Interface)](https://youtu.be/hDIcS66HpSk)
- [Kubernetes Networking: How to Write a CNI Plugin From Scratch - Eran Yanay, Twistlock](https://youtu.be/zmYxdtFzK6s)
- [Kubernetes Networking: How to Write Your Own CNI Plug-in with Bash](https://www.altoros.com/blog/kubernetes-networking-writing-your-own-simple-cni-plug-in-with-bash/)