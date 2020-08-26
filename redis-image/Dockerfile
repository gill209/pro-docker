# Use an existing docker image aas a base
FROM alpine

#Download and install a dependency
RUN apk --update redis

#Tell the image what to do when it starts
#as a container
CMD ["REdis-server"]