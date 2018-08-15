FROM bycedric/ci-node

LABEL maintainer 'Cedric van Putten <cedric@peakfijn.nl>'

RUN apk add --no-cache \
		git \
		openssh-client \
	&& npm install -g \
		semantic-release \
		@peakfijn/config-release-laravel \
	&& npm cache rm --force
