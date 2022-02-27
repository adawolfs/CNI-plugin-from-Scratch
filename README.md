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


## Live en La Hora de Kubernetes

### Parte 1
https://youtu.be/-rpKakmIr6Y

[Slides](https://docs.google.com/presentation/d/e/2PACX-1vSQSQLmNCsGL43tMlHHgjsU9CDSgk83z06Pw5G7eDvE_WpJSNll7sahpI2C8alt542TlL1uHManhX5y/pub?start=true&loop=true&delayms=3000)

### Parte 2
https://youtu.be/y16puleeXx0

[Slides](https://docs.google.com/presentation/d/e/2PACX-1vR8y1MCoRu1SOapIBKMVgNXhLK-XOGTDBEU-PbA9wIzkTICe5ibMsJVLgwvvYRcvZbXk4wpHrhw0-zZ/embed?start=true&loop=true&delayms=3000)

## Referencias

Esta demo hace uso del codigo y conceptos compartidos en:

- https://github.com/s-matyukevich/bash-cni-plugin
- https://github.com/mmirecki/cnidemo
- https://github.com/eranyanay/cni-from-scratch
- [Writing a CNI - as easy as pie Write you own CNI (Container Network Interface)](https://youtu.be/hDIcS66HpSk)
- [Kubernetes Networking: How to Write a CNI Plugin From Scratch - Eran Yanay, Twistlock](https://youtu.be/zmYxdtFzK6s)
- [Kubernetes Networking: How to Write Your Own CNI Plug-in with Bash](https://www.altoros.com/blog/kubernetes-networking-writing-your-own-simple-cni-plug-in-with-bash/)