# Probabilistic programs
This repo contains a set of demo probabilistic programs in both psi and webppl to help people understand how to model real world problems using probabilistic programming languages.

Quickstart:

Get the docker container using the following commands:
  1.  Install docker using [this](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/#install-using-the-repository).
  2.  ```sudo docker pull sadutt/prob-ttr:v3```
  3.  ```sudo docker run --name probInst -it sadutt/prob-ttr:v3```

This has psi and webppl installed. To run any example,go to programs folder and run :

`psi psi/burglarAlarm.psi`

`webppl webppl/burglarAlarm.psi`

Alternatively, you can get the Virtualbox VM [here](https://drive.google.com/open?id=0BxHnQE_Hmlq_NGpMNzdiQUR2ejg) if you dont want to use docker.

