# image-mirror

Mirror container images using Skopeo to the container registry of your choice

## Prerequisites

- Skopeo
- Already logged into the destination container registry (via `skopeo`, `podman`, or `docker`)
 
## Usage

```bash
$ ./image-mirror.sh quay.io/my-org
```

## Contribute

Add your image to the file `mirror_list.txt` to be run as part of the repository workflow push job and the cron job
