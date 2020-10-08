FROM debian:buster

# bind-tools contain `dig`, `nslookup`, etc.
RUN apt-get update -y &&
    apt-get install -y \
        curl \
        git \
        traceroute &&
    apt-get clean

ENTRYPOINT ["/bin/bash", "-c"]
CMD ["echo 'Default command is used, exiting. You may want to override the command to use the toolkit.'"]
