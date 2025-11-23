# Patch files

This directory contains patch files that can be applied to specific Gitea releases.

## Available patches

- `gitea-1.25.1-arch-repo-split-packages.patch`: addresses Arch package split-package collisions (e.g., `p11-kit` and `libp11-kit`) for Gitea 1.25.1.
- `gitea-1.25.1-arch-repo-split-packages.zip`: zipped version of the patch above for convenient download.

## Downloading

To download a patch directly from a Gitea instance or local clone, use one of the following commands from the repository root:

```sh
# Copy to a desired location (local checkout)
cp patches/gitea-1.25.1-arch-repo-split-packages.patch /tmp/
cp patches/gitea-1.25.1-arch-repo-split-packages.zip /tmp/

# Save from a remote repository (replace <BASE_URL> with your server origin)
curl -L "<BASE_URL>/patches/gitea-1.25.1-arch-repo-split-packages.patch" -o gitea-1.25.1-arch-repo-split-packages.patch
curl -L "<BASE_URL>/patches/gitea-1.25.1-arch-repo-split-packages.zip" -o gitea-1.25.1-arch-repo-split-packages.zip
```
