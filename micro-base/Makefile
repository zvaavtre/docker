#
# A base image that is useful for launching springboot jar files
#

TAG=latest

build: 
	docker build --squash -t zvaavtre/micro-base .

push: build
	docker push zvaavtre/micro-base:${TAG}
