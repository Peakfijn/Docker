FROM docker:stable

LABEL maintainer 'Peakfijn <online@peakfijn.nl>'

RUN apk add --no-cache bash curl git nodejs nodejs-npm \
	&& npm install -g npm@latest \
	&& npm set progress=false \
	&& npm cache rm --force \
	&& curl https://cli-assets.heroku.com/install.sh | sh
