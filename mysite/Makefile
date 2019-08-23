
PHONY += chown-src
chown-src:
	sudo chown $(shell id -u):$(shell id -g) -R ./

PHONY += run
run:
	docker run --rm -it -v $PWD:/src jguyomard/hugo-builder hugo /bin/sh

