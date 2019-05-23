FROM node:10-alpine

LABEL maintainer 'Cedric van Putten <cedric@peakfijn.nl>'

RUN apk add --no-cache \
		git \
		openssh-client \
	&& npm install -g \
		@peakfijn/config-release-react \
		semantic-release \
	&& npm cache rm --force
