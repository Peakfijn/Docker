FROM node:10-alpine

LABEL maintainer 'Cedric van Putten <cedric@peakfijn.nl>'

RUN apk add --no-cache git \
	&& npm install -g \
		@peakfijn/config-commitlint \
		commitlint \
		commitlint-format-junit \
	&& npm cache rm --force
