FROM node:12-alpine

LABEL maintainer 'Cedric van Putten <cedric@peakfijn.nl>'

RUN apk add --no-cache \
		git \
		openssh-client \
	&& npm install -g --force \
		@peakfijn/config-release-expo@2 \
		semantic-release@15 \
	&& npm cache rm --force
