## Prerequisites
- A machine with a supported OS (Linux, macOS, or Windows).
- Administrator/root access on the machine.
- Azure account for deploying on Azure Kubernetes Service (AKS).

### Install Necessary Tools

#### 1.1 Install Kubernetes Tools
- Using curl:
If you have curl installed, use this command:
curl.exe -LO "https://dl.k8s.io/release/v1.31.0/bin/windows/amd64/kubectl.exe"

- Using Chocolatey
  choco install kubernetes-cli

  - Test to ensure the version you installed is up-to-date:
  ` kubectl version --client`
