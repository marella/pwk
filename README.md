Sample scripts and manifests for playing with Kubernetes.

## Installation

```sh
curl -sL https://file.marella.me/pwk/latest/install.sh | bash
```

## Usage

Initialize cluster and follow instructions to add worker nodes:

```sh
kube init
```

Create resources using a configuration file:

```sh
kube up https://file.marella.me/pwk/latest/echo.yaml
```

Delete resources using a configuration file:

```sh
kube down https://file.marella.me/pwk/latest/echo.yaml
```

Use `kubectl` commands:

```sh
kube get all
```
