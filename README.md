
# plonk-pi-explore-py

This repository is a master repo for a experimentation with the PLONK stack on Raspberry PI machines using Python as the language for functions.

## Resources
|Type|Video|Related|
|-|-|-|
|Video|[PI and K8S](https://youtu.be/ZiR3QEfBivk)|[Blog post](https://medium.com/@alexellisuk/walk-through-install-kubernetes-to-your-raspberry-pi-in-15-minutes-84a8492dc95a)|
|Video|[Setup PI via Ansible](https://youtu.be/vooBccHq6_4)|[Blog post](https://qmacro.org/2020/04/05/initial-pi-configuration-via-ansible/)|
|Training||[OpenFAAS](https://github.com/openfaas/workshop)|

## Tools
* [Ansible](https://www.ansible.com/) - automate provisioning, configuration, installation, etc.
* [Arkade](https://github.com/alexellis/arkade) - tool installer from repo
* [k3sup](https://github.com/alexellis/k3sup) - helper tool for installing k3s
* [k3s](https://rancher.com/docs/k3s/latest/en/) - lightweight k8s implementation
* [OpenFAAS](https://www.openfaas.com/)
  * [PLONK stack](https://www.openfaas.com/blog/plonk-stack/)
  * [Gateway](https://docs.openfaas.com/architecture/gateway/)
  * [NATS](https://github.com/nats-io) - tie functions to events (data streaming or messaging)
* kubernetes-dashboard

## K3S extensions
* inlets - get public IP
* Traefik
