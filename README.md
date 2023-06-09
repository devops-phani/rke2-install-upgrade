# rke2-install-upgrade

Master node upgrade or install

```
curl -sfL https://get.rke2.io | INSTALL_RKE2_TYPE="server" INSTALL_RKE2_VERSION="v1.25.10+rke2r1" sh -
```

Worker node upgrade or install

```
curl -sfL https://get.rke2.io | INSTALL_RKE2_TYPE="agent" INSTALL_RKE2_VERSION="v1.25.10+rke2r1" sh -
```

Reference links
- https://docs.rke2.io/install/quickstart
- https://docs.rke2.io/install/methods
- https://docs.rke2.io/upgrade/manual_upgrade
- https://docs.rke2.io/upgrade
- https://docs.rke2.io/install/methods
- https://docs.rke2.io/install/containerd_registry_configuration
