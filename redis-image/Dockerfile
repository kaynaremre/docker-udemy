# Use an existing docker image as a base
FROM alpine

# Download and install a dependency

run apk add --update redis

# Tell the image waht to do when it starts as a container

CMD ["redis-server"]