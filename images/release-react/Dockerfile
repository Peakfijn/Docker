FROM node:12-alpine

LABEL maintainer 'Peakfijn <online@peakfijn.nl>'

RUN apk add --no-cache \
		git \
		openssh-client \
	&& npm install -g --force \
		@peakfijn/config-release-react@2 \
		semantic-release@15 \
	&& npm cache rm --force
