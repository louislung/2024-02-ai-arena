# note foundry is based on alpine
FROM ghcr.io/foundry-rs/foundry:nightly-a44159a5c23d2699d3a390e6d4889b89a0e5a5e0

# for install slither in alpine-linux
RUN apk add py3-pip
RUN python3 -m pip install slither-analyzer

# for viewing dot file
RUN apk add --upgrade graphviz-dev