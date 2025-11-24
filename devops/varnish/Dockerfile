# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Érico Andrei <ericof@plone.org>" \
      org.label-schema.name="tredf-varnish" \
      org.label-schema.description="Treinamento TRE-DF Varnish image." \
      org.label-schema.vendor="Érico Andrei"

COPY etc/varnish.vcl /etc/varnish/default.vcl
