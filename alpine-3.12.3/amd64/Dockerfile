FROM scratch

ARG BUILD_DATE
ARG VCS_REF

LABEL maintainer="Finbarrs Oketunji <oketunjifinbarrs@hotmail.com>" \
    architecture="amd64/x86_64" \
    alpine-version="3.12.3" \
    build="12-28-2020" \
    org.opencontainers.image.title="alpine" \
    org.opencontainers.image.description="Deploy a Docker image on Alpine Linux" \
    org.opencontainers.image.authors="Finbarrs Oketunji <oketunjifinbarrs@hotmail.com>" \
    org.opencontainers.image.vendor="Cloudeya Limited" \
    org.opencontainers.image.version="v0.0.1" \
    org.opencontainers.image.url="https://hub.docker.com/r/0xnu20/alpine/" \
    org.opencontainers.image.source="https://github.com/0xnu/alpine" \
    org.opencontainers.image.revision=$VCS_REF \
    org.opencontainers.image.created=$BUILD_DATE

ADD alpine-minirootfs-3.12.3-x86_64.tar.gz /
CMD ["/bin/sh"]
