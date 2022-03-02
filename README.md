# OS_Docker_INIT

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
