FROM alpine:3.12

# bind-tools contain `dig`, `nslookup`, etc.
RUN apk add --no-cache \
    bash \
    bind-tools \
    curl \
    git

ENTRYPOINT ["/bin/bash"]
