git-ftp for Docker
==================

Simple Docker image for git-ftp functionality.

Use it as follows:

```
docker run --rm -i -v [/path/to/your/repo]:/repo init -u user -p password hostname
docker run --rm -i -v [/path/to/your/repo]:/repo push -u user -p password hostname
