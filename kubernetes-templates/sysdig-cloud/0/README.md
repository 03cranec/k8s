Installing Sysdig in k8s with Rancher<br>

The following kernel headers are necessary before deploying the agent using the rancher catalog.<br>

DOCKER<br>
$ sudo ros service enable kernel-headers<br>
$ sudo ros service up -d kernel-headers<br>


SYSTEM DOCKER<br>
$ sudo ros service enable kernel-headers-system-docker<br>
$ sudo ros service up -d kernel-headers-system-docker<br>
