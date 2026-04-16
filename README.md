# CLM Cloud Solutions krew Index

Custom [krew](https://krew.sigs.k8s.io/) plugin index for CLM Cloud Solutions
kubectl plugins.

## Available Plugins

### kubebolt

Instant Kubernetes monitoring — full cluster visibility in under 2 minutes.

```bash
# One-time: add this custom index
kubectl krew index add clm https://github.com/clm-cloud-solutions/krew-index.git

# Install
kubectl krew install clm/kubebolt

# Run
kubectl kubebolt
```

- **Website:** https://clm-cloud-solutions.github.io/kubebolt/
- **Repository:** https://github.com/clm-cloud-solutions/kubebolt
- **License:** MIT

## Usage

```bash
# List plugins from this index
kubectl krew search clm/

# Upgrade a plugin
kubectl krew upgrade clm/kubebolt

# Uninstall
kubectl krew uninstall kubebolt
```

## How this index works

Plugin manifests in this repository are **automatically generated** by release
workflows in the upstream project repositories. Each manifest points to
platform-specific archives published on GitHub Releases with verified SHA256
checksums.

Do not edit manifests manually — changes will be overwritten on the next release.

## Support

Open issues in the specific product repository:

- KubeBolt issues: https://github.com/clm-cloud-solutions/kubebolt/issues
