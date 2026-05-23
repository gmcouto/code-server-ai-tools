ARG MOD_IMAGE
FROM lscr.io/linuxserver/code-server:latest AS base
FROM ${MOD_IMAGE} AS mod
FROM base
COPY --from=mod /etc/s6-overlay /etc/s6-overlay
