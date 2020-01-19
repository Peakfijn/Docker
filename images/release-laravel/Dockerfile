FROM node:10-alpine

LABEL maintainer 'Cedric van Putten <cedric@peakfijn.nl>'

RUN apk add --no-cache \
		git \
		openssh-client \
	&& npm install -g --force \
		@peakfijn/config-release-laravel@2 \
		semantic-release@15 \
	&& npm cache rm --force
