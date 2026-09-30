ABOUT
=====

A radically simple and opinionated role for Trivy security scanner.

In which sense opinionated?
- It does not install the APT repo
- It does not use APT at all
- It installs Trivy from a local or remote archive
- It sandboxes Trivy heavily using a Systemd Service

Why?
Prevention of Upstream Attacks.

State: Not complete but works so far.


TO DO
=====

- Enable configuration of Trivy


NOTES
=====

- https://trivy.dev/docs/v0.74/guide/scanner/secret#recommendation
- https://trivy.dev/docs/v0.74/guide/configuration/#configuration-file