FROM alpine:3.12

# bind-tools contain `dig`, `nslookup`
RUN apk add --no-cache \
    bash \
    bind-tools \
    curl \
    git

ENTRYPOINT ["/bin/bash"]
