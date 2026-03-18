# argocd-vm-demo
Demo for deploying kubevirt VMs with ArgoCD

Create an ArgoCD Application to point to the repo root.

## Add a new VM
- Create a new overlay with the cusomizations needed.
- Add that overlay to resources in /kustomization.yaml.
- Create/Merge a PR with the main branch.