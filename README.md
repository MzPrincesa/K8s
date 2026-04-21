# K8s

A basic study of Kubernetes with commonly used commands and setup steps.

---

## Install Minikube

Start by visiting the official installation guide:
[https://minikube.sigs.k8s.io/docs/start/?arch=%2Fwindows%2Fx86-64%2Fstable%2F.exe+download](https://minikube.sigs.k8s.io/docs/start/?arch=%2Fwindows%2Fx86-64%2Fstable%2F.exe+download)

Before installing, choose a container or virtual machine manager from the **“What you’ll need”** section.

---

## Using Docker as the Driver

If you plan to use Docker:

* Minikube Docker driver guide:
  [https://minikube.sigs.k8s.io/docs/drivers/docker/](https://minikube.sigs.k8s.io/docs/drivers/docker/)

* Install Docker Desktop:
  [https://docs.docker.com/desktop/](https://docs.docker.com/desktop/)

Docker Desktop includes:

* Docker Engine
* `kubectl` (so no separate installation is required)

For Linux users who prefer Docker Engine only:
[https://docs.docker.com/engine/install/](https://docs.docker.com/engine/install/)

> ⚠️ When installing Docker Desktop, run the installer as an administrator since it requires elevated privileges.

---

## Install Minikube

Once Docker (or your preferred driver) is set up, proceed with Minikube installation using the official guide linked above.

---

## Notes

* On Windows, after installing Minikube, **restart your terminal** before running any commands.
* Ensure Minikube and kubectl are available in your system `PATH`.

---
