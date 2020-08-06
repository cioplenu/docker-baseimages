FROM alpine

RUN apk add --no-cache git									&& \
	wget 'https://github.com/phrase/phrase-cli/releases/download/2.0.13/phrase_linux_amd64'	&& \
	install ./phrase_linux_amd64 /usr/bin/phrase						&& \
	rm phrase_linux_amd64

ENTRYPOINT ["/usr/local/bin/phrase"]
