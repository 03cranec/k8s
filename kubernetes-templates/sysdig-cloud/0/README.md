Installing Sysdig in k8s with Rancher

The follwing kernel headera are necessary before deploying the agent using the rancher catalog.

DOCKER
$ sudo ros service enable kernel-headers
$ sudo ros service up -d kernel-headers


SYSTEM DOCKER
$ sudo ros service enable kernel-headers-system-docker
$ sudo ros service up -d kernel-headers-system-docker
