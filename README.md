# Kubescape Docker Desktop extension
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fkubescape%2Fdocker-desktop-extension.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fkubescape%2Fdocker-desktop-extension?ref=badge_shield)


This is a Docker Desktop extension for Kubescape.
It lets you improve the security of your Kubernetes cluster by scanning it for misconfigurations and vulnerabilities.

For now, the extension supports visualising your results using the ARMO Platform dashboard. Support for Backstage, Grafana and the self-hosted Kubescape backend are on our roadmap.

## Using the development version

1. Clone this repo.
2. Change into the repo’s directory.
3. Run Docker Desktop.
4. Inside the Docker Desktop application, go to Settings → Kubernetes → Enable Kubernetes.
5. Run `make install-extension`.
6. A new extension named Kubescape should appear.


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fkubescape%2Fdocker-desktop-extension.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fkubescape%2Fdocker-desktop-extension?ref=badge_large)