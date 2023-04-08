FROM node:18-bullseye
RUN apt-get update

RUN apt-get update && apt-get install -y \
    vim less

WORKDIR /src

#CMD ["tail", "-f", "/dev/null"]
CMD ["npx", "json-server", "--watch", "db.json"]
