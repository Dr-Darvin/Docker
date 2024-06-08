# use an existing docker iage base 

FROM alpine

# download and install dependancies
RUN apk add --update redis

# tell container what to do when it starts
CMD ["redis-server"]