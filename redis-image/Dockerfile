FROM alpine

RUN apk add --update redis
RUN apk add --update gcc

CMD ["redis-server"]

# notes
# docker build -t naufalathallah/redis:latest .
# docker run naufalathallah/redis