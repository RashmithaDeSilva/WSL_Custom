# WSL Custom

### Create folder where you want to store it
```sh
mkdir MyLinuxEnv
```
---

### Import from existing WSL export or custom rootfs

* https://cloud-images.ubuntu.com/wsl/
* https://cloud-images.ubuntu.com/wsl/jammy/current/

```sh
# wsl --import [DistroName] [InstallLocation] [TarballPath] [--version 2]
wsl --import ubuntu22.04 .\ .\ubuntu-jammy-wsl-amd64-ubuntu22.04lts.rootfs.tar.gz --version 2
```
---

### Start/Stop your environment like a container
```sh
wsl -d ubuntu22.04
wsl --terminate ubuntu22.04
```

