FROM node:12-alpine

LABEL maintainer 'Cedric van Putten <cedric@peakfijn.nl>'

RUN apk add --no-cache git \
	&& npm install -g --force \
		@peakfijn/config-commitlint@2 \
		commitlint@8 \
		commitlint-format-junit@1 \
	&& npm cache rm --force
