FROM scratch

ARG BUILD_DATE
ARG VCS_REF

LABEL maintainer="Finbarrs Oketunji <f@finbarrs.eu>" \
    architecture="amd64/x86_64" \
    alpine-version="3.13.2" \
    build="2-23-2021" \
    org.opencontainers.image.title="alpine" \
    org.opencontainers.image.description="Deploy a Docker image on Alpine Linux" \
    org.opencontainers.image.authors="Finbarrs Oketunji <f@finbarrs.eu>" \
    org.opencontainers.image.vendor="Phooni Limited" \
    org.opencontainers.image.version="v0.0.1" \
    org.opencontainers.image.url="https://hub.docker.com/r/0xnu20/alpine/" \
    org.opencontainers.image.source="https://github.com/0xnu/alpine" \
    org.opencontainers.image.revision=$VCS_REF \
    org.opencontainers.image.created=$BUILD_DATE

ADD alpine-minirootfs-3.13.2-x86_64.tar.gz /
CMD ["/bin/sh"]
