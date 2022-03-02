# OS_Docker_INIT

![version](https://img.shields.io/badge/Version-latest-da282a)  [![Docker Automated Build](https://img.shields.io/docker/automated/xrsec/osinit?label=Build&logo=docker&style=flat-square)](https://hub.docker.com/r/xrsec/osinit) [![OS Docker INIT](https://github.com/XRSec/OS_Docker_INIT/actions/workflows/OSINIT.yml/badge.svg)](https://github.com/XRSec/OS_Docker_INIT/actions/workflows/OSINIT.yml)

## USE

```dockerfile
FROM xrsec/osinit:centos
LABEL maintainer="xrsec"
LABEL mail="troy@zygd.site"
LABEL Github="https://github.com/XRSec/OS_Docker_INIT"
LABEL org.opencontainers.image.source="https://github.com/XRSec/OS_Docker_INIT"
LABEL org.opencontainers.image.title="OS_Docker_INIT"

RUN whoami

# ENV TZ='Asia/Shanghai'
# ENV LANG 'zh_CN.UTF-8'

# STOPSIGNAL SIGQUIT

CMD [ "/bin/bash"]
```
