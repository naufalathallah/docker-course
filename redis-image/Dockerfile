FROM alpine

RUN apk add --update redis
RUN apk add --update gcc

CMD ["redis-server"]

# notes
# docker build -t naufalathallah/redis:latest .
# docker run naufalathallah/redis

# manual build (alternative)
# docker run -it alpine sh
# apk add --update redis
# docker commit -c 'CMD ["redis-server"]' <container_id> naufalathallah/redis:latest