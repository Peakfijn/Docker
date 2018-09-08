FROM bycedric/ci-node

LABEL maintainer 'Cedric van Putten <cedric@peakfijn.nl>'

RUN apk add --no-cache git \
	&& npm install -g \
		@peakfijn/config-commitlint \
		commitlint \
	&& npm cache rm --force
