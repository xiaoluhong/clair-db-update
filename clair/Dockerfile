ARG  CLAIR_VERSION=${CLAIR_VERSION}

FROM quay.io/coreos/clair:${CLAIR_VERSION}

COPY config.yaml /config/config.yaml

CMD ["-config=/config/config.yaml"]
