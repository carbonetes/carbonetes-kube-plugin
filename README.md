[![Carbonetes](https://cdn.carbonetes.com/carbonetes-plugin/assets/branding/branding_header.png)](https://carbonetes.com)

# Carbonetes CLI Plugin

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/kubectl-carbonetes-scan)](https://artifacthub.io/packages/search?repo=kubectl-carbonetes-scan)

This repository serves as a host to our plugin for `OpenShift CLI (oc)` and `Kubernetes command-line tool (kubectl)`.

## oc and kubectl plugins

> An independent executable file which helps users on different tasks while using the CLI. Typically, these plugins starts their name with, `oc-` or `kubectl-`.

**`Carbonetes`** provides comprehensive container analysis and policy evaluation as a fully managed service. Carbonetes analyzes your container images for native code vulnerabilities, software composition analysis (SCA), license types, malware, secrets and bill of materials.

To know more about Carbonetes, check [our website](https://carbonetes.com).

## Custom Index via `Krew`

[Krew](https://krew.sigs.k8s.io/) is a kubectl plugin manager and also a kubectl plugin itself. You can easily [install](https://krew.sigs.k8s.io/docs/user-guide/setup/install/) it with only a few steps.

* Add Carbonetes Custom Index via Krew
    ```sh
    $ kubectl krew index add carbonetes https://github.com/carbonetes/carbonetes-kube-plugin.git
    ```
* Install `carbonetes-scan` via Krew
    ```sh
    $ kubectl krew install carbonetes/carbonetes-scan
    ```

Visit [carbonetes-scan repo](https://github.com/carbonetes/kubectl-carbonetes-scan) for more installation procedures.

## Support
To help with this plugin, or have an issue or feature request, please contact: [eng@carbonetes.com](eng@carbonetes.com)

If reporting an issue, please include:

* the version of the plugin
* relevant logs and error messages
* steps to reproduce

## License and Copyright

Copyright © 2021 Carbonetes

Licensed under [MIT License](LICENSE).