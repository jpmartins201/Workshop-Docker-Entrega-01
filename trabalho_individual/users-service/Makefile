current_dir := $(shell pwd)
.PHONY: build

build:
	sudo docker build -t users-service .

.PHONY: run

run:
	sudo docker run --rm -p 7101:7101 -it users-service
