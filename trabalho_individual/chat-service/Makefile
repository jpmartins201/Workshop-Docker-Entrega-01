current_dir := $(shell pwd)
.PHONY: build

build:
	sudo docker build -t chat-service .

.PHONY: run

run:
	sudo docker run --rm -p 7100:7100 -it chat-service
