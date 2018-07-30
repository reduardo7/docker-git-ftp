git-ftp for Docker
==================

Simple Docker image for `git-ftp` functionality.

Use it as follows:

```bash
docker run --rm -i -v [/path/to/your/repo]:/repo reduardo7/docker-git-ftp git ftp init -u user -p password hostname
docker run --rm -i -v [/path/to/your/repo]:/repo reduardo7/docker-git-ftp git ftp push -u user -p password hostname
```
