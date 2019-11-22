FROM ruby:2.6.5-alpine

ENV BUNDLE_PATH="/github/workspace/vendor/bundle"
ENV LANG C.UTF-8

RUN echo @edge http://dl-cdn.alpinelinux.org/alpine/edge/community >> /etc/apk/repositories && \
  echo @edge http://dl-cdn.alpinelinux.org/alpine/edge/main >> /etc/apk/repositories && \
  apk add --no-cache \
  libstdc++@edge \
  libuv@edge \
  build-base \
  git \
  nodejs@edge \
  nodejs-npm@edge \
  yarn@edge
