FROM node
COPY package.json /src/
RUN cd /src && npm install
WORKDIR /src
ENTRYPOINT ["node"]
