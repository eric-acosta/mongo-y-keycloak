FROM mongo:4.4.1
LABEL maintainer="eacosta901@gmail.com"
ENV MONGO_INITDB_DATABASE=TEACHERBD
CMD ["/usr/bin/mongod","--bind_ip_all", "--replSet", "rs0"]
HEALTHCHECK --retries=1 \
	CMD /usr/bin/mongo --eval "rs.initiate()"
