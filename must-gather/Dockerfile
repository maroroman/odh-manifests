FROM quay.io/openshift/origin-cli:latest

# copy all collection scripts to /usr/bin
COPY collection-scripts/* /usr/bin/
RUN dnf install -y rsync

ENTRYPOINT /usr/bin/gather
