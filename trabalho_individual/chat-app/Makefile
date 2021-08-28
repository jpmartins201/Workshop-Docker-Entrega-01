current_dir := $(shell pwd)
.PHONY: build

build:
	sudo docker build -t chat-app .

.PHONY: run

run:
	sudo docker run --rm -p 7001:7001 -it chat-app
