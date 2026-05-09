# docker-images

Custom Docker images for personal projects, hosted on GHCR.

## Images

| Folder | Image | Description |
|--------|-------|-------------|
| `gitea-runner/` | `ghcr.io/<owner>/gitea-runner` | Gitea act runner base (ubuntu 22.04 amd64) |

## Build

Images build automatically on push to `main` when a `Dockerfile` changes.
To add a new image, create a folder with a `Dockerfile` — the workflow picks it up automatically.
