# syntax=docker/dockerfile:1.3
# Use a consistent platform image for macOS/Linux builds
FROM --platform=$TARGETPLATFORM nginx:1.25-alpine

ENV FRAME_ANCESTORS ""

COPY nginx.conf /etc/nginx/nginx.conf
COPY default.conf.template /etc/nginx/templates/
