FROM bycedric/ci-node

LABEL maintainer 'Cedric van Putten <cedric@peakfijn.nl>'

RUN npm install -g \
		@peakfijn/config-stylelint \
		stylelint \
		stylelint-config-peakfijn \
		stylelint-config-styled-components \
		stylelint-processor-styled-components \
	&& npm cache rm --force
