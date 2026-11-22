# BambuBoard for Unraid

This repository hosts the Unraid Community Apps template for [BambuBoard](https://github.com/t0nyz0/BambuBoard). The template pulls the stable image from GitHub Container Registry and maps the Unraid server's port 18080 to the app. Change the host port if that port is in use.

A new install stores its settings, Cloud token, scenes, and cache in the Docker volume `bambuboard-data`. Include the volume in backups and reuse it on updates. For an existing bind-mount installation, follow the [BambuBoard Docker upgrade steps](https://github.com/t0nyz0/BambuBoard/blob/v3.3.2/README.md#upgrading-an-existing-docker-installation) and keep that mount when configuring the container.

Report issues in [BambuBoard's issue tracker](https://github.com/t0nyz0/BambuBoard/issues).
